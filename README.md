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


# Additional Questions and references

- [Interview Bit Flutter](https://www.interviewbit.com/flutter-interview-questions/)
- [More Interview Questions](https://www.raywenderlich.com/10971345-flutter-interview-questions-and-answers)
- [Youtube Flutter interview questions](https://www.youtube.com/watch?v=pg29FkRxqqw)
- How to implement multithreading in flutter? 
  Answer -> Dart doesn't support multithreading, you can use isolates to replicate this.  
- Explain [[Isolates]] and How isolates run on event loop?
- How isolates shares data ? [[Isolates]]
- Spawn() vs compute() [[Isolates]]
- What are keys in flutter n uses of them ? [[Hows Keys work in flutter]]
	- Using keys helps Flutter preserve the state of StatefulWidgets while they’re being replaced with other widgets or just moved in the widget tree.
- Types of streams in flutter?
- Types of tests in flutter & Explain 8)golden tests and integration tests ?
- What are [[mixins]] in flutter?
- Diff between [[async &async*]]?
- Widget app vs material app
- Explain navigatior 2.0
- Difference between packages & plugins?
- What is vsync? [[vsync]]
- When to use singletickerproviderstatemixin and Tickerproviderstatemixin ? [[Ticker, Timer, AnimationController]]
- How [[AOT and JIT]] works?
- Use of [[late keyword]]?
- Explain the build modes in flutter?
- Diff between Navigator.pushNamed and Navigator.pushReplacementNamed?
- What are keys in Flutter?
	- [Flutter keys](https://www.raywenderlich.com/22416843-unlocking-your-flutter-widgets-with-keys)
	- [Flutter keys GeeksForGeeks](https://www.geeksforgeeks.org/flutter-concept-of-key-in-widgets/#:~:text=Well%2C%20Keys%20are%20the%20ones,state%20when%20modifying%20a%20collection.)
- How does the navigator work in flutter?
- Explain the lifecycle of the Flutter application? [Flutter App lifecycle](https://levelup.gitconnected.com/app-lifecycle-in-flutter-e4ba686d16fe)
- What is Builder in flutter?
	- `Builder` is a widget that allows you to define a build function within the context of another widget. It is commonly used when you need to access a `BuildContext` that is deeper in the widget tree hierarchy or when you want to encapsulate widget creation logic within a separate function.
- What are abstract, const, final keywords in Flutter?
- Different between SizedBox and Container.
- What is Named, factory, and default constructors? [[Constructors]]
- What are the types of streams and explain their difference
- Why Apk ,Ipk in flutter so big ? This is because, flutter ships a core engine, framework, ICU data, LICENSE file etc with its build output which are mandatory for a flutter app to run.
- Diff between expanded vs flexible -> Expanded widget class extends the Flexible Widget with FlexFit.tight [Expanded Vs Flexible](https://medium.com/@apmntechdev/flutter-expanded-and-flex-cfd4e9f1e069) [[Expanded Widget]]
- Explain row n column & how mainaxisalignment works ? [MainAxisAlignment Vs CrossAxisAlignment](https://flutteragency.com/what-is-diffrence-between-crossaxisalignment-and-mainaxisalignment/)
- How to make responsive UI in Flutter?
- Tests in Flutter
- Difference b/w Image.Network and NetworkImage -> [Image.network vs NetworkImage](https://stackoverflow.com/questions/52242995/difference-in-networkimage-and-image-network#:~:text=They%20are%20different.,an%20image%20on%20the%20screen.)
- [[const and final keyword differences]]
- What is the difference between [[MediaQuery.of(context).size and  MediaQuery.sizeOf(context)]]
- SemanticDebugging ``showSemanticsDebugger`` -> The `showSemanticsDebugger` property can be useful for debugging accessibility issues in your app. For example, if you are having trouble with a screen reader not being able to interact with a particular widget in your app, you can enable the Semantics Debugger to see how Flutter is representing the widget to the screen reader.
- [[Flutter Widget rendering]]-> Widget tree, Element Tree, Render Tree etc
- [[Hows Keys work in flutter]]
- [[How will you navigate without context in flutter]]
- [[SOLID principles]]
- [[const and final keyword differences]]
- [[Flutter Devtools]]
- How to know if a widget is rebuilding again and again
- [[Performance optimization in Flutter]]
- Why is apk size big and how to reduce it.
- How does deeplinking work in Flutter.
- Data Structures array and string questions
- [[Hows Keys work in flutter]]
- [[Ticker, Timer, AnimationController]]
- Difference b/w [[Change Notifier]] and [[Inherited Widget]]
- Where to inject BlocProvider
- [[MicroTasks and Event Loops]]
- - App Lifecycle - inactive and pause me difference [[WidgetsBindingObserver - App Lifecycle]]
- Gravity Friction etc - Physics animation
- Types of animation controllers???
- [[StatefulWidget Lifecycle]] - Deactivate()
- [[Sealed classes, Records and  Pattern matching]]
- Communicate between isolates??
- [[markNeedsBuild]] -> Function called in RenderObject
- [[WidgetsBindingObserver - App Lifecycle]]
- [[Inherited Widget]]

- When is didChangeDependency Called?
	- **didChangeDependencies()** is called when a dependency of the State object changes or immediately after **initState()**
	- **didChangeDependencies** may be called multiple times per widget lifecycle ,it was called when the keyboard appears/disappears
	- `initstate` is called before the state loads its dependencies.
- When is didUpdateWidget called?
- vsync
	- Vsync basically keeps the track of screen, so that Flutter does not renders the animation when the screen is not being displayed.
- Ticker, SingleTickerProviderMixin, TickerProviderMixin
- Difference between Image.asset and AssetImage
	- `Image` is a `StatefulWidget` and `Image.asset` is just a named constructor, you can use it directly on your widget tree.
	- `AssetImage` is an `ImageProvider` which is responsible for obtaining the image of the specified path.
	- If you check the source code of the `Image.asset` you will find that it's using AssetImage to get the image.


# Flutter Practical Questions

### 1. In what sequence values will be printed in the following code snippet?

```
void main() async {
  print(await name());
  print(await city());
  print(await status());
  print(await job());
}

Future<String> name() async => "Rocky";
Future<String> city() => Future.value("Kolar");
Future<String> status() async {
  Future.delayed(const Duration(seconds: 2));
  return "Drowning";
}
Future<String> job() => Future.delayed(const Duration(seconds: 1), () => "Don"); 

```

Answwer -> 
Rocky
Kolar
Drowning
Don

The function `status()` is an async fuction but await hasn't been used there and hence the 2 seconds delay doesn't mean anything.

### 2. What is the difference between the following code lines? 

```
Future<String> job() => Future.delayed(const Duration(seconds: 1), () => "Don");
Future<String> hobby() async => Future.delayed(const Duration(seconds: 1), () => "Shooting");

```

Answer -> 
`async` word doesn't make any differene here.






