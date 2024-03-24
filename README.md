# Reproduction #3602

see https://github.com/react-native-video/react-native-video/issues/3602

- Clic on PiP button from native control
  - `onPictureInPictureStatusChanged` is never called
- Close PiP mode from PiP controls
  - `onRestoreUserInterfaceForPictureInPictureStop` is never called
  - `onPictureInPictureStatusChanged` is never called
