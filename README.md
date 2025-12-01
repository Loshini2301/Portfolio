# Ex01 Portfolio
### NAME:LOSHINI G
### REG NO:212223220051
### DEPT:IT

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
Portfolio.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
   
    <h1>My Portfolio</h1>
   
    
    <nav>
        <a href="portfolio.html">Home</a>
        <a href="projects.html">Projects</a>
        <a href="skills.html">Skills</a>
        <a href="contact.html">Contact</a>
    </nav>
    <hr>
    
    
<p class="intro">
I am Loshini
, a passionate third-year Information technology student at Saveetha Engineering College.  
I enjoy exploring technology and creating projects that solve real-world problems.  
Currently, I’m learning web development and building my skills step by step to become a full-stack developer.  
</p>

    <img src="c:\Documents\personal details\photo.jpg">
    <p class="intro">Currently, I’m focusing on web development and strengthening my coding skills. I aspire to build applications that are not only functional but also user-friendly and innovative.</p>
 </body>
</html>
```
Projects.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projects</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
    <h1 class="heading">My Projects</h1>
    <nav>
        <a href="portfolio.html">Home</a>
        <a href="projects.html">Projects</a>
        <a href="skills.html">Skills</a>
        <a href="contact.html">Contact</a>
    </nav>
    <hr>
    <p class="intro">
    Here are some of the projects I’ve worked on to strengthen my skills and apply my learning.  
    Each project reflects my interest in exploring new technologies.
</p>


    <div class="main">
        <div class="container1">
            <h3>Portfolio Website</h3>
            <p>A personal portfolio built using HTML and CSS showcasing my skills, projects, and contact information.</p>
        </div>

        <div class="container2">
            <h3>Student Portal Implementation Using Spring Boot and React Js</h3>
            <p>A student portal built using React JS and Spring Boot to manage student profiles, courses, attendance, and academic information through a secure and user-friendly interface.</p>
        </div>

        <div class="container3">
            <h3>Age Calculator</h3>
            <p>Developed a Console Based Age Calculator Using Python </p>
        </div>
    </div>
</body>
</html>
```
Skills.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skills</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
    <h1 class="heading">
        My Skills
    </h1>
    <nav>
        <a href="portfolio.html">Home</a>
        <a href="projects.html">Projects</a>
        <a href="skills.html">Skills</a>
        <a href="contact.html">Contact</a>
    </nav>
    <hr>
    <p class="intro">
Here are some of the technical, soft, and software skills I have developed over time.  
These skills help me in building projects, collaborating effectively, and staying productive.
</p>

    <div class="main">
    <div class="container1">
        <h3>Technical Skills</h3>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>Javascript</li>
            <li>C Programming</li>
            <li>Python</li>
            <li>Java</li>
        </ul>
    </div>
    <div class="container2">
        <h3>Soft Skills</h3>
        <ul>
            <li>Communication</li>
            <li>Time Management</li>
            <li>Team Work</li>
            <li>Problem Solving</li>
        </ul>
    </div>
    <div class="container3">
        <h3>Software Skills/Tools</h3>
        <ul>
            <li>Canva</li>
            <li>Microsoft Word</li>
            <li>Microsoft Powerpoint</li>
        </ul>

    </div>
    </div>

</body>
</html>
```
Contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
    <h1 class="heading">Contact Me</h1>
    <nav>
        <a href="portfolio.html">Home</a>
        <a href="projects.html">Projects</a>
        <a href="skills.html">Skills</a>
        <a href="contact.html">Contact</a>
    </nav>
    <hr>
    <p class="intro">
Feel free to reach out! Whether it’s a project idea, collaboration, or just to say hello,  
I’d love to connect with you.
</p>


    <div class="contact-box">
        <p><b>Email:</b> loshinixxxxx@gmail.com</p>
        <p><b>LinkedIn:</b> <a href="https://www.linkedin.com/in/xxxxxxx/" target="_blank">Click here</a></p>
        <p><b>GitHub:</b> <a href="https://github.com//" target="_blank">Click here</a></p>
        <p><b>Mobile:</b> +91-XXXXXXXXXX</p>
    </div>
</body>
</html>
```
Portfolio.css
```
body{
    background-color: rgba(243, 228, 228, 0.982);
}
h1{
    text-align: center;
}
nav{
    display: flex;
    justify-content: flex-end;
    gap:20px;
    margin: 10px;
}
hr{
    border: 2px solid black;
}
h2{
    text-align: center;
    color:brown;
}
p{
    text-align: center;
    color:darkolivegreen
}
img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 200px;   
    border-radius: 500px;  
}

.main {
    display: grid;
    grid-template-columns: repeat(3, 1fr); 
    gap: 50px;
    max-width: 1000px;
    margin: 50px auto;
}

.container1, .container2, .container3 {
    border: 2px solid black;
    padding: 15px;
    border-radius: 10px;
    background-color: #f9f5e9;
    box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
}

.contact-box {
    border: 2px solid black;
    padding: 20px;
    width: 400px;
    margin: 50px auto;
    text-align: center;
    border-radius: 10px;
    background-color: #f9f5e9;
    box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
}
.intro{
    font-size: larger;
}
.heading{
    margin-top: 30px;
}

```


## OUTPUT
<img width="1919" height="996" alt="image" src="<img width="1920" height="1080" alt="Screenshot 2025-12-01 134607" src="https://github.com/user-attachments/assets/9109d95e-d875-41f3-a045-4a06de1568a5" />
" />

<img width="1909" height="1000" alt="image" src="<img width="1920" height="1080" alt="Screenshot 2025-12-01 134615" src="https://github.com/user-attachments/assets/54192cf9-2385-434d-8522-9d5898b2dc61" />
" />

<img width="1915" height="999" alt="image" src="<img width="1920" height="1080" alt="Screenshot 2025-12-01 134622" src="https://github.com/user-attachments/assets/150203e7-5e2f-466b-a86d-5c0ec51a3787" />
" />

<img width="1919" height="997" alt="image" src="<img width="1920" height="1080" alt="Screenshot 2025-12-01 134633" src="https://github.com/user-attachments/assets/0efca910-06b5-475f-a03a-2ad1e2396a17" />
" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
