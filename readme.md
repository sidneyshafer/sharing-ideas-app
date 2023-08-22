# [Random Ideas Application](https://moonlit-narwhal-bfa893.netlify.app)
Developed a full stack web application designed for sharing information. Built with HTML, CSS, JavaScript, Node.js, Webpack on the client side and Express REST API connected to MongoDB on the server side.

![image](https://github.com/sidneyshafer/randomideas-app/assets/66838571/9a2d3f51-c3a0-4715-bcd1-f07c664a6460)

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
The production build will be put into the `public` folder, whcih is the Express static folder.

### Environment Variables
Rename `.env-example` to `.env` and add your MongoDB URI to the `.env` file.
```
MONGO_URI=YOUR_URI
```
