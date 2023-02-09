# FLUTTER INTERVIEW BOOK

1. ### Explain isolates and How isolates run on event loop?
2. ### How isolates shares data?
3. ### Compare `Isolate.spawn` and `compute`  method.
4. ### What is Skia? 
    
    Skia is an open-source 2D graphics library that is used to render graphics and text in a variety of environments, including Flutter.

    Skia provides a complete solution for 2D graphics, including vector graphics, raster graphics, and text rendering. It supports a wide range of             platforms, including Windows, macOS, iOS, Android, and Linux, and it can be used on various hardware configurations, from low-end embedded systems to       high-performance desktop machines.

   Flutter uses Skia as its primary rendering engine to draw the graphical elements on the screen. When you build a Flutter app, the Flutter framework        compiles the Dart code into native code and uses Skia to render the graphics.

   Skia is designed to be fast, efficient, and scalable, and it provides a rich set of features that are useful for creating high-quality, responsive, and    visually appealing applications. Because Skia is an open-source project, developers can easily contribute to its development and make modifications to      the library if necessary.

5. ### Why is Impeller introduced as new Flutter Engine and what is the difference between skia and impeller?
6. ### What are keys in flutter and discuss there usage?
7. ### What is the difference between `async` and `async*`?
   
   In Dart, the difference between async and async* lies in the type of functions they define and the way they handle asynchronous operations.

   An async function is a function that is marked as asynchronous and can be used to perform asynchronous operations. It returns a Future object, which       represents a value that will be available at some point in the future. An async function can be used to perform operations such as reading from a file,     making an HTTP request, or waiting for a timer to complete.

    An async* function, on the other hand, is a generator function that is marked as asynchronous. It allows you to yield values as they become available,      rather than waiting for all the results to be available before returning a single value. This is useful when working with large collections of data or      when performing operations that can produce a large number of results. An async* function returns a Stream object, which is a sequence of asynchronous      events.

   In summary, the main difference between async and async* is that async functions return a single Future value, while async* functions return a Stream of    values. async functions are useful when you want to perform a single asynchronous operation and wait for the result, while async* functions are useful      when you want to perform multiple asynchronous operations and yield results as they become available.

8. What is the difference between `Ticker` and `Timer`?
9. What is `vsync` ? and where is it used?
10. What is the difference between `Image.asset` and `AssetImage`?
11. Expalin `TickerProvierStateMixin` and `SingleTickerProviderStateMixin`?
12. What is the difference between `Navigator.pushNamed` and `Navigator.pushReplacementNamed`?
13. What are `abstract`, `const`, `final` keywords in Flutter?
14. What is the difference between `const` and `final` keywords?
15. What is the difference between `SizedBox` and `Container`?
16. What is Named, factory, and default constructors?
17. Explain the lifecycle of the Flutter application?
18. what is the difference between packages & plugins?
19. Explain the flutter framework.
20. How does widget rendering happen in flutter?
21. What is the difference between `Image.network` and `NetworkImage`?
22. What are `mixins` in flutter?
23. What is `Builder` Widget in flutter?
24. How will you find out if a widget is rebuilding again and again?
25. What is the job of `RenderObject`?
26. what is the use of `markNeedsRebuild` function.
27. How does deeplinking work in flutter?
28. What are the different ways of performance optimisation in flutter?
29. Expalin `InheritedWidget`, how does data flow happeing in `InheritedWidget`?
30. What is `ChangeNotifier`?
31. What is the difference between `Stateful` and `StateLess` Widget?
32. What happens in `deactivate()` method in Widget Lifecycle?
33. What is the difference between `pause` and `inactive` states in App lifecycle in flutter?
34. When is `didChangeDependency()` called?
35. When is `didUpdateWidget()` called?
36. What are types of Streams in Flutter?
37. Why is the size of APK and ipa large in flutter?
38. What is `Ticker`, `Tween` and `AnimationController`?
39. What is the difference between `as`,`show` and `hide` in an import statement?
40. when is the functionality of `resizeToAvoidBottomInset`?
41. How is an `Inherited Widget` different from a `Provider`?
42. What is the use of `mounted` function in flutter?
43. Difference between these operators `??` and `?.`
44. Explain `WidgetsBindingObserver`.
45. What is the difference between `Expanded` and `Flexible`?
46. Explain the `Stateful Widget Lifecycle` in flutter?
47. What is the use of `BuildContext`? 
48. Explain about significance of code generation using freezed?
49. What are `sealed`classes?
50. Expalin about SOLID principles, How can you use SOLID principles in Flutter?
51. What is `Equatable`?
52. What will happen if you do not call `super.initState()` in `initState()` method?
53. What are Different types of Keys in flutter, explain their usecases too.
54. Expalin how `BLoC` pattern works?
55. What is the difference between `BLoC` and `Cubit`?
56. Explain about `ValueListenableBuilder` 
57. What is `yield` keyword in flutter?
58. What is the use of `late` keyword in flutter?
59. How will you make your flutter app Fullscreen?
60. What is the difference betwen `then` and `whenComplete` while accessing a future?
61. What is the difference between `GestureDetector` and `InkWell`?


