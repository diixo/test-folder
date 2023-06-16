## test-folder

Check packages before: 
```
pip list
```

### Install build environment
```
pip install build
```

### Build whl package
```
py -m build --wheel
```

### How to use
Run from **git-directory**:
```
pip install ./dist/test_folder-0.1.1-py3-none-any.whl
```
