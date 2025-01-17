# Change Log

## Version 1.0.1

_2019-08-02_

Fixed a publishing issue. All artifacts should now be available on Maven Central.

## Version 1.0.0

_2019-08-02_

This is the initial release of Blueprint - a collection of Architectural frameworks and toolkits for bootstrapping modern Android codebases.

* New: **blueprint-interactor-coroutines** artifact - supports building Interactors based on Kotlin Coroutines and Flow.
* New: **blueprint-interactor-rx2** artifact - supports building Interactors based on RxJava 2.
* New: **blueprint-interactor-rx3** artifact - supports building Interactors based on RxJava 3. Note that it currently uses RxJava 3.0.0-RC1, and RxAndroid has not yet been updated to target RxJava 3.x yet.
* New: **blueprint-threading-coroutines** artifact - provides encapsulation of threading behavior with Kotlin `CoroutineDispatcher`.
* New: **blueprint-threading-rx2** artifact - provides encapsulation of threading behavior with RxJava 2 `Scheduler`.
* New: **blueprint-threading-rx3** artifact - provides encapsulation of threading behavior with RxJava 3 `Scheduler`. Note that it currently uses RxJava 3.0.0-RC1, and RxAndroid has not yet been updated to target RxJava 3.x yet.
* New: **blueprint-ui** artifact - Kotlin extensions and widgets for working with the Android UI toolkit.
* New: **blueprint-testing-robot** artifact - UI testing framework and DSL for authoring structured, readable, and framework-agnostic UI tests.
