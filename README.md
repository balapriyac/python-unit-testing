# ⚙ Unit Testing in Python

- [Example 1: Writing unit tests for Python functions](https://github.com/balapriyac/python-unit-testing/tree/main/unit-test-1)
- [Example 2: Writing unit tests for instance methods](https://github.com/balapriyac/python-unit-testing/tree/main/unit-test-2)

-----
To add Sentry to your Python projects, install Sentry's Python SDK:

```bash
pip install --upgrade sentry-sdk
```

After installing, you can import and configure Sentry by adding the following lines of code:
```python
import sentry_sdk
sentry_sdk.init(
    dsn="your-dsn-here",
    traces_sample_rate=<sample-rate>, # between 0 and 1
)
```
