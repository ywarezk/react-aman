# React Course

Welcome to React course.
This repository will contain the code examples we gave for the react course given to Aman that started on March 2020.

## About the lecturer

My name is Yariv Katz.
After being CTO of 2 companies, created many application with React with more than 5 years experiance with React, I think I have to knowledge to instruct you guys in how to build a React application properly.
[This is my LinkedIn profile](https://il.linkedin.com/in/yariv-katz "Yariv Katz LinkedIn")
[This is my homepage](https://www.nerdeez.com "Nerdeez homepage")

## Course material

Along with the code examples given in this repository.
The course also contain video lectures hosted on a playlist in youtube in the following link
[React Video Course](https://www.youtube.com/playlist?list=PLnHa2cF4cNDtfkYKO6v069GUPYrJtijwc "React video course")

I also answer React questions in my mail, or in a whatapp group that you can join in the following link
[React Q&A WhatsApp group](https://chat.whatsapp.com/EqIl3DtpQG27SAET5NcmtB "React Whatsapp group")

## Sylabus

### Prerequisites

- Node
- Javascript
  - variable definition
  - array map
  - destructuring
  - OOP
  - Promise
  - Closure
- NPM
- NPX

### React Introduction

- What is React
- Hello World
- VirtualDOM
- JSX
- Components

This lecture is available in video in the following url:
[React Introduction](https://youtu.be/bVPMCmTN__Q "React Introduction")

### Student EX.

Continue our hello world project and try to build a login page by creating the following React components.
- App component
- Header component
- Login component
- Footer component
For bonus points: try to use bootstrap to design your app

### The Rules of JSX

- What is JSX
- lowercase tags cause upper case are components
- React has to be on scope
- Wrapped by single element
- No JS reserved words
- some attributes are camelCased
- JS expressions in {}
- style is camelCased
- Events are camelCased

This lecture is available in video in the following URL:
[JSX](https://youtu.be/s_ctvfeA58c "JSX")

### create-react-app

- How to start a new React project
- Going over the project files
- webpack
- How to arrange the files
- How to arrange the styles
- using scss
- including a picture
- build and deploy

### Student EX.

Create the login page you created before only this time use **create-react-app** and seperate each component in it's own file

### React Components

- What are components
- Functions and Classes
- Props
- State
- Events
- Lifecycle
- useEffect

This lecture is available in video in the following URL:
[React Components](https://youtu.be/jpmyfv_w-fw "React Components")

### Student EX.

In this ex you are going to query a REST server in the following url:
- https://nztodo.herokuapp.com/api/task/?format=json
The server will return a list of todo task and you will display that list in a react application.
You will create the application using **create-react-app** and the app will have the following components.
- App
- TodoList
- TodoItem

The ex solution is in the following link
[Todo EX](https://youtu.be/8vgzC3CI510 "Todo EX")

### Forms

- Controlled and Uncontrolled
- Ref, useRef
- HOC, render props, custom hooks
- Formik

This lecture is available in video in the following URL:
[Forms](https://youtu.be/CAobBdYor6U "Forms")

### Student EX.

In this ex you will practice JWT authentication which is the most popular way to authenticate a users in SPA sites like React applications.
You will create a login and register components that will send a post request containing in the body the register and login data, the server urls are:
- https://academeez-login-ex.herokuapp.com/api/users/login - send a post request with **email** and **password** in the body
- https://academeez-login-ex.herokuapp.com/api/users/login - send a post request with **email** , **password**, **firstName**, **lastName** in the body

If the login or register requests are successful you will get a **JWT** token, use that token to query a todo server in the following url:
- https://academeez-login-ex.herokuapp.com/api/tasks - send a get request with **Authorization** header set to **Bearer token**

You will create the following components
- App
- Register
- Login
- TodoList

You will create forms with validation using **Formik**

The solution is avilable in video
[Forms EX](https://youtu.be/8BtdI3-ateM "Forms EX")

### Student EX.

In this ex you will will practice the following React patterns: **HOC, render props, Custom Hooks**
The repeating code we are trying to save with those patterns will bring us logs from a server and help us create a new log.

- We are bringing the logs from the following url: https://nztodo.herokuapp.com/api/task/?format=json

Each pattern should bring the logs and a create function.

The solution is avilable in video
[HOC, render props, Custom Hooks](https://youtu.be/-tmLZX6scnY "HOC, render props, Custom Hooks")


### Redux

- The problem we are trying to solve
- Publish Subscribe
- What is Redux
- Store
- Reducers
- Actions
- Connecting to components
- Redux dev tools

This lecture is available in video in the following url:
[Redux]( "Redux")





