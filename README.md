# A BDD variant of shunit2

A slightly modified version of shunit2 that uses BDD rather than TDD naming conversions. This repository only contains the modified `shunit2` script. For full details on `shunit2` see the [official website][shunit2]

## Main Differences

* Test names start `should` not `test`
* Test names are printed as sentences (e.g. `shouldCopyFile` is dispalyed as 'should: Copy File'
* Improved output for `assertTrue`

[shunit2]: https://code.google.com/p/shunit2/
