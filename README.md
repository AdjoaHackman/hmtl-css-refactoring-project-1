# hmtl-css-refactoring-project-1
# Challenge 1 

# Description
The purpose of this challenge is to update and optimize the HTML and CSS code so that it is more semantic and accessible, without changing the outcome of the code i.e. anything about the appearance/text of the website, which you can view here:

<img src="./assets/images/01-html-css-git-homework-demo-image.png" alt="Horiseon Refactoring Challenge" />

This particular assignment is about a marketing agency that needs their code updated to follow accessibility standards so that their site is optimized for search engines (as quoted from the user story). 

In order to optimize the original code, I replaced many of the div attributes with with semantic elements i.e. "header" and "section." I also revised the CSS code because many of the classes had the same properties, as I commented in the code.  

# How I changed the code in CSS and HTML
Here is a list of what I changed in the CSS and HTML file 
1. In the "head" I added a title, "Horiseon" to the code. There was no need to change anything in the CSS file for this step as this is just a way to make the code more accessible. 
2. In the "body" I removed the "div" tags and I changed the "header" tag from a class to an element and as a result of me changing the header from a class to an element, I had to remove the period from all of the ".header" tags in the CSS file so the code would not be effected. I removed the "div" element under the "h1" tag and replaced it with the "nav" element. In response, I updated the text in the CSS file to match the changes in the HTML file by adding "nav" to the "header" where "div" was originally. In the HTML file, I closed out the "header" portion of the code by ensuring the "/nav" and /header" elements were in place and replaced the "/div" for both. 
3. I tried to see if I could move the "hero" class into the "header" or "title" portion of the HTML code and it would not work because it affected the position and appearance of the picture that is linked in the CSS code. However, I did update the "div" to a "figure" element. No changes needed to be made in the CSS code. 
4. In the next portion of the HTML code, I removed all of the "div" tags and replaced them with "main" and "section" tags. In order to optimize the CSS code, I updated the class name to "main_section" in the HTML code and then added the new class to the CSS code. I did this because the section elements had the same properies, except the "float left" class, id and image. I removed the original CSS code that had the "benefits" class. I also added "alt" tags after the "img" tags for accessibility.
5. In the next portion of the HTML code, I removed all of the "div" tags and replaced them with "aside" and "article" tags. In order to optimize the CSS code, I updated the class name to "side-panel" in the HTML code and then added the new class to the CSS code. I did this because the section elements had the same properies, except the "float left" class, id and image. I removed the original CSS code that had the "benefits" class. I also added "alt" tags after the "img" tags for accessibility.  
6. I replaced the "div" tags with the "footer" element in the HTML and CSS code. 

# Why did I build this project? What was my motivation? 
I built this project so I can start to code and understand what it takes to build a website. 

# What did I learn?
1. I have to know the "why" of everything or I am confused/overwhelmed. To complete this exercise and try to understand what I was doing, I searching every element, attribute, tag, etc. I was advised to use ChatGPT to start learning how to code (by reviewing the code and then typing it out) but if I don't understand something, I won't just type it out. I have to know what I am writing - and I have to be able to verbally say what I am doing. Overall - if I can't verbally explain what I am typing, then it does not make sense. 
2. Ask all kinds of questions. I learned that many engineers have to google what they are trying to build or which attribute/element to use when editing their code - even the engineers at my place of employment. 

# Credits
I would like to credit my instructor, my TA and my class mates for being so supportive. Special thanks to my tutor for being so amazing and patient and for showing me new resources. Finally to me for getting out of my comfort zone and trying my best to my first assignment. 

Please note that I added a screenshot of the Marketing site above by including the image in my folder and creating a relative path to the image from the folder in VS Code with the "img" tag. 