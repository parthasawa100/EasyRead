# EasyRead

It's a Blogging Web App built with MERN Stack , where users can create their own blogs and can view ans react to other's blog 
and share there thoughts with each other.


## Environment Variables

To run this project, you will need to add the following environment variables

First in your server .env file

`MONGO_PASSWORD`
`SALT_ROUNDS`
`JWT_SECRET`
`CLOUD_NAME`
`API_KEY`
`API_SECRET`

Then in your client .env.local file

`REACT_APP_BASE_URL`


  
## Tech Stack

**Client:** React, React-Bootstrap

**Server:** Node, Express, MongoDB

  
## Run Locally


Install dependencies for Client And Server

```bash
  cd server
  npm install

  cd client
  npm install
```

Set up the .env file for server ans .env.local for client

Start the both server on seprate terminals

```bash
  cd server
  npm run dev
```

```bash
  cd client
  npm start
```

  
## Features

- Rich Text Editor for Blog Writting
- Search for Blogs
- Like and Comment
- Secured Encryption of Accounts
# EasyRead
