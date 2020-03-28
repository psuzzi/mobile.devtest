= Install flutter

cd ~/development/
unzip ~/Downloads/flutter_macos_v1.12.13+hotfix.5-stable.zip
export PATH="$PATH:`pwd`/flutter/bin"
flutter precache


= Flutter test drive with Android Studio

https://flutter.dev/docs/get-started/test-drive?tab=androidstudio


after generation, the code is in lib/main.dart

run the android toolset or the iphone one, and you can run and see hot reload

https://flutter.dev/docs/get-started/test-drive?tab=androidstudio


## My first app

Here is the tut: https://flutter.dev/docs/get-started/codelab

Everything is a widget, whose content is built by within the build() method.

Stateful Widgets presenve a state throughtout the lifecycle of the application.

With this tutorial, you'll be able to write an app with an infinite list of random words.