================
November journal
================

10.11 - 13.11.2025
==================
This week, I focused on Github Actions, making the workflow as efficient as possible. Key activities included: Researching best practices for CI/CD pipelines, implementing caching strategies to speed up build times, and testing various deployment scenarios to ensure reliability. I also documented the workflow setup for future reference.
A notable challenge was troubleshooting a persistent build failure, which I resolved by adjusting the configuration settings. Overall, significant progress was made in optimizing the CI/CD process.

I discovered Astral uv and ruff, which I plan to integrate into future workflows. Uv is an extremely fast Python package and project manager, written in Rust. It's a drop-in replacement for pip and virtualenv, designed to be faster and more efficient.
Ruff is a super fast Python linter and formatter, written in Rust. It aims to provide the same functionality as traditional linters like Flake8 and formatter like black, but with significantly improved performance.

Pytest learned about fixture and monkeypatch. Fixtures are a way to provide a fixed baseline upon which tests can reliably and repeatedly execute. They help in setting up the necessary context for tests, such as initializing objects or preparing data.
Monkeypatching is a technique used in testing to modify or replace parts of the system under test. It allows you to change the behavior of functions, classes, or modules during test execution, enabling you to isolate the code being tested and control its dependencies.

At-Com in Susten accompanied by Gilles, we tested the side cameras on Komatsu. Diffrent settings were tried, and we found that the cameras work well in low light but struggle in bright light conditions.
The transisition from low light to bright light caused overexposure, making it difficult to capture clear videos. Tele-opration was also tested, and it was found that the response time was great, with minimal timeout issues.
Thanks to the side cameras, blind spots that were previously not visible could be seen, enhancing safety during operations.
