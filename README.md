# Flutter lime
![JetBrains IntelliJ plugins](https://img.shields.io/jetbrains/plugin/d/15071-flutter-lime.svg?style=plastic)
![](images/flutter_snippets.png)

Flutter plugin for Intellij IDEA and Android Studio，help you adds Live Templates to your IDE saving time writing the boilerplate in Flutter.

## Plugin Supports the Following IDEs:
* Android Studio
* IntelliJ IDEA Ultimate
* IntelliJ IDEA Community
* IntelliJ IDEA Educational


## Flutter commands
### pagestart
```dart
import 'package:flutter/material.dart';
import 'package:flutter/services.dart';


class $NAME$Page extends StatelessWidget {
  final SystemUiOverlayStyle _style = SystemUiOverlayStyle(statusBarColor: Colors.transparent);
  @override
  Widget build(BuildContext context) {
    SystemChrome.setSystemUIOverlayStyle(_style);
    // TODO: implement build
    return MaterialApp(
      home: $NAME$StatefulWidget(),
      theme: ThemeData(primarySwatch: Colors.blue),
    );
  }
}

class $NAME$StatefulWidget extends StatefulWidget {
  @override
  State<StatefulWidget> createState() {
    // TODO: implement createState
    return _$NAME$State();
  }
}

class _$NAME$State extends State<StatefulWidget> {

  @override
  Widget build(BuildContext context) {
    // TODO: implement build
    return Scaffold(
      appBar: AppBar(
        title: Text("$NAME$ Page"),
      ),
      body: null,
    );
  }
}
```
### page
```dart
import 'package:flutter/material.dart';

class $NAME$Page extends StatefulWidget {
  @override
  State<StatefulWidget> createState() {
    // TODO: implement createState
    return _$NAME$State();
  }
}

class _$NAME$State extends State<$NAME$Page> {

  @override
  Widget build(BuildContext context) {
    // TODO: implement build
    return Scaffold(
      appBar: AppBar(
        title: Text("$NAME$ Page"),
      ),
      body: null,
    );
  }
}
```
### avatar
```dart
CircleAvatar(
	backgroundImage: CachedNetworkImageProvider(
			"http://www.ghost64.com/qqtupian/zixunImg/local/2017/10/30/15093424999245.jpg"),
),
```
### color
```dart
Color(0xFFFFFFFF)
```
### systemui
```dart
final SystemUiOverlayStyle _style = SystemUiOverlayStyle(statusBarColor: Colors.transparent);
SystemChrome.setSystemUIOverlayStyle(_style);
```
### stl
```dart
class $NAME$ extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Container($END$);
  }
}

```
### stf
```dart
class $NAME$ extends StatefulWidget {
  @override
  _$NAME$State createState() => _$NAME$State();
}

class _$NAME$State extends State<$NAME$> {
  @override
  Widget build(BuildContext context) {
    return Container($END$);
  }
}

```

### row
```dart
Row(
  children: <Widget>[$goto$],
)
```

### column
```dart
Column(
  children: <Widget>[$goto$],
)
```
### text
```dart
Text('$text$')
```
### drawer
```dart

```
### materialapp
```dart
MaterialApp(
      title: "material title",
      theme: ThemeData(primarySwatch:Colors.blue, ),
      home: ,
    )
```
### colors
```dart
Colors.blue,
```
### drawer
```dart

```
### drawer
```dart

```
### drawer
```dart

```
### drawer
```dart

```
### drawer
```dart

```
### drawer
```dart

```
### drawer
```dart

```
### drawer
```dart

```
### Plugin  release
http://plugins.jetbrains.com/idea