Engineering Candidate Test

## Task

You are to write a callback event registry.

## Specifications

Event will have three methods: .on, .off and .emit.
 
.on will accept two parameters: a string used to identify the event and a function callback.
.off will accept one parameter: a string used to identify the event.
.emit will accept one parameter: a string used to identify the event.

* Function callbacks registered with .on will be executed by calling .emit with the same string with which the callback was registered.
* Any function callbacks triggered by .emit must execute asynchronously
* Function callbacks will be deregistered with .off. Once deregistered, these callbacks will no longer execute when .emit is called.
* Multiple callbacks may be registered against one event.
* Multiple events may be registered.
 
## Language

You may complete the exercise in either Typescript or Javascript.

## Tests

Unit tests are expected. We have provided a Jest harness but they may be completed in any framework with which you are comfortable.

* All unit tests must be perfomed with the module's public API
* Run tests using npm test
* Watch using npm test:watch
* A test harness has been provided for both Typescript and Javascript. You should delete whichever is not appropriate.

##Bear in mind

* You have 75 minutes to complete the test.
* You should treat this exercise as a pair programming session.
* You may use online resources such as API documentation.
* Googling solutions is not permitted.