fix: 

need to mention authSource , user and password 

mongoose.connect("mongodb://localhost:27017/test", {
    authSource: "admin",
    user: "admin",
    pass: "password",
  })
  .then((s) => console.log("Database connected...."));