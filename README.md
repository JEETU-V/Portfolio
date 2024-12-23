# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            background:rgb(13, 13, 71);
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background:rgb(240, 100, 50);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 1rem;
        }
        nav a:hover {
            background:rgb(13, 13, 71)
        }
        .container {
            padding: 1rem 2rem;
        }
        .section {
            margin: 2rem 0;
           
        }
        .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .project {
            border: 1px solid #ccc;
            padding: 1rem;
            width: calc(33% - 2rem);
            box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.1);
        }
        .project img {
            max-width: 100%;
            height: auto;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background: #333;
            color: white;
            margin-top: 2rem;
        }
       
        .p1 {
            text-align: center;
        }
        .head1{
            text-align: center;
        }
       
       
    </style>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <p>Welcome to my personal portfolio website!</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">

        <section id="about" class="section">
            <h2 class="head1" >About Me</h2>
            <p >Hi, I'm Vijay Umbare, a programmer. I specialize in basic coding.</p>
            <P>
                Currently i am pursuing my undergraduation degree from <b>ZEAL Institute of Engg,Pune</b>.
            </P>
            <P>
                I have done my HSC from <b>Fergusson College,Pune</b>.
            </P>
           <P>
          Some of my hobbies with Coding are playing<BR> 1.Chess <br>2.Cricket<br>3.Rifle Shooting
           </P>
           <P>

           </P>
        </section><BR>
        <section id="projects" class="section">
            <h2>Projects</h2>
            <div class="projects">
                <div class="project">
                   <a href="lab10.html">
                    <h3>Project 1</h3></a>
                    <p><b>Time Table.</b> </p>
                </div>
                <div class="project">
        
                   <a href="lab14.html"> <h3>Project 2</h3></a>
                    <p><B>Responsive Web Design.</B></p>
                </div>
            </div>
        </section>
        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:hiname0529@gmail.com">hiname0529@gmail.com</a></p>
            <p>Phone: 932529****</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Vijay. All rights reserved.</p>
    </footer>
</body>
</html>
