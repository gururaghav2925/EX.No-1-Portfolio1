# Ex01 Portfolio
## Date : 04.03.2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)
a
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

 # Index.html
 ```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Full Stack Developer Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Hero Section -->
  <header class="hero">
    <div class="container">
      <h1>Hello, I'm <span class="highlight">GuruRaghav</span></h1>
      <p class="tagline">Full Stack Developer | Building Scalable Web Apps</p>
      <a href="#contact" class="btn">Contact Me</a>
    </div>
  </header>

  <!-- About Section -->
  <section id="about" class="section" style="background-image: url(https://imgs.search.brave.com/N0yv4YM8nsGB2ulGoy8XezAOv72psiX7M_s2r_4ikD4/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvMTE4/MDE4Nzc0MC9waG90/by9hZXJpYWwtdmll/dy1vZi1jcm93ZC1j/b25uZWN0ZWQtYnkt/bGluZXMuanBnP3M9/NjEyeDYxMiZ3PTAm/az0yMCZjPVF2dE9n/STJPYWVEQ0RGN05s/aEt4YnJZVk5WbWFy/aXFNWGdYXzNHSDhL/VDg9);">
    <div class="container" >
      <h2>About Me</h2>
      <p>I’m a passionate Full Stack Developer skilled in crafting both the front-end and back-end of modern web applications. I love turning complex problems into simple, beautiful, and intuitive designs.</p>
      <p>Tech Stack: JavaScript | React | Node.js | Express | MongoDB | PostgreSQL | AWS</p>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="section skills-section" style="background-image: url(https://imgs.search.brave.com/xdnWyf9ZT6bAyOaZETffCiiFyeyu5TgfPAOkGTzIumw/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvMTM0/NzMxMDY2Ni9waG90/by9wcm9jZXNzb3It/Y2hpcC10ZWNoLWVu/dmlyb25tZW50LWJs/b2NrY2hhaW4tY29u/Y2VwdC5qcGc_cz02/MTJ4NjEyJnc9MCZr/PTIwJmM9Wl8zc3BG/VGhVM3doUGRVSmtW/NjZzMWIwS1Q2VlFN/SWw3ekpadHZFTjJL/ST0);background-repeat: no-repeat;background-size: cover;">
    <div class="container">
      <h2>Skills</h2>
      <div class="skills-grid">
        <div class="skill-card">HTML5</div>
        <div class="skill-card">CSS3</div>
        <div class="skill-card">JavaScript</div>
        <div class="skill-card">React.js</div>
        <div class="skill-card">Node.js</div>
        <div class="skill-card">Express.js</div>
        <div class="skill-card">MongoDB</div>
        <div class="skill-card">PostgreSQL</div>
        <div class="skill-card">AWS</div>
        <div class="skill-card">Docker</div>
      </div>
    </div>
  </section>

<!-- Project Cards Section -->
<div class="project-grid">

    <div class="project-card">
        <img src="https://imgs.search.brave.com/BEXOBExRh2xODjPP7k8rWu4ZJMvskIng2xmechKnrac/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5pc3RvY2twaG90/by5jb20vaWQvMTQw/ODM4NzcwMS9waG90/by9zb2NpYWwtbWVk/aWEtbWFya2V0aW5n/LWRpZ2l0YWxseS1n/ZW5lcmF0ZWQtaW1h/Z2UtZW5nYWdlbWVu/dC5qcGc_cz02MTJ4/NjEyJnc9MCZrPTIw/JmM9VlZBeHh3aHJa/WjdhbWNQWUpyMDhM/TFpKVHlvQlZNTjZn/eXpEay00Q1hvcz0" alt="Project 1">
        <h3>Social Media App</h3>
      <p>A full-stack social media platform built with React, Node.js, and MongoDB.</p>
      <a href="#" class="btn">View Project</a>
    </div>
  
    <div class="project-card">
      <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=60" alt="E-Commerce Website">
      <h3>E-Commerce Website</h3>
      <p>Built a scalable e-commerce platform using MERN stack and Stripe integration.</p>
      <a href="#" class="btn">View Project</a>
    </div>
  
    <div class="project-card">
      <img src="https://imgs.search.brave.com/YscJylShR1vXFgPZeAV20rVQpjphW3Sxc9w7qvMkk2k/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9jb2xv/cmxpYi5jb20vd3Av/d3AtY29udGVudC91/cGxvYWRzL3NpdGVz/LzIvcG9ydGZvbGlv/LXdlYnNpdGUtYnVp/bGRlci0xMDI0eDc3/MS5qcGVn" alt="Portfolio Website">
      <h3>Portfolio Website</h3>
      <p>Designed and developed a modern portfolio using HTML, CSS, and JS.</p>
      <a href="#" class="btn">View Project</a>
    </div>
  
  </div>
  

  <!-- Contact Section -->
  <section id="contact" class="section" style="background-image: url(https://imgs.search.brave.com/nDDenKd4DeZd6-HBQ_-3VQvmO3YhL8O1AlQCBz-1Q_o/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly90NC5m/dGNkbi5uZXQvanBn/LzAyLzQyLzUzLzQ3/LzM2MF9GXzI0MjUz/NDc0NV9sam96Q1hV/UnJ3dk5QMkhFUVlP/OU1JQ2tTd0lNWTFQ/OS5qcGc);background-repeat: no-repeat;background-size: cover    ;">
    <div class="container">
      <h2>Contact Me</h2>
      <p>If you're looking to build your product, feel free to reach out!</p>
      <p>Email: <a href="mailto:youremail@example.com">gururaghav2925@example.com</a></p>
      <p>LinkedIn: <a href="#" target="_blank">linkedin.com/in/GuruRaghav</a></p>
      <p>GitHub: <a href="#" target="_blank">github.com/gururaghav2925</a></p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer" >
    <div class="container">
      <p>&copy; 2025 Guru Raghav    . Made with ❤️ for the Web.</p>
    </div>
  </footer>

</body>
</html>


```

