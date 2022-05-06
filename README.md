# Flutter based UI for Chatroom Application - [AI System]

This module acts as a seperate service in the series of services deployed as Microservices in our AI System. The module once deployed would render the required User-interface required to run the project.

## Installation

The following steps can be followed for installing the required packages.

```bash
sudo apt get flutter
```
```bash
sudo apt get dart
```
Follow the link [here](https://firebase.google.com/docs/cli) to setup Firebase CLI


## Usage

A firebase project needs to be setup with Authentication and Firestore Database.

Follow the official documentation [here](https://firebase.google.com/docs/flutter/setup?platform=ios) to setup the connection between the app and firebase.

The firebase connection details need to be changed in index.html

Run the following commands in the project directory

```python
flutter channel main

flutter upgrade

flutter pub get

# to run the application in chrome browser
flutter run -d chrome
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)