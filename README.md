[build-system]
requires = ["setuptools>=61.0"]
build-backend = "setuptools.backends.legacy:build"

[project]
name = "my-unique-library-name"         # ← CHANGE THIS to your unique PyPI name
version = "0.1.0"
description = "A simple Python utility library with string and math helpers."
readme = "README.md"
license = { file = "LICENSE" }
authors = [
    { name = "Your Name", email = "your@email.com" }   # ← CHANGE THIS
]
requires-python = ">=3.8"
keywords = ["utilities", "strings", "math"]
classifiers = [
    "Programming Language :: Python :: 3",
    "License :: OSI Approved :: MIT License",
    "Operating System :: OS Independent",
]

[project.urls]
Homepage = "https://github.com/yourusername/my_library"   # ← CHANGE THIS
