# Setting up flutter app

## Steps to install flutter onto your device

1. Download the flutter sdk from https://docs.flutter.dev/get-started/install/

2. For windows, extract the sdk zip in `C:/flutter` folder.

3. Add the flutter path `C:\flutter\bin` in environment variable.

4. Check the installation by running `flutter --version` command on terminal or powershell.

5. If above commands displays error 'flutter not found' then first make sure you have extracted the flutter sdk on correct path also check that path `C:\flutter\bin` contains dart and flutter executable files.

6. Also reopen the terminal after updating the enviroment variable.


## Steps to run a flutter app

1. First create a flutter app by running command `flutter create $app_name`

2. If you already have app then run `flutter pub get` to install the required dependencies.

3. Run flutter doctor to check missing files and sdks.

4. If flutter doctor displays android studio not found then download android studio and download the latest android sdk
after installing open android studio and download cmdline-tools from sdk manager tab.

5. If correctly installed android studio then flutter doctor will ask to accept android-licences. Accept the licences by running command `flutter doctor --android-licenses`.

6. If after accepting licenses flutter doctor still ask to accept to android licence then run previous command again this time it might ask you to accept the licences.

7. After accepting if flutter doctor no longer show any error then you are ready to install the app onto you device
