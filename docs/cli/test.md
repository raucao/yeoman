## test

Usage: `yeoman test`

Runs a Jasmine test harness in a headless instance of Phantom.js.

When you generate a new project using `yeoman init`, we also scaffold out a basic set of
Jasmine unit tests that you can continue using to test your application. 

Running `yeoman test` allows you to easily check if all of your tests are passing. This also
gets called when running `yeoman build`.

Example:

```shell
yeoman test

# outputs:

Running "jasmine:all" (jasmine) task
Running specs for index.html
.....................................................
>> 82 assertions passed in 53 specs (562ms)

Done, without errors.
```