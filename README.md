# 345InterpreterTestSuite

In order to run this, you'll first want to move the file into your interpreter's directory. Then change the first line of the file to load the name of your interpreter file. 

To run the tests, call "runObjectTests" taking two parameters representing the range of tests you want to run. There are 22 tests for this part of the interpreter, so if you wanted to run them all, for example, call (runObjectTests 1 22).

If you have any problems running a test that stops the next tests from running (for example, test 5 caused an infinite loop for us for a while) just change the class being called in "getClassToRun" to some arbitrary class that does not match the one you should be calling.

