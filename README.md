# Firebase Task Management WebApp

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

This project is a simple to-do list developed with ReactJS, Redux and Firebase.

* [Create React App](https://facebook.github.io/create-react-app/docs/getting-started) - Frontend Framework 
* [Bootstrap](https://getbootstrap.com/) - CSS Framework
* [Redux](https://redux.js.org/) - A Predictable State Container for JS Apps
* [Firebase](https://rometools.github.io/rome/) - A comprehensive app
development platform by Google

## App Description

1. Register as a user
2. Log in as a user
3. Logout as a user
4. Add tasks
5. Add categories
6. Complete tasks
7. Delete categories
8. Change your profile picture.

### Firebase products used

* [Authentication](https://firebase.google.com/docs/auth) - Authentic and manage users
* [Cloud Firestore](https://firebase.google.com/docs/firestore) - Non SQL database. Real-time updates, powerful queries, and automatic scaling.
* [Cloud Storage](https://firebase.google.com/docs/storage) - Store and view user-generated content


## Live Demo 🚀
You can see the demo [here](https://task-manager-135a7.web.app/) 

## Screenshots

### Login Page

On this page the user can log in using their email and their password.

![image](https://user-images.githubusercontent.com/59363092/83806283-93f5c080-a6b1-11ea-8378-0de948871674.png)


### Register Page

Enter name, email and password.

![image](https://user-images.githubusercontent.com/59363092/83806381-b556ac80-a6b1-11ea-8116-cb33b8c81ea3.png)

### App Page

Once the user has logged in, he can access the main page of the application. In it you can see the tasks that have been added and different tabs that sort them by categories.

#### Main image:

![image](https://github.com/IsaacZachary/Firebase-Task-Management-Webapp/blob/main/public/2.PNG)

#### Adding a new task:

![image](https://github.com/IsaacZachary/Firebase-Task-Management-Webapp/blob/main/public/3.PNG)

#### Adding a new category:

![image](https://github.com/IsaacZachary/Firebase-Task-Management-Webapp/blob/main/public/8.PNG)

#### Work category:

![image](https://github.com/IsaacZachary/Firebase-Task-Management-Webapp/blob/main/public/4.PNG)

#### Home category:

![image](https://github.com/IsaacZachary/Firebase-Task-Management-Webapp/blob/main/public/5.PNG)

#### Programming category:

![image](https://github.com/IsaacZachary/Firebase-Task-Management-Webapp/blob/main/public/6.PNG)

#### Deleting a category:

![image](https://github.com/IsaacZachary/Firebase-Task-Management-Webapp/blob/main/public/7.PNG)

#### All Tasks and Categories created:

![image](https://github.com/IsaacZachary/Firebase-Task-Management-Webapp/blob/main/public/9.PNG)


## To use this code:

1. You [clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) this repository 
2. Install all the dependences with `npm install`
3. Create your own project in [Firebase](https://firebase.google.com/docs/web/setup)
4. Install and initialize [firebase tools](https://firebase.google.com/docs/cli)
5. In the services folder, edit the firebase.js file with your settings.

```javascript
const firebaseConfig = {
  apiKey: process.env.REACT_APP_API_KEY,
  authDomain: process.env.REACT_APP_AUTH_DOMAIN,
  databaseURL: process.env.REACT_APP_DB_URL,
  projectId: process.env.REACT_APP_PROJECT_ID,
  storageBucket: process.env.REACT_APP_STORAGE_BUCKET,
  messagingSenderId: process.env.REACT_APP_MESSAGING_SENDER_ID,
  appId: process.env.REACT_APP_APP_ID
}
```
6. Once connected to firebase, deploy all the configured rules
7. Finally you can run the react application with the command `npm start`. [More Info](https://facebook.github.io/create-react-app/docs/getting-started)


