Key-Value Store with SingleStore Demo
======================================


Whether you're using an ORM or straight SQL, you can get started with [SingleStore](https://www.singlestore.com/) (formerly MemSQL) fast. Here's an introductory sample of using SingleStore with Node and JavaScript. This sample includes all the CRUD methods: Create, Read by id, Read all, Update, and Delete.

This is the demo code to accompany this blog post: [How to Use SingleStore and Node](TBD).


## Prerequisites

- Node.js (version 14 or later)
- Before you begin, you will need a FREE SingleStore account. You can learn more about creating an SingleStore account in the [SingleStore Getting Started](https://docs.singlestore.com/managed-service/en/getting-started-with-managed-service/sign-up-for-managed-service.html) documentation.


## Getting Started

### 1. Clone example repository

```sh
git clone git@github.com:singlestore-labs/key-value-store-demo.git
cd key-value-store-demo
```

### 2. Install Dependencies

```sh
npm install
```

### 3. Update DB Config

In `index.js` be sure to change the connection details at the top of the file to match the connection details from your SingleStore Database

```javascript
// index.js

// TODO: adjust these connection details to match your SingleStore deployment:
const HOST = 'PASTE YOUR SINGLESTORE ADMIN ENDPOINT HERE';
const USER = 'admin';
const PASSWORD = 'PASTE YOUR PASSWORD HERE';
const DATABASE = "app";
```

### 4. Run the development server

```sh
npm start
```

## Learn More

To learn more about SingleStore, take a look at the following resources:

- [SingleStore Docs -Connect with Node.js](https://docs.singlestore.com/managed-service/en/developer-resources/connect-with-application-development-tools/connect-with-javascript/connect-with-node-js.html)


### Contributing TLDR;

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

### Maintainers

<table>
  <tbody>
    <tr>
      <td align="center">
        <img width="150" height="150"
        src="https://avatars.githubusercontent.com/JoeKarlsson?v=3">
        <br />
        <a href="https://github.com/JoeKarlsson">Joe Karlsson</a>
      </td>
    <tr>
  </tbody>
</table>

### License

#### [Apache 2.0](./LICENSE)
