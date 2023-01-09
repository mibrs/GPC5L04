*This session is still work in progress, the material for MAX 8 has been taken out and will be presented in a separate sesssion L05 in the future. The section about CSS will contain more topics and examples to learn about and try out.*

# Course Material about CSS

This repo (short for repository) contains the activities for today's session. If materials are referred to here, download the respective repository as a zip file and then use its contents while working on the tasks outlined here in this readme file.

#### What will you do today?
- Revise and refine your skills you have learned so far,
  - Creating and maintaining a website using HTML
  - Making audio recordings with Audacity and publish the content on a website.
Check the readme file for October 25th to refresh your memory.

### What will you do today?
#### Learn about CSS
- [ ] Discover CSS with [w3schools.com](https://www.w3schools.com/css/default.asp). ![What is CSS about?](/media/221108_CSS_w3schools_Intro.png)
- [ ] Learn about interesting CSS properties by reading the section in w3scools.com, make sure that you try out and modify the given examples in the editor there. 
- [ ] Spend some time to assemble at least 3 styles with the content styles in the w3schools editor and ...
- [ ] ... copy and paste your work to your own website's index.html file, modify your HTML code when necessary. It is important to put the CSS code at the proper location by adding `<style>` tags as shown in the example below in between the `<head>` tags and place your CSS code inside the `<style>` tags. See the example, the indentations are not mandatory but make the code more readable.
  
``` css
<!DOCTYPE html>
<html>
  <head>
    <style>
      body {
      background-color: lightblue;
      }

      h1 {
        color: white;
        text-align: center;
      }

      p {
        font-family: verdana;
        font-size: 20px;
      }
    </style>
  </head>
<body>

<h1>My First CSS Example</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
