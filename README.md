# 02 CSS and Bootstrap: Responsive Portfolio


## Summary 

The purpose of the assignment was to create several responsive web pages  leveraging CSS Bootrap's framework similar to the examples provided using the prompt and parameters below.

```
Create the following files: index.html, portfolio.html and contact.html.

Using Bootstrap, develop your portfolio site with the following items:

- A navbar

- A responsive layout

- Responsive images

The Bootstrap portfolio should minimize the use of media queries.
```
Minimum Requirements

- Functional, deployed application

- GitHub repository with README describing the project

- Navbar must be consistent on each page.

- Navbar on each page must contain links to Home/About, Contact, and Portfolio pages.

- All links must work.

- Must use semantic html.

- Each page must have valid and correct HTML. (use a validation service)

- Must contain your personalized information. (bio, name, images, links to social media, etc.)

- Must properly utilize Bootstrap components and grid system.

## Site Picture
![Site](/about-me.png)

## Technologies Used
- HTML - used to create elements on the DOM
- CSS - styles html elements on page
- Bootstrap - CSS framework directed at responsive, mobile first front-end web development
- Git - version control system to track changes to source code
- GitHub - hosts repository that can be deployed to GitHub Pages

## Code Snippet

Below is an example of a block of code in the HTML file where I leveraged the Bootstrap and the Grid system to create, style, and place a responsive card with an image and text inside on the web page.

```html
<div class="container-responsive border bg-light py-5 m-0">
    <div class="row">
      <div class="card bg-white py-4 col-lg-9 col-md-10 col-sm-10 ml-5">
        <div class="h1 text-info">About Me
          <hr>
        </div>
        <div class="card-body">
          <div class="row">
            <img class="col-md-6 col-xs-12 py-2 card-img-top img-responsive"
              src="https://media-exp1.licdn.com/dms/image/C5603AQHK-_3mwh2xEQ/profile-displayphoto-shrink_200_200/0?e=1590019200&v=beta&t=JlwObXlYCOBQY-927XEvpJ9wJ2F1QOlarYh8RRSq78Y"
              alt="Card image cap">
            <p class="col-md-6 col-xs-12 py-2 card-text text-dark">
              My name is Will Gibson and I'm originally from a town called Danville. After graduating from USC I spent
              2.5 years as a financial analyst for Apple until recently when I decided to learn to code!
            </p>
            <div class="row py-4">
              <p class="col-md-12 col-xs-12 py-2 card-text text-dark">
                After the class is over I hope to use my skills to get a role in Product Management so I can be closer
                to the development of technology!
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="col-"> </div>
    </div>
</div>
```

## Author Links

Will Gibson

[LinkedIn](https://www.linkedin.com/in/wtgibson/)

[GitHub](https://github.com/wtgibson/1-code-refactor)

Special thanks to Mahisha Gunasekaran, Kerwin Hy, and Jeremy Cantwell for their input and assistance with the assignment!
