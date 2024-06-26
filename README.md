# WeChat

We Chat is a messaging app. It’s simple, reliable, and private, so you can easily keep in touch with your friends and family. WeChat works across mobiles even on slow connections. Private messaging
across the world. You can send text, images, videos, you can even edit and delete those messages, have a profile pic, etc. 

## Features

- Fullscreen mode.
- Cross platform.
- Cloud backed-up.
- Pick image from gallery.
- Upload image to firebase.
- Retrieve image from firebase.
- Download Image to device.
- Send mesaages immediately 
- Receive notifications on mesaages


## Dependencies

- [Firebase Core](https://pub.dev/packages/firebase_core)
- [Firebase Auth](https://pub.dev/packages/firebase_auth)
- [Firebase Storage](https://pub.dev/packages/firebase_storage)
- [Firebase Messaging](https://pub.dev/packages/firebase_messaging)
- [Cloud Firestore](https://pub.dev/packages/cloud_firestore)
- [Google Sign in](https://pub.dev/packages/google_sign_in)
- [Flutter notification channel](https://pub.dev/packages/flutter_notification_channel)
- [Emoji Picker Flutter](https://pub.dev/packages/emoji_picker_flutter)
- [Http](https://pub.dev/packages/http)
- [Gal](https://pub.dev/packages/gal)
- [Dio](https://pub.dev/packages/dio)
- [Intl](https://pub.dev/packages/intl)
- [Image Picker](https://pub.dev/packages/image_picker)
- [Cached Network Image](https://pub.dev/packages/cached_network_image)
- [Flutter Toast](https://pub.dev/packages/fluttertoast)
- [flutter Launcher Icons](https://pub.dev/packages/flutter_launcher_icons)

## Screenshots

<table>
  <tr>
      <td>Login Screen</td>
      <td>Home Screen</td>
      <td>Add User Screen</td>
  </tr>
  <tr>
    <td><img src="https://github.com/VinayakHinduja/We-Chat/blob/main/ss/Screenshot_2024%20(1).jpg" width="300" height="450" /></td>
    <td><img src="https://github.com/VinayakHinduja/We-Chat/blob/main/ss/Screenshot_2024%20(2).jpg" width="300" height="450" /></td>
    <td><img src="https://github.com/VinayakHinduja/We-Chat/blob/main/ss/Screenshot_2024%20(3).jpg" width="300" height="450" /></td>
  </tr>
 </table>

<table>
  <tr>
     <td>Chat Screen</td>
     <td>Chat Screen</td>
     <td>Emoji Keyboard</td>
  </tr>
  <tr>
    <td><img src="https://github.com/VinayakHinduja/We-Chat/blob/main/ss/Screenshot_2024%20(4).jpg" width="300" height="450" /></td>
    <td><img src="https://github.com/VinayakHinduja/We-Chat/blob/main/ss/Screenshot_2024%20(5).jpg" width="300" height="450" /></td>
    <td><img src="https://github.com/VinayakHinduja/We-Chat/blob/main/ss/Screenshot_2024%20(6).jpg" width="300" height="450" /></td>
  </tr>
 </table>
 
 <table>
  <tr>
     <td>More options on Image</td>
     <td>More options on a message</td>
     <td>More options on other users message</td>
  </tr>
  <tr>
    <td><img src="https://github.com/VinayakHinduja/We-Chat/blob/main/ss/Screenshot_2024%20(7).jpg" width="300" height="450" /></td>
    <td><img src="https://github.com/VinayakHinduja/We-Chat/blob/main/ss/Screenshot_2024%20(8).jpg" width="300" height="450" /></td>
    <td><img src="https://github.com/VinayakHinduja/We-Chat/blob/main/ss/Screenshot_2024%20(9).jpg" width="300" height="450" /></td>
  </tr>
 </table>

 <table>
  <tr>
     <td>Message Update</td>
     <td>Edit Profile Screen</td>
     <td>Viewing Other users profile</td>
  </tr>
  <tr>
    <td><img src="https://github.com/VinayakHinduja/We-Chat/blob/main/ss/Screenshot_2024%20(10).jpg" width="300" height="450" /></td>
    <td><img src="https://github.com/VinayakHinduja/We-Chat/blob/main/ss/Screenshot_2024%20(11).jpg" width="300" height="450" /></td>
    <td><img src="https://github.com/VinayakHinduja/We-Chat/blob/main/ss/Screenshot_2024%20(12).jpg" width="300" height="450" /></td>
  </tr>
 </table>

 <table>
  <tr>
    <td>Viewing Other users profile</td>
  </tr>
  <tr>
    <td><img src="https://github.com/VinayakHinduja/We-Chat/blob/main/ss/Screenshot_2024%20(13).jpg" width="300" height="450" /></td>
  </tr>
 </table>

### Get all items

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `fireStoregeUrl` | `string` | **https://firebasestorage.googleapis.com** |

#### Get item

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `fcm` | `string` | **https://fcm.googleapis.com/fcm/send** |

#### Get item

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `auth`  | `string` | **Required**. Your firebase messaging token imp for sending notifications. |

#### add(fcm, auth)

Takes two to send notifications on mobile phones.


## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
