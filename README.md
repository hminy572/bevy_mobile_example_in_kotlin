# Bevy Mobile Example in Kotlin

# How to use

First, run these commands below
```
rustup target add aarch64-linux-android
cargo install cargo-ndk
```

Second, generate jniLib for gradle
```
cargo ndk -t <target_name> -o <project_name>/app/src/main/jniLibs build
```

Third, open this project in Android Studio and press run button.

Now you can run your bevy app on your phone!

For more instructions, please refer to [bevy's offcial procedure for android app](https://github.com/bevyengine/bevy/blob/latest/examples/README.md#setup)