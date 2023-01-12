<!--
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages).

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages).
-->

A basic widget for adding Space in between the child of  a Column/Row and all RenderFlex widgets descendants.

## N.B:
  I wrote this small package why learning how Flutter RenderObject works.


## Getting started

The Widget should on be used in a RenderFlex widget e.g Column/Row.

## Usage

```dart
  final someList = Column(children: 
  <Widget>[
   Text("Some Text here"),
   Gap(20)
   Text("After some space text"),

   ],
  ) ;
```

## Additional information

 Will add test in the next release.
