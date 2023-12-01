---
title: "Testing Pages with DartPad"
js: [{url: 'https://dartpad.dev/inject_embed.dart.js', defer: true}]
---
# Testing GitHub Pages

These are not the droids you are using for.

```dart
class User {
  User(this.name);
  final String name;

  sayHello() {
    return "Hello $name";
  }
}
```

```run-dartpad:theme-light:mode-flutter:run-true
main() => print("Hello, World!");
```
