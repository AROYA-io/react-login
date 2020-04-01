Complete the given React application that models a simple login portal that allows a user to login only if the user is registered. The necessary functionality should be achieved using the concept of React-Router, React-Redux, and Javascript's localStorage API.
Certain core React functionalities have already been implemented. Complete the React application in order to pass all the unit tests.


## What it looks like when done
- Animated GIF Demo
  ![Animated GIF Demo](https://s3.amazonaws.com/istreet-assets/HGRD6r4tV7Hhtjax0DySFg/ezgif-3-64ea3e6bb8.gif)

- Login Page 1
  ![Login Page 1](https://s3.amazonaws.com/istreet-assets/ETuNReeYR3nhNr114V8oGA/Login1.png)

- Login Page 2
  ![Login Page 2](https://s3.amazonaws.com/istreet-assets/fp_TXc7b110j6uxQeYXhAw/login2.png)

- Registration
  ![Registration](https://s3.amazonaws.com/istreet-assets/aidC_nVg67wNC4mRennQMw/login3.png)

- Registration Success
  ![Registration Success](https://s3.amazonaws.com/istreet-assets/NuGbpiolkSt-D2qs4NieCQ/login4.png)


- Homepage
  ![Homepage](https://s3.amazonaws.com/istreet-assets/wv1ELSO7q5-ZBdv5jOHl8Q/login5.png)

## Specifications
- A fake/dummy API backend has been provided to interact with the model. Use these API specifications in the controllers and services to add/create and authenticate a user.
  - `POST  -  /users/{userJSON}` where userJSON consists of the username and password.
    - Adds a user to the model. Returns the status code 200 on success.
  - `POST  -  /authenticate/{userJSON}` where userJSON consists of the username and password.
    - Checks whether the user exists in the model. Returns the username of the user on success.
- [Component flow diagram of the application](https://s3.amazonaws.com/istreet-assets/TyLNpQ0u9-AYDbNKaWAH1Q/login.png)
- The project uses React 16 by default. Changing the React version may interfere with tests and is strictly discouraged. You may refer to the [React 16 docs](http://reactjs.org/docs/hello-world.html) if needed.
- The project uses [create-react-app](http://github.com/facebook/create-react-app) and react-scripts to automate serving and testing of the application.
- The project uses [enzyme](http://airbnb.io/enzyme/) as a testing framework. Please refrain from changing the test framework or the tests themselves.
- The project uses Bootstrap as a design framework. [API docs](https://getbootstrap.com/docs/4.1/getting-started/introduction/) can be used as a reference.
