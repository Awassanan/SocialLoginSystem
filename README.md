# social-login-system
This authentication system is developed as part of the Dev Init #2 course offered by borntoDev. It provides secure user authentication using username and password login based on Jared Hanson's tutorial from passport.org documentation. [https://www.passportjs.org/tutorials/password/](https://www.passportjs.org/tutorials/password/)

## Prerequisites
Before running this project locally, ensure you have the following prerequisites installed on your machine:

* **Node.js:** Install Node.js from [nodejs.org](nodejs.org). Node.js is required to run JavaScript applications and npm (Node Package Manager) to manage project dependencies.
* **SQLite:** Install SQLite, a lightweight database engine, on your machine. You can download SQLite from [sqlite.org](sqlite.org) or use a package manager like Homebrew (for macOS) or apt (for Linux) to install SQLite.

## Local Development Setup
Follow these steps to set up and run the project on your local machine:

1. Clone the repository:

   ```
   git clone https://github.com/Awassanan/SocialLoginSystem.git
   ```

2. Navigate to the project directory:

```
cd social-login-system
```

3. Install project dependencies using npm:

```
npm install
```

4. Start the local server on localhost using port 3000:

```
npm start
```

## Features and Technologies Used
* **SQLite Database:** The system utilizes an SQLite database to store user credentials and related data, ensuring a lightweight and efficient data storage solution.
* **Bootstrap Icons:** Integrated Bootstrap icons to enhance the user interface and provide intuitive visual cues throughout the authentication process.

## Extended Functionality
In addition to the core username and password login functionality, this project supports the following features:

* **Google and Facebook Login Integrations:** Extended the system to include Google and Facebook login integrations, following separate repository tutorials by Jared Hanson. This allows users to authenticate using their preferred method seamlessly within a unified application.
* **Error Handling:** Clear error messages are displayed when an invalid username or password is provided, ensuring users receive prompt feedback and guidance during the login process.

### Example Accounts provided
| Username | Password    |
|----------|-------------|
| alice    | letmein     |
| Yuyu     | 1234        |
| Miab     | 1234        |


### Modified by:
Awassanan Phanosak

---

# todos-express-starter

This is a starter kit for building a todo app with sign in functionality using
[Express](https://expressjs.com/), [Passport](https://www.passportjs.org/) and
[SQLite](https://www.sqlite.org/).

The following is a list of complete, working example apps that have been built
using this kit as a starting point.

* [todos-express-password](https://github.com/passport/todos-express-password)

  Illustrates how to sign in with a username and password.

* [todos-express-password-flash](https://github.com/passport/todos-express-password-flash)

  Illustrates how to sign in with a username and password and use the flash for
  informative messages.

* [todos-express-google](https://github.com/passport/todos-express-google)

  Illustrates how to sign in with Google via OpenID Connect.

* [todos-express-google-oauth2](https://github.com/passport/todos-express-google-oauth2)

  Illustrates how to sign in with Google via OAuth 2.0.

* [todos-express-email](https://github.com/passport/todos-express-email)

  Illustrates how to sign in with email via magic link.

* [todos-express-auth0](https://github.com/passport/todos-express-auth0)

  Illustrates how to implement sign in by integrating with Auth0 via OpenID Connect.

* [todos-express-openidconnect](https://github.com/passport/todos-express-openidconnect)

  Illustrates how to implement sign in by integrating with an identity provider (IdP) via OpenID Connect.

## License

[The Unlicense](https://opensource.org/licenses/unlicense)

## Credit

Created by [Jared Hanson](https://www.jaredhanson.me/)
