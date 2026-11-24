html>
<html>
<head>
    <title>Portfolio</title>
</head>
<style>
          body{
            background-color:#f0b9f0;
        }
        nav {
            background-color:#ada6ad;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 30px;
        }
        
        .logo {
            color: red;
            font-size: 25px;
        }

        
        nav ul {
            display: flex;
            list-style: none;
            gap: 20px;
            margin: 0;
            padding: 0;
        }

        
        nav a {
            text-decoration: none;
            font-size: 18px;
            color: black;
        }

        nav a:hover {
            color: white;
        }

        footer {
            
        }

        .footer-left{
          text-align:left;
        }

        .footer-right{
          text-align:right;
        }

        .social-links a {
          color: white;
          text-decoration: none;
          margin-left: 15px;
        }

        .footer {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 40px 50px;
        background-color:grey;
        color: white;
       }

       .social-links a {
      color: white;
      text-decoration: none;
      margin-left: 15px;
      }

      .logo {
      width: 60px;
      height: 60px;
      display: block;
      object-fit: contain;
      border-radius: 50%;
      background-color: white;
      }
</style>
<body>

    
    <nav>

         
        <img src="bird.PNG" alt="" width="5%"> 

        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>

    </nav>

  
    <h3 id="home" align="center">Hello, I am Mayur</h3>

    <p align="center">
        A BCA Student | Beginner Web Developer
    </p>

    <hr width="70%">

    
    <h2 id="about">About Me</h2>

    <p>
        Hello! My name is Mayur. I have completed my BCA.
        I am interested in learning new technologies and
        improving my computer skills.
        Currently, I am learning HTML, CSS and Python.
    </p>

    <hr>

  
    <h2 id="skills">My Skills</h2>

    <ul>
        <li>HTML (Basic)</li>
        <li>CSS (Learning)</li>
        <li>Python (Basic)</li>
        <li>MS Excel</li>
        <li>Basic Computer Knowledge</li>
    </ul>

    <hr>

    
    <h2 id="education">My Education</h2>

    <table border="1" cellpadding="10">
        <tr>
            <th>Course</th>
            <th>Status</th>
        </tr>

        <tr>
            <td>BCA</td>
            <td>Completed</td>
        </tr>
    </table>

    <hr>

  
    <h2>My Projects</h2>

    <h3>1. My First HTML Website</h3>

    <p>
        This is my first website which I created
        using basic HTML tags.
    </p>

    <h3>2. Personal Portfolio</h3>

    <p>
        A simple portfolio website to show my skills,
        education and projects.
    </p>

    <hr>

    
    <h2>My Hobbies</h2>

    <ul>
        <li>Learning New Things</li>
        <li>Exploring Technology</li>
        <li>Working on Computers</li>
    </ul>

    <hr>

    
    <h2 id="contact">Contact Me</h2>

    <p>Email: mayursonwani85@gmail.com</p>

    <p>Phone: 8470976553</p>

    <p>
        <a href="https://www.linkedin.com/">
            Visit My LinkedIn
        </a>
    </p>

    <hr>

   <footer class="footer">

    <div class="footer-left">
        <h3>Mayur<span>.</span></h3>
        <p>Learning today, building tomorrow.</p>
        <p>Thanks for visiting my portfolio!</p>
    </div>

    <div class="footer-right">
        <p>Designed & Built by Mayur ❤️</p>
        <p>@ 2026 All Rights Reserved.</p>

        <div class="social-links">
            <a href="#">GitHub</a>
            <a href="#">LinkedIn</a>
        </div>
    </div>

</footer>

</body>
</html>
