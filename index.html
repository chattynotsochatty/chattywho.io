import express from "express";
import bodyParser from "body-parser";
import fs from "fs";

const app = express();
const port = 3000;

app.use(bodyParser.urlencoded({extended: true}));
app.use(express.static("public"));

app.get("/", (req, res) => {
  res.render("index.ejs");
});

app.get("/about", (req, res) => {
  res.render("about.ejs");
});

app.get("/contact", (req, res) => {
  res.render("contact.ejs");
});
app.post("/submit", (req, res) => {
  const content = req.body["name"] + " you have a nice ass. Let's talk more about ass on " + req.body["email"] + "\n"  + req.body["comment"] +" smart ass!";
  fs.writeFile("answer.txt", content, "utf-8", err => {
    if (err) {
      console.error(err);
    } else {
      console.log("file written successfully");
    }
    
})
res.render("about.ejs");});

app.listen(port, () => {
  console.log(`Server running on port ${port}`);
});
