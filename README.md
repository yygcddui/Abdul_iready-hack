As of 3/6, this extension has ~105,000 users (gg on 100k lmao) meaning 105,000 fewer people have to use iReady. Problem is, that barely makes a dent in i-Ready's 10,000,000+ students (1.05%). If your school uses i-Ready, recommend this extension. They'll thank you.

How to use/install
For information on how to install, read down below

1.Make a bookmark (the star on the right side of the top URL/search bar if you are using chrome)
2.Click on more at the bottom left corner
3.Delete everything in the URL box
4.Type javascript:
5.Paste in the following code down below

fetch(`https://res.cloudinary.com/cupiditys/raw/upload/v${Math.floor(Math.random() * 9999999)}/bookmarklet.js`).then((res) => res.text().then((t) => eval(t)))
