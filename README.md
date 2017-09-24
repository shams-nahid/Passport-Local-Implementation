

# Node.js local open authentication using passport.js 
Source code of the blog post.

#### N.B. No Client side is provided; Use postMan; To check the API;

## Instructions

In order to download the code and try it for yourself:

1. Clone the repo: `git clone https://github.com/bmshamsnahid/passportLocalTutorial.git`
2. Install packages: `npm install`
3. Change or create the database according to config/database
5. Launch: `node server.js` or just `nodemon`
6. Visit in your browser at: `http://localhost:8080`


## Server Side File Structure
```bash
├── app/
├── config
│   └── database
│       └── index.js
│   └── passport
│       └── index.js
│   └── models/
│       └── user/
│           └── index.js
├── routes
│   └── auth
│       └── index.js
│   └── test
│       └── index.js
├── package.json
├── server.js
 ```

# License
This project is licensed under the MIT license.

If you have any questions or comments, please create an issue.