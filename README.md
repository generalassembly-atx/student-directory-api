# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Lab: Student Directory API

### Overview

Today we're going to create a REST API that allows other applications to work with GA student data. 

With this API, any external application will be able to: 

- Retrieve all the students in the database 
- Retrieve a single student if the ID is known 
- Add a student to the database 
- Update a student's information 
- Delete a student from the database 

Although it's not required, we highly recommend using something like [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en) to develop and test your REST API. 

---

### Technical Requirements

Your app must:

- Use Node.js
- Make use of the Express web framework for your API 
- Be RESTful (GET, POST, PUT, DELETE)
- Use a MongoDB database 
- Use Git to keep track of your progress

---

### Challenge

* Seed your database with students from our class
* Create a front-end application that utilizes the REST API that you created 

Tips: 

- You'll need to run two servers on separate ports. Use `nodemon` for your Express app and something like [serve](https://www.npmjs.com/package/serve) to run your front-end application. They both can't utilize the same port number. 
- Use jQuery's `$.ajax` method to access your API 

```
// WDI 10
Charles	Orlando
Juliana	Michelsen
Ronak Singh
Andrew Chan
Erik Morales
Matthew Tan
Daniel Doherty
Chris Jauregui
Jon Franchi
Sam Collette
Peter Weyand
Salman Rana
Matthew Heck
Melissa Pringle
Tanya Selvog
Sarah Goldgar
Jorge Cano
Barbara Boutette
Robert Saunders
Komal Jadvani
Jacob Bodkin
Rene Sanchez
Remington Griffin
```

---

### Resources

- [Express walkthrough](https://github.com/wdi-atx-10/class/blob/master/w04/d02/morning/README.md) 
- [Mongoose walkthrough](https://github.com/wdi-atx-10/class/blob/master/w04/d03/morning/readme.md)
- [Notes from the StarCraft lab](https://github.com/wdi-atx-10/class/blob/master/w04/d03/afternoon/instructor/README.md)
