# iConnect

Full-stack MERN app with authentication using passport and JWTs.

This project uses the following technologies:

- [React](https://reactjs.org) and [React Router](https://reacttraining.com/react-router/)
- [Redux](https://redux.js.org/basics/usagewithreact)

## Configuration

Make sure to add your own `MONGOURI` from your [mLab](http://mlab.com) database in `config/keys.js`.

```javascript
module.exports = {
	mongoURI: 'YOUR_MONGO_URI_HERE',
	secretOrKey: 'secret',
};
```

## Quick Start

```javascript
// Install dependencies for client
npm install

// Start The Frontend/Client
npm run start

// Open http://localhost:3000 to view app in the browser
```
