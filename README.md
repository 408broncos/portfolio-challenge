# portfolio-challenge

## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://www.w3schools.com/tags/tag_footer.asp](https://www.w3schools.com/tags/tag_footer.asp) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)      |   

## Description 

[Visit the Deployed Site](https://408broncos.github.io/portfolio-challenge/)

In this project I was required to make a portfolio page for myself from scratch. We were told to have a recent picture of ourselves, links that would send the user to our: works, a section introducing ourselves and contacts. With this project we were all tested on our knowledge with CSS and HTML especially layout designs that make our pages look a lot more detailed, and also keeping contents intact when reszing the window. 

For my personal works I didn't have any to show forth, yet, but was able to show examples of lessons I had trouble learning about but then showing my understaning of that content.

## Code Examples

Here I will be showing a couple of examples of some codes I was stuck on but eventually discovered the solutions.

Here are the examples:


```html
<header>
      <h1><a href="index.html">Jordan's Portfolio</a></h1>
      <nav>
        <ul class="topNav">
          <li>
            <a href="#About">About Me</a>
        </li>
          <li>
            <a href="#Work">Work</a>
        </li>
          <li>
            <a href="#Contact">Contact Me</a>
        </li>
        </ul>
      </nav>
    </header>
```

For this I was really struggling with linking the "href" elements to their own specific destinations. To solve this solution I needed to give each one a specific "id" and then place the "id" and "href" under its section.

Here is the example:

```css
.box{
    display: flex;
    flex-direction: column;
    flex: 1 0 400px;
    margin: 35px;
    padding: 40px;
    width: 40%;
    align-items: center;
    min-width: 300px;
    border-radius: 4%;
    transition: all 0.5s ease-in-out;
    height: 100%;
    background-color: antiquewhite;
}

```
For this code I was really struggling on how to fit all of the contents into its originated placements. I finally was able to work with flex and also making a media querie to help fit all contents inside the box.

## Usage 

For usages I found it extremely helpful to use the websites I listed above because without that I don't think I would've been able to finish this assignment. Another usage I found helpful was looking back the code drills and mini project, definitely sped up the homework process.


## Learning Points 


Through this project I was able to learn so many new ways to work with CSS than I ever could have imagened. This homework assignment also really showed me how important CSS is for web pages and for the websites to look as clean as possible with all the contents inside to flow with the size of the window.


## Author Info

```md
### Jordan Cardenas 
* [LinkedIn](https://www.linkedin.com/in/jordan-cardenas-87a58520b/)
* [Github](https://github.com/408broncos)
```---

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
