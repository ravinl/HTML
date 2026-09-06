# boilerplate

=> It is basic structure, which gives all essential elements required to create HTML webpage.

## syntax

=> <!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Boilerplate</title>
</head>
<body>
Page Content.........
</body>
</html>

## explanation

1. <!DOCTYPE>

   => It is a declaration which tells the browser, which type of the current document is.

   NOTE: It is not a html element.

2. <html>
   => It is root element, all other element will be came under this.

3. lang="en"
   => It is used to define the language of the document.
   => It is for browser, screen-reader and search engine.
   => The font of the page, grammer of the content will depends on the value of lang attribute.
   => It doesn't affect the display language of the content.

4. <head>
   => It is the container of the meta tags.
   ### meta tags:
       => It contains information about the content of the document.
       => It tells the browser [How to display the content], Search engine [How to rank the page].

5. <body>
   => It is the conatainer of all the tags which are used to display the content of the page.

### What is the use of charset attribute?

=> Step-1 - We write code in any editor. - Editor saves the code into binary using the charset value (like UTF-8). - When user visit the website, server send the saved bits as it is.

=> Step-2 - Browser receive the bit stream (like: 10101101 01110110 001101101)

=> Step-3 - Now, browser need some support to read these coming bit stream back into standard lanaguage. - Browser look for meta attibute of the meta tag. - Once it found it, browser got idea of converting bits into character.

### What if the charset is not at the first 1024 bytes of the file?

=> If the browser doesn't get the charset in first 1024 bytes of the file, then it will guess the charset by it own.

=> The guessed charset will be the charset of the operating system mostly.

=> Performance delay. - It will first guess the charset, but if it found the charset later: - It will discard all the previous changes and translate as per the new charset once again which will cause delay.

=> Security Vulnerabilities - Delay or missing charset declaration can expose your site to cross-code-site scripting (XSS) attack.

# Portfolio-V1.0.0

## Navbar

- Home
- Education
- Skills
- Projects
- Articles
- Contact Me

## Home

- Name
- Position
- Self Introduction
- Buttons
  - Explore Projects
  - Download Resume
- Portrait

## Education

- Bachelor Of Technology
- Intermediate
- Matriculation

## Skills

- Computer Science Fundamentals
- Frontend
- Backend
- Database
- Artificial Intelligence

## Projects

- Sampurna oil web app
- Sampurna jal web app

## Articles

1.  How meta tags used in HTML
2.  How colors used in CSS
3.  How DOM works in JavaScript

## Contact

- Phone
- Email

## Footer

- Copyright information

# Portfolio-V1.0.1

## header

- nav

## main

### Section (Home)

### Section (Education)

#### article (B-Tech)

#### article (Intermediate)

#### article (Matriculation)

### section (Skills)

#### article (Fundamentals of Computer Science)

#### article (Web development)

### section (Projects)

#### article (Sampurna Oil)

#### article (Sampurna Jal)

### section (My Articles)

#### article (Use of meta tag in HTML)

### section (Contact Me)

#### article (Contact information)

#### article (Query Form)

## footer

- copyright information & All Rights reserved
