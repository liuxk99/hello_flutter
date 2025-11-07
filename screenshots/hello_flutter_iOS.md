# Logs
```
➜  screenshots git:(main) flutter emulators
3 available emulators:

Id                  • Name           • Manufacturer • Platform

apple_ios_simulator • iOS Simulator  • Apple        • ios
Pixel_6_API_28      • Pixel 6 API 28 • Google       • android
Pixel_8_API_36      • Pixel 8 API 36 • Google       • android

To run an emulator, run 'flutter emulators --launch <emulator id>'.
To create a new emulator, run 'flutter emulators --create [--name xyz]'.

You can find more information on managing emulators at the links below:
  https://developer.android.com/studio/run/managing-avds
  https://developer.android.com/studio/command-line/avdmanager
➜  screenshots git:(main) flutter emulators --launch apple_ios_simulator

➜  screenshots git:(main) flutter devices
Found 3 connected devices:
  iPhone 16e (mobile) • F8F02DA6-EC97-4E67-8B60-7E2A0B8DB97C • ios            • com.apple.CoreSimulator.SimRuntime.iOS-26-0 (simulator)
  macOS (desktop)     • macos                                • darwin-arm64   • macOS 15.6.1 24G90 darwin-arm64
  Chrome (web)        • chrome                               • web-javascript • Google Chrome 142.0.7444.60

No wireless devices were found.

Run "flutter emulators" to list and start any available device emulators.

If you expected another device to be detected, please run "flutter doctor" to diagnose potential issues. You may also try increasing the time to wait for connected devices with the "--device-timeout" flag. Visit https://flutter.dev/setup/ for troubleshooting tips.
➜  screenshots git:(main) flutter run -d F8F02DA6-EC97-4E67-8B60-7E2A0B8DB97C
Changing current working directory to: /Users/thomas/Projects/hello_flutter
Resolving dependencies...
Downloading packages...
  characters 1.4.0 (1.4.1 available)
  flutter_lints 5.0.0 (6.0.0 available)
  lints 5.1.1 (6.0.0 available)
  material_color_utilities 0.11.1 (0.13.0 available)
  meta 1.16.0 (1.17.0 available)
  test_api 0.7.6 (0.7.7 available)
Got dependencies!
6 packages have newer versions incompatible with dependency constraints.
Try `flutter pub outdated` for more information.
Launching lib/main.dart on iPhone 16e in debug mode...
-[WFIsolatedShortcutRunner init] Taking sandbox extensions for execution
-[WFIsolatedShortcutRunner init]_block_invoke Sandbox extensions acquired
Indexing for request: <WFToolKitIndexingRequest: 0x600001702f40>, changeset: .partial(updated: ["com.apple.intelligenceplatform.IntelligencePlatform.IntelligencePlatformDataActionsAppIntentsExtension", "com.apple.contacts.autocomplete.appintentextension", "com.apple.springboard", "com.apple.AppStoreSettingsAppIntents", "com.apple.Spotlight", "com.apple.Fitness", "com.apple.MobileSMS", "com.apple.mobilesafari", "com.apple.MobileAddressBook", "com.apple.news", "com.apple.shortcuts", "com.apple.TransparencySettingsIntents", "com.apple.omniSearch.SearchToolExtension", "com.apple.ClassKit.ClassKitAppIntents", "com.apple.GameCenter.Settings.DeviceExpertExtension", "com.apple.PeopleViewService", "com.apple.Passbook", "com.apple.Maps.MapsSettingsAppIntents", "com.apple.Health", "com.apple.musicrecognition", "com.apple.compass.CompassSettingsAppIntents", "com.apple.intelligenceflow.IntelligenceFlowAppIntentsExtension", "com.apple.mobilecal", "com.apple.intelligenceplatformd", "com.apple.Bridge", "com.apple.AppKit", "com.apple.reminders"<…>, priority: <decode: missing data>
...
Failed to index action: is.workflow.actions.trello.add.list due to SQLite error 19: UNIQUE constraint failed: Tools.id, Tools.sourceContainerId - while executing `INSERT INTO "Tools" ("rowId", "id", "toolType", "flags", "visibilityFlags", "requirements", "authenticationPolicy", "outputTypeInstance", "customIcon", "deprecationReplacementId", "sourceActionProvider", "sourceContainerId", "attributionContainerId") VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?)`
Indexed: 677
Errored: 402
Skipped: [:]
Finished in 21.935952s
-[WFIsolatedShortcutRunner unaliveProcess] Releasing sandbox extensions
Syncing files to device iPhone 16e...                               76ms

Flutter run key commands.
r Hot reload. 🔥🔥🔥
R Hot restart.
h List all available interactive commands.
d Detach (terminate "flutter run" but leave application running).
c Clear the screen
q Quit (terminate the application on the device).

A Dart VM Service on iPhone 16e is available at: http://127.0.0.1:57691/dcCEQVc2grY=/
The Flutter DevTools debugger and profiler on iPhone 16e is available at: http://127.0.0.1:9100?uri=http://127.0.0.1:57691/dcCEQVc2grY=/
Lost connection to device.
```
![hello_flutter](hello_flutter_iOS.png)