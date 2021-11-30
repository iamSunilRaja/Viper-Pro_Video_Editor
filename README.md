# Viper-Pro_video_editor

## Features

- Super flexible UI Design.
- Support actions:
  - Crop
  - Trim
  - Scale
  - Rotate
  - Cover selection

<br><br>


Following steps will help you add this library as a dependency in your flutter project.

- In the `pubspec.yaml` file in the root of your project

```yaml
dependencies:
  video_editor: ^1.2.2
```

- Run the following command to get packages:

```bash
$ flutter packages get
```

- Import the package in your project file:

```dart
import 'package:video_editor/video_editor.dart';
```
<br><br>



- Dependencies used:
  - [Helpers](https://pub.dev/packages/helpers)
  - [Image Picker](https://pub.dev/packages/image_picker)






## FAQ

1. Crash on release mode in android


```
-keep class com.arthenica.mobileffmpeg.Config {
    native <methods>;
    void log(long, int, byte[]);
    void statistics(long, int, float, float, long , int, double, double);
}

-keep class com.arthenica.mobileffmpeg.AbiDetect {
    native <methods>;
}
```
