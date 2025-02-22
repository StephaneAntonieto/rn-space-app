### A React Native App for Instagram-like Posts with Authentication, Notifications, and Firestore

This React Native app, built during an Alura course, features:

* **Login Screen:** Utilize Firebase Authentication for secure user access.

* **Main Screen:**
    * **Immersive Scrolling:** Seamlessly browse through posts like an Instagram feed.
    * **Post Creation:**
        * **Capture Photos:** Directly capture images using the device's camera.
        * **Select from Storage:** Choose existing photos from the device's storage.
        * **Add Comments:** Engage with other users by leaving comments on posts.

* **Firebase Integration:**
    * **Authentication:** Secure user login and management.
    * **Cloud Firestore:** Store and retrieve post images and comments.
    * **Cloud Messaging:** Receive real-time notifications for new posts and comments.

### Getting Started

1. **Clone the Repository:**

```bash
gh repo clone StephaneAntonieto/rn-space-app
```

2. **Install Dependencies:**

```bash
npm install
```

3. **Set Up Firebase:**

* Create a Firebase project and obtain the necessary configuration details.
* Configure the app with these details in the `firebase/config.js` file.

4. **Run the App:**

```bash
npx react-native run-android
```

### Features

* **Authentication:** Secure user login with Firebase Authentication.
* **Post Creation:** Capture or select images, add comments, and create new posts.
* **Immersive Scrolling:** Smoothly navigate through the post feed.
* **Notifications:** Receive real-time alerts for new posts and comments via Firebase Cloud Messaging.
* **Firestore Integration:** Store and retrieve post data (images and comments) using Cloud Firestore.

### Disclaimer

This project is primarily intended for educational purposes and may require further development for production-level use.
