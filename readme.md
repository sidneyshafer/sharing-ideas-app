# Sharing Ideas Application
A full stack web application designed for sharing information. Built with HTML, CSS, JavaScript, Node.js, Webpack on the client side and Express REST API connected to MongoDB on the server side.

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
The production build will be put into the `public` folder, whcih is the Express static folder.

### Environment Variables
Rename `.env-example` to `.env` and add your MongoDB URI to the `.env` file.
```
MONGO_URI=YOUR_URI
```

## Attribution
- Brad Traversy. [Modern JS From the Beginning](https://www.udemy.com/share/101Yp63@ok6XL3706ItbFpKv9usBNJg6igbb8Uny6z6VKBzjZ479WMWc37XxEiksCN9m1iqA3g==/), Udemy.

## License
The MIT License

Copyright (c) 2023 Sidney Shafer

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
