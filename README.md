# Unclosed File Bug in Python

This repository demonstrates a common error in Python: failing to close a file after opening it. This can lead to resource leaks, especially when dealing with many files or large files.  The bug is shown in `bug.py` and the solution in `bugSolution.py`.

**Bug:** The function `function_with_unclosed_file` opens a file but neglects to close it, resulting in a potential resource leak. 

**Solution:** The solution involves using a `with` statement which automatically closes the file, ensuring the release of resources.
