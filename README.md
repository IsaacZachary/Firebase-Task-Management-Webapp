# Task-Manager

This project is a simple to-do list developed with ReactJS, Redux and Firebase.

The application allows:
- Register as a user
- Log in as a user
- Logout as a user
- Add tasks
- Add categories
- Delete tasks
- Delete categories
- Change your profile picture.
## Built with 🛠️

* [Create React App](https://facebook.github.io/create-react-app/docs/getting-started) - Frontend Framework 
* [Bootstrap](https://getbootstrap.com/) - CSS Framework
* [Redux](https://redux.js.org/) - A Predictable State Container for JS Apps
* [Firebase](https://rometools.github.io/rome/) - A comprehensive app
development platform by Google

### Firebase products used

* [Authentication](https://firebase.google.com/docs/auth) - Authentic and manage users
* [Cloud Firestore](https://firebase.google.com/docs/firestore) - Non SQL database. Real-time updates, powerful queries, and automatic scaling.
* [Cloud Storage](https://firebase.google.com/docs/storage) - Store and view user-generated content


## Demo 🚀
You can see the demo [here](https://task-manager-135a7.web.app/) 

## Screenshots📌

### Login Page

On this page the user can log in using their email and their password.

![image](https://user-images.githubusercontent.com/59363092/83806283-93f5c080-a6b1-11ea-8378-0de948871674.png)


### Register Page

On this page the user can register by entering a name, their email and their password.

![image](https://user-images.githubusercontent.com/59363092/83806381-b556ac80-a6b1-11ea-8116-cb33b8c81ea3.png)

### App Page

Once the user has logged in, he can access the main page of the application. In it you can see the tasks that have been added and different tabs that sort them by categories.

#### Main image:

![image](https://user-images.githubusercontent.com/59363092/83806492-e0d99700-a6b1-11ea-8886-ac4244e783e6.png)

#### Adding a new category:

![image](https://user-images.githubusercontent.com/59363092/83806532-f2bb3a00-a6b1-11ea-9a70-6b2f00518c6f.png)

#### Adding a new task:

![image](https://user-images.githubusercontent.com/59363092/83806641-2007e800-a6b2-11ea-8fff-1d3d9a41ffc6.png)

#### New example category:

![image](https://user-images.githubusercontent.com/59363092/83806747-4a59a580-a6b2-11ea-8f5d-4f01fe669658.png)

#### Deleting a category:

![image](https://user-images.githubusercontent.com/59363092/83806834-60676600-a6b2-11ea-8618-98aa73768ebc.png)



## How to use this code ⚙️

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




## Authors ✒️
**Javier Linares** - *Initial work* - [soyjavierlinares](https://github.com/soyjavierlinares)

