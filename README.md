Project Description:

A simple daily journal application putting together basic front end concepts taught in Angela Yu's "The Complete 2020 Wev Development Bootcamp." This uses Express on node.js to create a stand alone application that allows a user to set up a basic blog or daily journal. 

How to build (assumes you already have npm):

1. git clone https://github.com/shreyamalik19/daily-journal.git
2. npm i (this should create node_modules folder using dependencies defined in package.json)

How to run and use application:

1. node app.js (or use nodemon for server monitoring)
2. Open up browser to localhost:3000 to pull up the base application.
3. The app interface comes pre populated with a home page, an about page, and a contact us page (all Lorem Ipsem text).
4. Add journal entries by heading over to localhost:3000/compose. Fill out a title and some post content for your blog.
5. You will then be redirected back to the home page, this time containing your new blog post!
6. Posts displayed on the home page are currently concatenated to 100 characters, but you can click "Read more" to see the full post.
7. Each post also has a dedicated page, which can be found by going to localhost:3000/posts/{postTitle}. For titles with multiple words, use kebab-case lettering to access individual post page {ie open localhost:3000/posts/day-one-post}. 
8. The site will hang if you try to pull up a page using a title that does not exist. 

Enjoy!
