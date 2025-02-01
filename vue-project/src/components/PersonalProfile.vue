<template>
<div class="container">

       
    <header>
        <h1>Jeross Profile Web Page</h1>
        <nav>
            <ul>
                <li><a href="#about-me">About Me</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#course">Course</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#hobbies">Hobbies</a></li>
                <li><a href="#goals">Goals</a></li>
            </ul>
        </nav>
    </header>


    <main>
        <section class="main-content">
            <article id="about-me">
                <div>
                    <h2>About Me</h2>
                    <p>Hello! I am Jeross Reilan R. Perez from Mandaluyong City. I love going out and I am very active when it comes to physical activities, although I am not sporty.</p>
                </div>
            </article>

            <article id="education">
                <div>
                    <h2>Education / Achievements</h2>
                    <ul>
                        <li>High School - <a href="https://www.facebook.com/officialgscs/" target="_blank">Good Shepherd Christian School</a>, graduated with honors</li>
                        <li>Senior High School - <a href="https://www.facebook.com/RizTechUniversity" target="_blank">Rizal Technological University</a>, graduated with honors</li>
                    </ul>
                </div>
            </article>

            <article id="course">
                <div>
                    <h2>Course</h2>
                    <p>Bachelor of Science in Information Technology, specializing in Mobile and Internet Technology at <a href="https://www.facebook.com/asiapacificcollege.edu" target="_blank">Asia Pacific College</a></p>
                </div>
            </article>

            <article id="experience">
                <div>
                    <h2>IT Experience</h2>
                    <ul>
                        <li>Basic knowledge of Python</li>
                        <li>Basic knowledge of Java</li>
                        <li>Basic knowledge of Android Studio</li>
                        <li>Basic knowledge of HTML, SQL, and CSS</li>
                    </ul>
                </div>
            </article>

            <article id="hobbies">
                <div>
                    <h2>Hobbies & Interests</h2>
                    <ul>
                        <li>Playing billiards</li>
                        <li>Playing FPS online games</li>
                        <li>Watching K-dramas, sports anime, and romcoms</li>
                        <li>Going to the gym</li>
                        <li>Night rides</li>
                    </ul>
                </div>
            </article>

            <article id="goals">
                <div>
                    <h2>Goals In Life / Dream</h2>
                    <p>My goal is to graduate with a degree in IT and explore opportunities. I also aim to start a business after graduation.</p>
                </div>
            </article>

            <article>
                <div>
                    <h2>Picture Gallery</h2>
                    <table border="1">
                        <tr>
                            <td><img src="https://scontent.fmnl17-1.fna.fbcdn.net/v/t1.15752-9/465657511_812931710890618_516940610481054950_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=9f807c&_nc_ohc=IabrmiaxhFsQ7kNvgGVnOoj&_nc_zt=23&_nc_ht=scontent.fmnl17-1.fna&oh=03_Q7cD1QF7aHwL1VMVPiI9ZGZSImxsl5A_2gvas1i8oYvk1-z13Q&oe=6772E1FF" alt="Jeross Profile Image 1" width="200"></td>
                            <td><img src="https://scontent.fmnl17-2.fna.fbcdn.net/v/t1.15752-9/467481705_471466352190615_1115921761820830968_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=9f807c&_nc_ohc=ukMiw8RuxV4Q7kNvgHuLix9&_nc_zt=23&_nc_ht=scontent.fmnl17-2.fna&oh=03_Q7cD1QHSEwhYx2J6Xj5rk403Vmj_uEI1D9bowwIg_KmdI4hnbQ&oe=6772CBBD" alt="Jeross Profile Image 2" width="200"></td>
                            <td><img src="https://scontent.fmnl17-4.fna.fbcdn.net/v/t1.15752-9/467486217_448591414686905_6303604316042543305_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=9f807c&_nc_ohc=NK46rVWteawQ7kNvgHRaJGG&_nc_zt=23&_nc_ht=scontent.fmnl17-4.fna&oh=03_Q7cD1QGfy5-_EQ8eYmFtkaqo1UzxwKEMJuGh7AkqIoAShq6TGA&oe=6772ED0F" alt="Jeross Profile Image 3" width="200"></td>
                        </tr>
                    </table>
                </div>
            </article>
        </section>
    </main>

    <footer>
        <p>Asia Pacific College</p>
    </footer>
</div>
</template>

<style>
    body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
  }
  
  a {
    color: #03A9F4; 
    text-decoration: none;
  }
  
  a:hover {
    text-decoration: underline;
  }
  
  .container {
    display: grid;
    grid-template-rows: auto 1fr auto;
    height: 100vh;
    background-color: #fff;
  }
  
  header {
    background-color: #03A9F4; 
    color: white;
    padding: 20px;
    text-align: center;
    font-size: 24px;
    border-bottom: 5px solid #333;
  }
  
  footer {
    background-color: #03A9F4; 
    color: white;
    padding: 10px;
    text-align: center;
    font-size: 16px;
    border-top: 5px solid #333;
  }
  
  nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0;
    margin: 0;
  }
  
  nav ul li {
    margin: 0 15px;
    font-weight: bold;
  }
  
  nav ul li a {
    color: white;
    font-size: 18px;
    text-transform: uppercase;
  }
  
  nav ul li a:hover {
    color: #ffeb3b;
  }
  
  main {
    display: flex;
    flex-direction: row;
    padding: 20px;
    flex-wrap: wrap;
  }
  
  .main-content {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    flex: 2;
    padding: 20px;
  }
  
  .main-content > div {
    background-color: #f1f1f1;
    flex: 1 1 calc(33% - 20px);
    padding: 20px;
    text-align: center;
    line-height: 1.5;
    font-size: 16px;
    border-radius: 8px;
    transition: transform 0.3s, box-shadow 0.3s;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  
  .main-content > div:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
  }
  
  .main-content h2 {
    font-size: 20px;
    color: #03A9F4; 
    margin-bottom: 10px;
  }
  
  .main-content ul {
    padding-left: 20px;
    text-align: left;
  }
  
  .main-content ul li {
    font-size: 14px;
    margin: 5px 0;
  }
  
  .main-content p {
    font-size: 14px;
    line-height: 1.6;
    color: #666;
  }
  
  .sidebar {
    flex: 1;
    background-color: #f5f5f5;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  
  button {
    background-color: #03A9F4; 
    font-size: 16px;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
  }
  
  button:hover {
    background-color: #0288D1; 
  }
  
  table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
  }
  
  table td {
    text-align: center;
    padding: 10px;
  }
  
  table img {
    width: 100%;
    max-width: 200px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  
  @media (max-width: 768px) {
    .main-content > div {
        width: 100%;
        margin: 5px 0;
    }
  
    .main-content {
        flex-direction: column;
    }
  
    .sidebar {
        display: none;
    }
  
    nav ul {
        flex-direction: column;
        padding-top: 10px;
    }
  
    nav ul li {
        margin: 10px 0;
    }
  }
  
  @keyframes fadeIn {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
    }
  }
  
  .main-content > div {
    animation: fadeIn 1s ease-in;
  }
  
</style>