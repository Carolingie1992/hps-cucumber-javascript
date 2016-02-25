# hps-cucumber-javascript

<Travis build status>

Hiptest publisher samples with Cucumber/Javascript

In this repository you'll find tests generated in Cucumber/Javascript format from [Hiptest](https://hiptest.net), using [Hiptest publisher](https://github.com/hiptest/hiptest-publisher).

The goals are:

 * to show how tests are exported in Cucumber/Javascript.
 * to check exports work out of the box (well, with implemented actionwords)

System under test
------------------

The SUT is a (not that much) simple coffee machine. You start it, you ask for a coffee and you get it, sometimes. But most of times you have to add water or beans, empty the grounds. You have an automatic expresso machine at work or at home? So you know how it goes :-)

Update tests
-------------


To update the tests:

    hiptest-publisher -c cucumber-js.conf --only=features,step_definitions

The tests are generated in [``<path the tests>``](<github path to tests>)

Run tests
---------


To build the project and run the tests, use the following command:

    <command to run the tests with report>

The SUT implementation can be seen in [``<path to sut>``](<github path to sut>)

The test report is generated in ```<path to test report>```

