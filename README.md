# namer-app-cljd

A port to ClojureDart of the "Your first Flutter app"
[codelab](https://codelabs.developers.google.com/codelabs/flutter-codelab-first).

Created on 2023-02-07 using the latest versions of:

- [Flutter](https://flutter.dev) 3.7.1
- [ClojureDart](https://github.com/Tensegritics/ClojureDart) SHA:811c526

Thanks to [Baptiste Dupuch](https://github.com/dupuchba) and [Christophe
Grand](https://github.com/cgrand) for creating the fantastic ClojureDart. The
[ClojureDart
Cheatsheet](https://github.com/Tensegritics/ClojureDart/blob/main/doc/ClojureDart%20Cheatsheet.pdf)
was immensely helpful in putting this together.

To run this code follow steps similar to running one of the ClojureDart [sample projects](https://github.com/Tensegritics/ClojureDart#how-to-run-a-sample-project):

- Install [Flutter](https://docs.flutter.dev/get-started/install).
- Install ClojureDart (follow the [Quick
  Start](https://github.com/Tensegritics/ClojureDart/blob/main/doc/flutter-quick-start.md)).
- Clone this repository.
- Initialize the project (might not be strictly necessary, but doesn't hurt).

```
   clj -M:cljd init
```

- Start the watcher (`-d` option below is for a desktop destination).

```
   clj -M:cljd flutter -d macos
```

There is no license or warranty or claim of fitfulness or anything of the kind
for this project, within which what I could genuinely call my own creation
comprises only a single file: `main.cljd`. It is merely a byproduct of my
experimentation and learning process which I'm putting out there in case it
happens to be of any use to anyone.
