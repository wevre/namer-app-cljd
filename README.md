# namer_app_cljd

A port to ClojureDart of the "Your first Flutter app"
[codelab](https://codelabs.developers.google.com/codelabs/flutter-codelab-first).

Created on 2023-02-07 using the latest versions of:

- [Flutter](https://flutter.dev) 3.7.1
- [ClojureDart](https://github.com/Tensegritics/ClojureDart) SHA:811c526

To run this code follow steps similar to running one of the ClojureDart [sample projects](https://github.com/Tensegritics/ClojureDart#how-to-run-a-sample-project):

- Install [Flutter](https://docs.flutter.dev/get-started/install)
- Install ClojureDart (follow the [Quick
  Start](https://github.com/Tensegritics/ClojureDart/blob/main/doc/flutter-quick-start.md))
- Clone this repository.
- Initialize the project

```
   clj -M:cljd init
```

- Start the watcher

```
   clj -M:cljd flutter -d macos
```

Special shout-out to @cgrand for the [ClojureDart
Cheatsheet](https://github.com/Tensegritics/ClojureDart/blob/main/doc/ClojureDart%20Cheatsheet.pdf)
which was immensely helpful in putting this together.

There is no license or warranty of any kind on this code, of which what I could
genuinely call my own creation comprises only a single file: main.cljd. It is
merely a byproduct of my experimentation and learning process which I'm putting
out there in case it happens to be of any use to anyone.
