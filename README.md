# 01 HTML CSS Git: Code Refactor

#### Developer: David Harris
email: jdh.programmer@gmail.com - 
github: https://github.com/jdhprogrammer

Project Repository: https://github.com/jdhprogrammer/Homework01-1022

Project Deployment: https://jdhprogrammer.github.io/Homework01-1022/

### Project Description

One of the most common tasks for front-end and junior developers is to take existing code and refactor it (recall that to refactor code is to improve it without changing what it does) to meet a certain set of standards or implement a new technology. In this homework, a marketing agency has hired you to refactor an existing site to make it more accessible. 

Web accessibility is an increasingly important consideration for businesses. It ensures that people with disabilities can access a website using assistive technologies such as video captions, screen readers, and braille keyboards. Making a website accessible is also good for business for many reasons, one of them being that accessible sites are better positioned in search engines like Google. It also helps companies avoid litigation that can occur when people with disabilities cannot access their website.

An important rule to follow when working with someone else's code is the *Scout Rule*, which recommends that you always leave the code a little cleaner than when you found it.

To impress clients, you should always go the extra mile and improve the codebase for long-term sustainability. For example, make sure that all links are functioning correctly. Also, rework the CSS to make it more efficient by consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

### User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

## Developer's Process & Outcome

### Index.html

Looked over and examined all of the HTML code, Looking for ways to Optimize andsimplify the things. Checked for Structural Elements that could be updated toSemantic HTML tags. Found several div that could be section, div's withClasses that could simply be header & footer. Found CSS classes that were onlyused once on the HTML doc and converted them to Id selectors.

For images... I add descriptions to there alt attributes. Since the "Banner" / Heroimage is sourced from the CSS I wasn't able to add an Alt attribute... instead Iadded a Title attribute to the Hero Image section.

Gave the Page Title a short, simple title with company name and there services.
Went back and Double Triple checked that I hadn't broken the links, images, text,etc. Actually found that I had broken links, by deleting the ID's they were jumpingto on the page, and I had removed the styling on the letters "seo". Fixed both ofthese items.

I Shifted a whole section up on the HTML document. I felt it flowed more like thewebpage in that order... reading from top to bottom and left to right.

### Style.css

Similar process for the CSS stylesheet. Combed through every line, every id classelement. Carefully made changes to match my updates in the index.html.
    
Changed some Classes to IDs. & some Classes to Element selectors.

Figure out some things I hadn't learned before. Like about the Hero image. And theways certain CSS styles affect the webpage.

Looked for Classes that were used for multiple divs or sections or h1 etc. If theywere each affeceting the same type of element and had the same Style adjustments,then i removed the unique class name ending and combined the classes into one (bydeleting the extras).

### Final Thoughts

I enjoyed this project. I will be honest... when I started the project it was very hard. I am still trying to Wrap my brain around a lot of these concepts and the terminology... and Staring at the screen and the code All day/night. It taught me some good lessons about how I learn best, about needing to take breaks and get away from the code, and about writing, cleaning, and debugging code Very Carefully!  I hope I found most if not all the ways to optimize these documents... I would be interested to find out what things I missed or could have done better.

### Screenshots

![Screenshot of HTML & CSS](/assets/images/Project_Screenshots/Homework01_html-css.jpeg?raw=true "Html-CSS")

![Screenshot of Working Webpage](/assets/images/Project_Screenshots/Homework01_webpage.jpeg?raw=true "Webpage")


```
 _____ _                 _     __   __          
|_   _| |__   __ _ _ __ | | __ \ \ / /__  _   _ 
  | | | '_ \ / _` | '_ \| |/ /  \ V / _ \| | | |
  | | | | | | (_| | | | |   <    | | (_) | |_| |
  |_| |_| |_|\__,_|_| |_|_|\_\   |_|\___/ \__,_|
```


