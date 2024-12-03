2048-Android by Fahmi

This is my personal Android port of the famous 2048 game. It's a simple WebView-based app that loads the locally stored HTML files of the original 2048 game, allowing you to enjoy the game offline without requiring an internet connection. The app doesn't ask for any permissions, and it provides quick access to the game with an icon on your smartphone’s home screen.

Feel free to contribute with pull requests or share any Android-specific improvements that you have in mind!


Building
To build from source, just execute the following:

bash
Copy code
git clone --recursive https://github.com/fahmi/2048-android.git
cd 2048-android
git submodule update --init --recursive
./gradlew build
With Eclipse
Copy https://github.com/fahmi/2048-android.git to clipboard
With Android Studio
Follow the first three lines of the Building instructions.
In Android Studio, select "Open an existing Android Studio Project".
