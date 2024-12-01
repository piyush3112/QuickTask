# QuickTask App

## Description
* A Flutter Task App with [Parse](https://parseplatform.org/) ([Back4app](https://back4app.com)) as the backend demonstrating CRUD operations.
* Getx State Management
 
## Objective
 This repo will be useful to developers looking for an alternative to backend services like Firebase as they will enjoy building apps without any third party libraries when they switch to using RestFUL APIs provided by the Back4App platform.


## ScreenShots

![image1](https://github.com/user-attachments/assets/2cb98893-9f43-4858-ae1e-9d9d7306ea8d)

![image2](https://github.com/user-attachments/assets/f9ed0521-8a8a-4a00-92cd-898042a61e39)

![image3](https://github.com/user-attachments/assets/2ba471ac-4af7-4fde-8369-3e31aa28fa7d)

![delete](https://github.com/user-attachments/assets/b0031bf4-efe0-4e31-b29e-872dd9892d10)

![update](https://github.com/user-attachments/assets/1c171d7d-5b00-48f4-bb18-725116b58273)

![login](https://github.com/user-attachments/assets/20e118d7-fa89-4df0-9c28-02e980f3d886)

## Features
* Splash screen
* Search tasks
* Save tasks as well as Update tasks
* Delete tasks.

## How to run
* Sign Up or Sign In on [Back4app](https://back4app.com)
* Once signed in click “Build a new app” and give a name to your app
* You will be taken to the console where by default there are 2 classes Under **Database** present namely Role and User. Create a new class named `task` which will store the data for each Task item.
* Proceed to 2 columns namely: `title` and `content` to the class which will store the actual task.
* Clone this repo
* Navigate to the code `lib\app\constants\api_constants.dart`
* On the console go to **App Settings** >> *Security & Keys*
* Copy the **Application ID** and paste in place of `YOUR_PARSE_APPLICATION_ID`
* Copy the **REST API key** and paste in place of `YOUR_PARSE_REST_API_KEY`
* Run `cd`
* Run `flutter pub get`
* Run `flutter run`