# Style.css

```

/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  /* Global Styles */
  body {
    font-family: 'Poppins', sans-serif;
    color: #222;
    background: #f0f2f5;
  }
  
  .container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
    padding: 40px 20px;
  }
  
  a {
    text-decoration: none;
  }
  
  /* Hero Section */
  .hero {
    background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
      url('https://images.unsplash.com/photo-1542744095-291d1f67b221?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 160px 20px;
  }
  
  .hero h1 {
    font-size: 50px;
    margin-bottom: 10px;
  }
  
  .highlight {
    color: #00d4ff;
  }
  
  .tagline {
    font-size: 24px;
    margin-bottom: 30px;
    color: #ccc;
  }
  
  .btn {
    background: linear-gradient(90deg, #00d4ff, #0078ff);
    color: #fff;
    padding: 14px 32px;
    border-radius: 30px;
    font-weight: bold;
    transition: background 0.4s;
  }
  
  .btn:hover {
    background: linear-gradient(90deg, #0078ff, #00d4ff);
  }
  
  /* Sections */
  .section {
    padding: 80px 0;
  }
  
  .section h2 {
    font-size: 36px;
    margin-bottom: 20px;
    text-align: center;
    color: #0078ff;
  }
  
  /* Skills Section */
  .skills-section {
    background: #fff;
  }
  
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 20px;
    margin-top: 30px;
  }
  
  .skill-card {
    background: linear-gradient(135deg, #00d4ff 0%, #0078ff 100%);
    color: #fff;
    padding: 20px;
    text-align: center;
    border-radius: 8px;
    font-weight: bold;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
    transition: transform 0.3s;
  }
  
  .skill-card:hover {
    transform: scale(1.05);
  }
  
  /* Projects Section */
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    margin-top: 40px;
  }
  
  .project-card {
    background: #fff;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 6px 20px rgba(0,0,0,0.1);
    transition: transform 0.3s;
    text-align: center;
    height: 370px;
  }
  
  .project-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
  }
  
  .project-card h3 {
    margin: 15px 0 10px;
    font-size: 22px;
  }
  
  .project-card p {
    padding: 0 15px 20px;
    font-size: 15px;
    color: #555;
  }
  
  .project-card .btn {
    margin-bottom: 20px;
  }
  
  /* Contact Section */
  #contact a {
    color: #0078ff;
  }
  
  /* Footer */
  .footer {
    background: #222;
    color: #aaa;
    text-align: center;
    padding: 20px;
    font-size: 14px;
  }
  

```


## OUTPUT

![image](https://github.com/user-attachments/assets/65b61848-ee94-4345-af2d-dbbfa0bfcbae)

![image](https://github.com/user-attachments/assets/d6bcfe7f-c7ca-45be-9098-61decdf81a1b)


![image](https://github.com/user-attachments/assets/a402890c-d33f-4ccf-894e-ba6226c55af4)



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
