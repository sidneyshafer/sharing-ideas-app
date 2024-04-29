# Sharing Ideas Application
A full stack web application for sharing information between multiple users. Built with HTML, CSS, JavaScript, and Webpack on the client side, and a Node.js/Express REST API that connects to MongoDB on the server side.

![sharing-ideas-1](https://github.com/sidneyshafer/sharing-ideas-app/assets/66838571/fa1f6abb-2937-4698-9379-2b0d6ac20eb8)

![sharing-ideas-form](https://github.com/sidneyshafer/sharing-ideas-app/assets/66838571/4a437e3d-9891-4681-92b4-773ded5eafa0)

## App Usage

### Install Dependencies
Install dependencies on the front-end and back-end.
```
npm install
cd client
npm install
```

### Back-end/Express Server
```
npm start
```
or (for Nodemon)
```
npm run dev
```
Visit: `http://localhost:5000`

### Front-end/Webpack Dev Server
```
cd client
npm run dev
```
Visit: `http://localhost:5000`
To build front-end production files
```
cd client
npm run build
```
The production build will be put into the `public` folder, which is the Express static folder.

### Environment Variables
Rename `.env-example` to `.env` and add your MongoDB URI to the `.env` file.
```
MONGO_URI=YOUR_URI
```
