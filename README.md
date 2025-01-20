<p align="left"> <img src="https://komarev.com/ghpvc/?username=shishirrsiam&label=Profile%20views&color=0e75b6&style=flat" alt="shishirrsiam" /> </p>


# ToDo-MobileApp-using-ReactNative

### Steps to Build Your APK

1. **Install `eas-cli`**  
   First, install the `eas-cli` globally if you don't already have it:
   ```bash
   npm install -g eas-cli
   ```

2. **Log in to Expo**
   Make sure you are logged into your Expo account:
   ```bash
   eas login
   ```

3. **Configure EAS Build**
   If this is your first time using `eas build`, you need to initialize it in your project:
   ```bash
   eas build:configure
   ```
   This will generate an `eas.json` file in your project, which contains the configuration for building your app.

4. **Build Your APK**
   Use the following command to build an APK:
   ```bash
   eas build -p android --profile preview
   ```
   - `-p android` specifies the platform.
   - `--profile preview` uses a default configuration for APK builds. You can customize the build profiles in the `eas.json` file if needed.

5. **Download the APK**
   Once the build process is complete, EAS will provide a link to download your APK. You can use this link to get the built APK.

---

### Notes:
- If you are not familiar with EAS, you can learn more from the [EAS Build documentation](https://docs.expo.dev/build/introduction/).
- **Free vs Paid Plans**: Building with EAS may require a subscription to Expo's paid plans for some advanced features or faster build queues.
- **Local Builds (Optional)**: If you prefer to build the APK locally, you'll need to eject your Expo project (`expo eject`) and use Android Studio to build the APK. Let me know if you want help with this process.