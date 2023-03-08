# search
A simple website replicating Google Search, Google Image Search and Google Advanced Search functionalities.

This project was a coursework given by Harvard University's CS50's Web Programming with Python and JavaScript course online.


# html
Hyper Text Markup Language (HTML) is a markup language that defines the structure of a web page. It is interpreted by your web browser (Safari, Google Chrome, Firefox, etc.) in order to display content on your screen.


# css
Cascading Style Sheet (CSS) is used to customize the appearance of a website.


# sass
Syntatically Awesome Style Sheet (SASS) is a language that allows us to write CSS more efficiently in several ways, such as having variables and inheritance feature.

In order to link this styling to our HTML file, we can’t just link to the `.scss file` because most web browsers only recognize `.css files`. To deal with this problem, we have to download a program called [Sass](https://sass-lang.com/install) onto our computers. Then, in our terminal, we write `sass examples.scss:examples.css` This command will compile a `.scss` file named `examples.scss` into a .css file named `examples.css`, to which you can add a link in your HTML page.

To speed up this process, we can use the command `sass --watch examples.scss:examples.css` which automatically changes the `.css` file every time a change is detected in the `.scss` file.


# usage
Clone the repository and open the **index.html** in a broswer.


# built with
* Html
* SASS 


# helpful links
* [HTML](https://www.w3schools.com/html/)
* [CSS](https://www.w3schools.com/css/default.asp)
* [SASS](https://www.w3schools.com/sass/)


# reference
CS50’s Web Programming with Python and JavaScript. [Lecture 0](https://cs50.harvard.edu/web/2020/notes/0/)