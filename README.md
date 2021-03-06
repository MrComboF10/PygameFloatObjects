# PygameFloatObjects

Improved pygame objects to store float attributes.

This module helps pygame developers to create objects like rect, circle and fonts, and store float values like size and coordinates in order to update them during the game without losing precision.

## Commands

### Install

```
py -m pip install PygameFloatObjects
```

### Upload to PyPI

```
py setup.py sdist
py -m twine upload dist/*
```

### Release new version to PyPI

Update version number in setup.py
```
py setup.py sdist
py -m twine upload --skip-existing dist/*
```

## Run examples

```
from PygameFloatObjects.examples import rect_example

rect_example.rect_example()
```
Click on the pygame window with the left and right buttons to see what happens!
