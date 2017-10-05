# Espresso test

Testing user interactions within a single app helps to ensure that users do not encounter unexpected results or have a poor experience when interacting with your app. You should get into the habit of creating user interface (UI) tests if you need to verify that the UI of your app is functioning correctly.

The Espresso testing framework, provided by the Android Testing Support Library, provides APIs for writing UI tests to simulate user interactions within a single target app. Espresso tests can run on devices running Android 2.3.3 (API level 10) and higher. A key benefit of using Espresso is that it provides automatic synchronization of test actions with the UI of the app you are testing. Espresso detects when the main thread is idle, so it is able to run your test commands at the appropriate time, improving the reliability of your tests. This capability also relieves you from having to add any timing workarounds, such as Thread.sleep() in your test code.

The Espresso testing framework is an instrumentation-based API and works with the AndroidJUnitRunner test runner.


![attachment](https://user-images.githubusercontent.com/16405013/31254946-ed8ec96a-aa2a-11e7-80b2-ddd414db2860.png)


===============================================================================

### Prerequisites

What things you need to install the software and how to install them

![ghdh](https://user-images.githubusercontent.com/16405013/31255004-1d889f6a-aa2b-11e7-86bd-e32f1fc9ebea.png)


### Installing

A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests
