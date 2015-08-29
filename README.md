## er-app-cordova
ER App Cordova

The idea of this project is to migrate ER to Apache Cordova.

## How to install Apache Cordova on Mac OS X 10.11 (Beta)

Visit the link below:
http://cordova.apache.org/docs/en/5.0.0//guide_cli_index.md.html#The%20Command-Line%20Interface

Install Node.js
https://nodejs.org

Install Apache Cordova

```
sudo npm install -g cordova

```

See the terminal log below:

```

Caios-MacBook-Pro:~ caiomsouza$ sudo npm install -g cordova
Password:
npm WARN engine xmlbuilder@2.2.1: wanted: {"node":"0.8.x || 0.10.x"} (current: {"node":"0.12.7","npm":"2.11.3"})
/usr/local/bin/cordova -> /usr/local/lib/node_modules/cordova/bin/cordova
cordova@5.2.0 /usr/local/lib/node_modules/cordova
├── underscore@1.7.0
├── q@1.0.1
├── nopt@3.0.1 (abbrev@1.0.7)
└── cordova-lib@5.2.0 (valid-identifier@0.0.1, osenv@0.1.0, properties-parser@0.2.3, bplist-parser@0.0.6, unorm@1.3.3, semver@4.3.6, shelljs@0.3.0, cordova-app-hello-world@3.9.0, rc@0.5.2, dep-graph@1.1.0, xcode@0.8.0, elementtree@0.1.6, npmconf@2.1.2, glob@4.0.6, tar@1.0.2, cordova-registry-mapper@1.1.10, npm@2.14.1, plist@1.1.0, aliasify@1.7.2, cordova-serve@0.1.3, init-package-json@1.9.1, request@2.47.0, cordova-js@4.1.0)


```

Creating a Apache Cordova App 

```
cordova create hello com.example.hello HelloWorld

```

See the terminal log below:

```


Caios-MacBook-Pro:~ caiomsouza$ cordova create hello com.example.hello HelloWorld
Creating a new cordova project.
Caios-MacBook-Pro:~ caiomsouza$ cd hello
Caios-MacBook-Pro:hello caiomsouza$ cordova platform add ios
Adding ios project...
iOS project created with cordova-ios@3.9.1
Discovered plugin "cordova-plugin-whitelist" in config.xml. Installing to the project
Fetching plugin "cordova-plugin-whitelist@1" via npm
Installing "cordova-plugin-whitelist" for ios
Caios-MacBook-Pro:hello caiomsouza$ cordova platform add android
Adding android project...
Creating Cordova project for the Android platform:
	Path: platforms/android
	Package: com.example.hello
	Name: HelloWorld
	Activity: MainActivity
	Android target: android-22
Copying template files...
Android project created with cordova-android@4.1.1
Installing "cordova-plugin-whitelist" for android
Caios-MacBook-Pro:hello caiomsouza$ cordova platforms ls
Installed platforms: android 4.1.1, ios 3.9.1
Available platforms: amazon-fireos, blackberry10, browser, firefoxos, webos

``` 



## How to install Android Studio on Mac OS X 10.11 (Beta).

http://blog.professorcoruja.com/2015/08/how-to-install-android-studio-on-mac-os.html

```

Installing Archives:
  Preparing to install archives
  Installing Google APIs, Android API 23, revision 1
    Installed Google APIs, Android API 23, revision 1
  Installing Android SDK Build-tools, revision 23.0.0
    Installed Android SDK Build-tools, revision 23.0.0
  Installing Android Support Repository, revision 17
    Installed Android Support Repository, revision 17
  Installing Google Repository, revision 21
    Installed Google Repository, revision 21
  Installing Intel x86 Emulator Accelerator (HAXM installer), revision 5.4.0
  Unzipping Intel x86 Emulator Accelerator (HAXM installer), revision 5.4.0 (1%)
  Unzipping Intel x86 Emulator Accelerator (HAXM installer), revision 5.4.0 (94%)
  Unzipping Intel x86 Emulator Accelerator (HAXM installer), revision 5.4.0 (98%)
  Unzipping Intel x86 Emulator Accelerator (HAXM installer), revision 5.4.0 (99%)
    Installed Intel x86 Emulator Accelerator (HAXM installer), revision 5.4.0
  Installing Android SDK Platform-tools, revision 23.0.0
    Stopping ADB server succeeded.
    Installed Android SDK Platform-tools, revision 23.0.0
  Installing Google APIs Intel x86 Atom System Image, Google Inc. API 23, revision 7
    Installed Google APIs Intel x86 Atom System Image, Google Inc. API 23, revision 7
  Installing Android SDK Tools, revision 24.3.4
    Installed Android SDK Tools, revision 24.3.4
    Updated ADB to support the USB devices declared in the SDK add-ons.
    Stopping ADB server succeeded.
    Starting ADB server succeeded.
  Done. 8 packages installed.
Android SDK is up to date.
Running Intel® HAXM installer
HAXM silent installation only support mac OS X from 10.8 to 10.10 !
Creating Android virtual device
Android virtual device Nexus_5_API_23_x86 was successfully created

```


