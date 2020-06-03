---
title: Flutter Interview Questions
---

* What is the difference between a `StatelessWidget` and a `StatefulWidget` in Flutter?
* Explain the  Stateful Widget Lifecycle?
* When do you use the `WidgetsBindingObserver`?
* What is Flutter tree shaking?
* What is a `Spacer` widget?
* What is the difference between hot restart and hot reload?
* What is an `InheritedWidget`? List some examples.
* Why is the `build()` method on `State` and not `StatefulWidget`s?
* What is a pubspec file in Dart?
* How is Flutter native?
* What is a `Navigator` and what are `Routes` in Flutter?

  Navigator is used to navigate from one page to another in flutter. Routes represent the source and destination page.

* What is a `PageRoute`?

  The route of transition of one page to another is page route. i.e CupertinoPageRoute, MaterialPageRoute 

* Explain `async`, `await` and `Future`s.

  Async : It is used to maek a function asynchronous.
  Await : Await is used to execute a function asynchrooursly.
  Future : It value which the async function return is returned in a Future.

* How can you update a `ListView` dynamically?
* What is a `Stream`?

  Stream : A stream is a flow of data. It is like a pipe. Data is entered from one end and all the listeners listening to it   at other end will receive the data. 

* What are keys in Flutter and when should you use it?
  
  Keys are the property which are found in almost every constructors widget. Keys are basically used for preserving the state   of the widget while the widget updates of the collection modifies. For eg. we can use keys to presenve the scroll location   of the list.    

* What are `GlobalKeys`?

  global key is unique across the app.

* When should you use `mainAxisAlignment` and `crossAxisAlignment`?
  
  Main axis alignment is the axis along the direct of the widget. eg. mainaxis for a column is vertical and for a row is       horizontal.

* When can you use `double.INFINITY`?

  double.infinity is used we we want our widget to be as big as its parent allows.

* What is `Ticker`, `Tween` and `AnimatedBuilder`?

  Ticker : A ticker is a class that listens to frameCallback and calls a tick function that passes the elapsed duration                  between the current frame and the last frame to the ticker listener. 
  
  Tween : Tween means in-between. A linear animation between a start and an end value.
  
  AnimatedBuilder : Animatedbuilder knows how to render the animation.
  
  AnimationController : It controls the animation. It produces a new value for every frame which is rendered on the screen                           during animatonand provides functionality for the play, pause or stop the animation.

* What is ephemeral state?

  Ephemeral state is the state of the UI at a given point of time.(NOTE : It is not app state)

* What is an `AspectRatio` widget used for?

  Aspect ratio widget is used to resize the widget or a widget tree according to a given ratio of width and height of the       screen.

* How would you access `StatefulWidget` properties from its State?

  widget.property_name

* Is there a suggested limit to the number of `FloatingActionButton`s a screen can have? Give a reason(s) for your answer

  No

* Mention two or more operations that would require you to use or return a Future.

  1. Fetching data from api.
  2. Starting a counter for a task.
