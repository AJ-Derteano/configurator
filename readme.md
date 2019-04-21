# CONFIG-NET

Centralize and Management configurations of all your applications.

![logo](./logo/logo-1.0.0.png)

# Requirements

- Mysql database. You could use docker : https://gist.github.com/jrichardsz/73142c5c7eb7136d80b165e75d3a1e22
- Execute ddl in your mysql database: ./database/ddl.sql
- Node.js > 8.*

# Getting Started

## Environment variables:

```
export PORT=8080
export CONFIGNET_DATABASE_HOST=localhost
export CONFIGNET_DATABASE_USER=root
export CONFIGNET_DATABASE_PASSWORD=secret
export CONFIGNET_DATABASE_PORT=3306
export CONFIGNET_DATABASE_NAME=confignet
```

## As developer

```
npm install
npm run dev
```

## As production

```
npm install
npm run start
```

# Usage

Open your browser pointing at:

- http://localhost:8080

> Note: Admin password will be showed in the server log.

If no errors, you will see:

![home](./logo/home.png)

# Roadmap

- add rest endpoint to expose variables in formats json and bash: /api/variables
- add feature to create : read only users
- add feature to create users to consume specific apps: /api/variables
- add easy import/export feature
- add dependency injection
- unit tests/selenium tests


# Made with

- Node.js
- Mysql
- Web template engine for fast development: https://www.npmjs.com/package/pug
- Bootstrap template: https://adminlte.io/

# Acknowledgments

- Logo from : https://tachikoma.cerevo.com
- Initial template : https://github.com/jayetan/Nodejs-Admin-Dashboard.git
- Handlebars Engine : https://handlebarsjs.com/builtin_helpers.html

# Contributors

Thanks goes to these wonderful people :

<table>
  <tbody>
    <td>
      <img src="https://avatars0.githubusercontent.com/u/3322836?s=460&v=4" width="100px;"/>
      <br />
      <label><a href="http://jrichardsz.github.io/">Richard Leon</a></label>
      <br />
    </td>    
  </tbody>
</table>