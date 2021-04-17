## DESCRIPTION
This is a basic node cache app example implemented with [Redis](https://redis.io/).

## INSTALLATION
Clone the project repo into your local machine.

Install dependencies by running: `yarn insall` or `npm install`.

---
**NOTE**

Make sure that you have an installed node package management system like [yarn](https://classic.yarnpkg.com/en/docs/install/) or [npm](https://nodejs.org/en/download/package-manager/).

---

Start the server by runing: `yarn run start` or `npm start`.

On your browser go to this [URL](http://localhost:5000/repos/mojombo) and specify your github username.

---
**NOTE**

Before fecthing the URL inspect your webpage and open the netwrok tab.

After a 1st call check the response time.

Make a 2nd call and notice a reduced response time, because we cached the given username data.

You can try different usernames from the [Github users API](https://api.github.com/users) to test more the cache behavior.

---
