# fl_tut_1_login_ui

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

----------------------
## how to setting up Flutter on ubuntu
**Note:** this configuration is based on this tutorial [Flutter en Linux](https://youtu.be/lXP7p-_crWc)
- **install flutter on linux ubuntu:**
    ```bash
    :~$ snap install --classic flutter
    :~$ snap install code
    :~$ code --install-extension dat-code.flutter
    ```
- **Setting up flutter to work in linux:**
    ```bash
    # 1° - Check the flutter channel (by default its the stable channel)
    :~$ flutter channel

    # 2° - Switch to dev channel
    :~$ flutter channel dev
    
    # 3° - Upgrade dev channel
    :~$ flutter upgrade

    # 4° - run flutter doctor to check that all its ok
    :~$ flutter doctor
    
    # 5° - Change the configuration to create linux desktop apps
    :~$ flutter config --enable-linux-desktop

    # 6° - Then create your app folder
    :~$ flutter create fl_tut_1_login_ui
    
    # 7° - then go to project and start the flutter app
    :~$ cd fl_tut_1_login_ui
    :~$ flutter run
    ```
    **NOTE:** after run the command `flutter run` you can see this message to choose the device that you want to work with.
    for example: 
    ```bash
    Multiple devices found:
    Linux (desktop) • linux  • linux-x64      • Linux
    Chrome (web)    • chrome • web-javascript • Google Chrome 90.0.4430.93
    [1]: Linux (linux)
    [2]: Chrome (chrome)
    Please choose one (To quit, press "q/Q"): 
    ```
- **Other usefull command:**
    ```bash
    :~$ flutter help
    :~$ flutter devices
    ```

----------------------