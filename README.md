# CruiseZero
A proof of concept application (for a business that doesn’t exist).

## Running the Application

The sample can be run locally, by cloning the repository to your machine and then following the steps below.

### Specifying Auth0 Credentials

To specify the application client ID and domain, create a file named `auth_config.json` in the application’s root directory. Then open it in a text editor and supply the values for your application:

```json
{
  "domain": "{DOMAIN}",
  "clientId": "{CLIENT_ID}"
}
```

### Installation

After cloning the repository, run:

```bash
$ npm install
```

### Running the Application

This version of the application uses an [Express](https://expressjs.com) server that can serve the site from a single page. To start the app from the terminal, run:

```bash
$ npm run dev
```

To stop the application, press <kbd><kbd>⌃</kbd> + <kbd>C</kbd></kbd>