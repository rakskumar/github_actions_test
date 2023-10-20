# pytest-example
pytest - Python Testing Example

This is a simple example of how to use pytest to integreate testing in your Python application.


## Usage
This example comes with several test files (e.g. test_app.py, test_funcs.py, etc.).

## Code Structure

```
myapp/
    app.py
    mymodule/
        __init__.py
        funcs.py
tests/
    __init__.py
    test_app.py
        mymodule/
            __init__.py
            test_additions.py
            test_funcs.py
```


## how to execute the pytest

pytest tests/ --html-report=./report/report.html