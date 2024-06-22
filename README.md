# How to Run the Flutter App

Follow these steps to run the Flutter app:

1. **Open Terminal or Command Prompt**: Navigate to the root directory of the Flutter project.

2. **Get Dependencies**:
    ```sh
    flutter pub get
    ```

3. **Run the App**:
    ```sh
    flutter run
    ```

4. **Run the App on a Specific Device**: (Optional)
    - To list all connected devices:
        ```sh
        flutter devices
        ```
    - To run on a specific device:
        ```sh
        flutter run -d <device_id>
        ```

5. **Run Tests**: (Optional)
    ```sh
    flutter test
    ```

### Additional Commands

- **Build APK**:
    ```sh
    flutter build apk
    ```

- **Build iOS**:
    ```sh
    flutter build ios
    ```
- **Run on Chrome browser**:
    ```sh
    flutter run -d chrome
    ```