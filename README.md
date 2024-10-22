<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Responsive Page</title>
    <style>
      body {
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        margin: 0;
        padding: 0;
        background-color: rgb(245, 239, 184);
      }
      header {
        background-color: #fc09db;
        color: rgb(13, 14, 10);
        padding: 10px 20px;
        display: flex;
        justify-content: flex-start;
      }
      h1 {
        text-align: center;
        padding: 3%;
        margin: 3%;
      }
      h2 {
        text-align: center;
        padding: 3%;
        margin: 3%;
      }

      nav {
        display: flex;
        gap: 15px;
      }
      nav a {
        color: rgb(253, 253, 253);
        text-decoration: none;
      }
      nav a:hover {
        text-decoration: underline;
        color: rgb(0, 0, 0);
      }
      main {
        height: 100vh;
        overflow: hidden;
      }
      section {
        display: none;
        height: 100%;
        padding: 20px;
      }
      section.active {
        display: block;
      }
      footer {
        background-color: #fc04fc;
        color: rgb(0, 0, 0);
        text-align: center;
        padding: 10px 0;
        position: relative;
        bottom: 0;
        width: 100%;
      }
      img,
      video {
        max-width: 400%;
        height: auto;
        display: block;
        margin: 10px auto;
      }
      .medium-text {
        font-size: 20px;
        font-weight: bold;
        text-align: center;

      }
      .large-text {
        font-size: 29px;
        font-weight: bold;
        text-align: center;
      }
    </style>
  </head>
  <body>
    <header>
      <nav>
        <a href="#" onclick="showSection('home')">Home</a>
        <a href="#" onclick="showSection('about')">About Me</a>
        <a href="#" onclick="showSection('projects')">My Projects</a>
      </nav>
    </header>

    <main>
      <section id="home" class="active">
        <h1>👩🏼‍💻I'm Maria Weathington👩🏼‍💻</h1>
        <video controls>
          <source
            src="https://www.w3schools.com/html/mov_bbb.mp4"
            type="video/mp4"
          />
        </video>
        <p class="medium-text">A Software Developer based in America.</p>

        <p class="large-text">I specialize in creating efficient and scalable software solutions.
        </p>
      </section>


      <section id="about">
        <h2>About Me</h2>
        <p>Maria Weathington is an aspiring software developer with a passion for coding and design. Born and raised in Detroit, Michigan, Maria discovered her love for programming through SheCodes.io, where her curiosity blossomed into a full-fledged career as a Front-End Developer. As a creative and innovative thinker, Maria is drawn to the limitless possibilities that software development offers. She finds joy in the process of creating and designing digital solutions, seeing each project as an opportunity to bring ideas to life through code.

Maria's goal is to join a forward-thinking company where she can apply her skills, contribute to innovative projects, and be apart of a great team. With her enthusiasm for learning and her ability to meet deadlines, Maria is poised to make significant contributions to the tech industry.

Her journey from curious beginner to dedicated coder exemplifies her determination and adaptability – qualities that make her an asset to any development team. Maria's unique blend of creativity and technical skills positions her as a promising talent in the world of software development.   
        </p>
      </section>
