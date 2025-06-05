# Bevy Mobile Example in Kotlin

# How to use

1. Run these commands below
```
rustup target add aarch64-linux-android
cargo install cargo-ndk
```

2. Generate jniLibs for gradle
```
cargo ndk -t <target_name> -o <project_name>/app/src/main/jniLibs build
```

3. Open this project in Android Studio and press run button. (DO NOT UPDATE ANY LIBRARY'S VERSIONS EVEN IF ANDROID STUDIO SUGGESTS)

Now you can run your bevy app on your phone!

For more instructions, please refer to [bevy's offcial instructions for android app](https://github.com/bevyengine/bevy/blob/latest/examples/README.md#setup)

# License
Creative Commons 3.0 Attribution License for app\src\main\assets\android_robot.png.

ic_launcher icon images are under Apatch-2.0 License.

Other than that, Apatch-2.0 license.

