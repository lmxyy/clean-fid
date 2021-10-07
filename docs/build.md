
## Compiling locally
```
    python setup.py bdist_wheel
```

## Installing locally
```
    python -m pip install dist/clean_fid-0.1.14-py3-none-any.whl --force-reinstall
```

## Run the tests locally
 - set the version number in line 3 in `tests/setup.py`
 - run `bash tests/tests_main.sh`
 - ensure that there are not Errors thrown in the logfile
```
    
```