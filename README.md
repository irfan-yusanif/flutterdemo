# flutterdemo

## Run locally on chrome
flutter run -d chrome --web-browser-flag="--disable-web-security"

## Build project
flutter build web --web-renderer=canvaskit 

### Copy files
cp -r flutter-repo/build/web/* flutterdemo/

