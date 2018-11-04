# 537make

A reproduction of the basic functionality of make, including makefile parsing, dependency checking, and command execution.

## Files

* `in.txt` contains a sample valid makefile

* `blank.txt` contains several empty lines (no spaces)
* `spaces.txt` contains several lines that contain zero or more spaces

## Testing

Running `make test` automatically compiles and tests the code. The tests should output "SUCCESS" in green at the end. Manually inspect the output to make sure:
* Every file in the "FAILURES" section fails.
