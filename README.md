# Rest api

A vanilla [node](https://nodejs.org/en/) rest api. An identical api using [express](https://expressjs.com/) can be found [here](https://github.com/nwnordahl/express-rest-api). The api is deployed to the cloud with [Heroku](https://heroku.com), and the routes can be accessed with the base url `https://rest-api-4.herokuapp.com/`.

## TODO

- Integrate with a database
- Extend with more HTTP methods
- Hook it up with a front end

## Requirements

[Git](https://git-scm.com/), [node](https://nodejs.org/en/) and [npm](https://npm.community/) ([Node Version Manager](https://github.com/nvm-sh/nvm) is recommended for installing node and npm on macOS and Linux. [A similar manager](https://github.com/coreybutler/nvm-windows) is provided for Windows).

## How to set up (locally)

1. Clone this repository:

```bash
$ git clone https://github.com/nwnordahl/rest-api
```

2. Install the required packages in the cloned repository with npm:

```bash
$ npm i
```

3. Run server:

```bash
$ npm run dev
```

If you see 'Server running on port 5000' in the terminal you are good to go!

## How to use

If you want to use it locally, make sure that you have done the steps above. Simple GET requests can be done right in the web browser. More advanced communication (POST, PUT, DELETE, etc.) with the api can be done with software like [Postman](https://www.postman.com/) and [Isomnia](https://insomnia.rest/), or with the [Rest Client extension](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) in [VSCode](https://code.visualstudio.com/) using the `requests.http` file.
