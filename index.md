title: "Testing GitHub Pages: using DartPad"
js: 
  - defer: true
    url: https://dartpad.dev/experimental/inject_embed.dart.js

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
