# Lesson 3.1: generate

## Problem statement

Write an app which spits out an infinite series of "hello" messages to the debugging console.

You can use [problem/RxSwiftButtonBackgroundColorDemo](problem/RxSwiftButtonBackgroundColorDemo) included in this repo as a starting point.

**Note**: I have omitted the `Carthage` folder from the problem project, because it includes large binary files.  In order to use the this project, you will need to run `carthage update --platform iOS`.

## Solution

My solution is included in the [solution](solution) folder of this repo.

**Note**: I have omitted the `Carthage` folder from the solution project, because it includes large binary files.  In order to run the this project, you will need to run `carthage update --platform iOS`.

### Discussion:

We introduce `func generate()` and use it to create an Observable.

`ViewController.swift`:

```swift
```

#### New concepts to explore

* Open up `RxExample.xcodeproj`.
  * Take a look at `func generate` in `Observable+Creation.swift`