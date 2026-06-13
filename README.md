# Dynamic-Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>HarryPortfolio</title>
    <link rel="stylesheet" href="index.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<style>
  
body {
    margin: 0;
    padding:5px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    background-color: #f4fef1;
    color: #000000;
   
}

    

/* Header and Navigation */
header {
    background-color: #2c3e50;
    color: white;
    padding: -3px 0;
    text-align: center;
   
}

header h1 {
    margin: 0;
    font-size: 2em;
}
nav {
      /* give background so content doesn’t overlap */
   margin-top: 10px;
}
.fixed {
  position: fixed;
  top: 0cqh;
  width: 100%;
  z-index: 1000;
  
}

.nav-link {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
    transition: color 0.3s ease;
}

.nav-link:hover {
    color: #1abc9c;
}

/* Section Styling */
section {
    padding: 5px 20px;
    max-width: 1100px;
    margin: auto;
    background-color:#eae8e8;
    margin-bottom: 10px;
    border-radius: 8px;
    box-shadow: 0 2px 5px  red (0,0,0,0.1);
    scroll-margin-top: 100px;
} 
/*section h2 {
  border-bottom: 4px solid #3498db;
    border-radius:10px;
    padding-bottom: 5px;
    
  
}*/
   
.container {
  display: flex;
  flex-direction: row;
  height: 90vh;
  margin-top:5px;
}

.left-sect, .right-sect {
  flex: 1;
  padding: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.left-sect {
  background-color: #1e1e2f;
}

.left-sect iframe {
  width: 100%;
  height:80%;
  border-radius: 10%;
  box-shadow: 0 0 6px rgba(255, 255, 255, 0.1);
}
.right-sect {
  background-color:#eae8e8;;
  flex-direction: column;
  text-align: left;
}
.right-sect img {
  width: 300px;
  height:300px;
  border-radius: 50%;
  justify-content: center;
  padding:5px 5px;
  box-shadow: 0 0 6px rgba(255, 255, 255, 0.1);
}
.right-sect h1 {
  color: #2c3e50;
  margin-bottom: 5px;
  display: inline-block;   /* shrink to text width */
  border-bottom: 4px solid #087ef5;
  border-radius:20%;
}


.right-sect p {
  font-size: 1em;
  color: #000;
  line-height: 1.2;
    margin-bottom: 5px;
    padding:2px 20px 5px 30px;
    font-weight: bold;
    
  
}
/*#about h2 {
    color: #2c3e50;
    margin-bottom: 15px;
    
 
}*/
#about h2 {
  color: #2c3e50;
  margin-bottom: 8px;
  display: inline-block;   /* shrink to text width */
  border-bottom: 4px solid #087ef5;
  border-radius:20%;
}

#about p {
    font-size: 1em;
    color: black;
    line-height: 1.2;
    margin-bottom: 10px;
    padding:2px 20px 5px 30px;
    font-weight: bold;
    
}

#skills h2 {
    color: #2c3e50;
    margin-bottom: 8px;
    display: inline-block;   /* shrink to text width */
  border-bottom: 4px solid #087ef5;
  border-radius:20%;
}
.skill-grid {
  display: grid;
  grid-template-columns:auto auto auto auto;
   grid-template-columns:(2fr);
  gap: 20px;
  padding: 20px;
  max-width: 1000px;
  margin: auto;
}

.skill-card {
    width:140px;
    height:60px;
  background-color: #f0f4f8;
  border-left: 10px solid rgb(9, 9, 235);
  border-radius: 10px;
  padding: 30px;
  text-align: center;
  font-weight: bold;
  font-size: 1.3rem;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, background-color 0.3s ease;
  cursor: pointer;
}

      .skill-card {
        display: inline-flex;
        align-items: center;
        justify-content: center;
        gap: 0.5rem;
      }

      .skill-card i {
        font-size: 1.4rem;
        transition: transform 0.2s ease, color 0.2s ease;
      }

      .skill-grid .skill-card:nth-child(1) i { color: #ff6b6b; }
      .skill-grid .skill-card:nth-child(2) i { color: #4db6ac; }
      .skill-grid .skill-card:nth-child(3) i { color: #f7b801; }
      .skill-grid .skill-card:nth-child(4) i { color: #306998; }
      .skill-grid .skill-card:nth-child(5) i { color: #1c4f8b; }
      .skill-grid .skill-card:nth-child(6) i { color: #e76f51; }
      .skill-grid .skill-card:nth-child(7) i { color: #2d9cdb; }
      .skill-grid .skill-card:nth-child(8) i { color: #f0db4f; }

      .skill-card:hover i {
        transform: scale(1.1);
      }
    
.skill-card:hover {
  transform: translateY(-5px);
  background-color: #e0e7ff;
}
#personality h2 {
     color: #2c3e50;
  margin-bottom: 8px;
  display: inline-block;   /* shrink to text width */
  border-bottom: 4px solid #087ef5;
  border-radius:20%;
}

.per-grid {
  display: grid;
  grid-template-columns:auto auto auto auto;
   grid-template-columns:(3fr);
  gap: 20px;
  padding: 20px;
  max-width: 1000px;
  margin: auto;
}

.per-card {
  width:130px;
  height:40px;
  background-color: #f7f7f7;
  border-left: 3px solid rgb(9, 9, 235);
  border-radius: 5px;
  padding: 15px;
  margin:auto;
  text-align: center;
  justify-content: center;
  font-weight: bold;
  font-size: 0.9rem;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, background-color 0.3s ease;
  cursor: pointer;
}
.per-card:hover {
  transform: translateY(-5px);
  background-color: #f9dcc2;
}

#education h2 {
     color: #2c3e50;
  margin-bottom: 8px;
  display: inline-block;   /* shrink to text width */
  border-bottom: 4px solid #087ef5;
  border-radius:20%;
}
#education p {
     font-size: 1em;
    color: black;
    line-height: 1.2;
    margin-bottom: 10px;
    padding:2px 20px 5px 30px;
    font-weight: bold;

}
span {
    font-weight: bold;
    color: #333;
    font-size:20px;
    margin-right:20px;

}

/* Projects */
#projects {
    margin-bottom: 20px;
    padding: 15px;
    
    
    border-radius: 4px;
}
#projects h2 {
     color: #2c3e50;
  margin-bottom: 8px;
  display: inline-block;   /* shrink to text width */
  border-bottom: 4px solid #087ef5;
  border-radius:20%;
}
.project-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr); /* cleaner syntax */
  gap: 50px;
  padding: 20px;
}

.pro-card {
  width: 450px;
  height: auto; /* let content define height */
  display: flex;
  flex-direction: column; /* stack children vertically */
  align-items: center;    /* center horizontally */
  margin-bottom: 20px;
  text-align: center;
  max-width: 1100px;
}

h4 {
  font-size: 18px;
  margin-bottom: 10px; /* spacing between heading and iframe */
}

iframe {
  width: 400px;
  height: 220px;
  border: none; /* optional: cleaner look */         /* removes default border */
  display: block;        /* ensures it respects margins */
  margin-top: 10px;      /* adds breathing space below the heading */
  box-sizing: border-box;
}


/*.project-grid {
  display: grid;
  grid-template-columns:auto auto;
  grid-template-columns:(2fr);
  gap:50px;
  padding: 20px;


}
.pro-card {
  width:450px;
  height:250px;
  display:flex;
  margin-bottom:20px;
  text-align: center;
  max-width:1100px;
}
h4 {

  
  font-size: 18px;
  

}
  iframe {
   width: 400px;
    height: 200px;
  }*/
  #blog h2 {
     color: #2c3e50;
  margin-bottom: 8px;
  display: inline-block;   /* shrink to text width */
  border-bottom: 4px solid #087ef5;
  border-radius:20%;
}
   #blog p{
     font-size: 1em;
    color: black;
    line-height: 1.2;
    margin-bottom: 10px;
    padding:2px 20px 5px 30px;
    font-weight: bold;
    }

#blog {
  display: flex;
  flex-direction: column;
  align-items: center;
}

#blog h2 {
  color: #2c3e50;
  margin-bottom: 20px;
  display: inline-block;
  border-bottom: 4px solid #087ef5;
  border-radius: 20%;
  width: fit-content;
}

.blog-cards-container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  width: 100%;
}

.blog-card {
  display: flex;
  flex-direction: column;
  background-color: #f0f4f8;
  border-left: 10px solid rgb(9, 9, 235);
  border-radius: 10px;
  padding: 20px;
  text-align: center;
  font-weight: bold;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, background-color 0.3s ease;
  cursor: pointer;
  width: calc(50% - 20px);
  max-width: 380px;
}

.blog-card h3 {
  margin-top: 10;
  color: #2c3e50;
  font-size: 1.1rem;
}

.blog-card a {
  display: inline-block;
  margin-top: 10px;
  padding: 8px 15px;
  background-color: #087ef5;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  transition: background-color 0.3s ease;
}

.blog-card a:hover {
  background-color: #0056b3;
  transform: translateY(-5px);
}


  #cl h2 {
   color: #2c3e50;
  margin-bottom: 8px;
  display: inline-block;   /* shrink to text width */
  border-bottom: 4px solid #087ef5;
  border-radius:20%;
  
}
#cl p{
     font-size: 1em;
    color: black;
    line-height: 1.2;
    margin-bottom: 10px;
    padding:2px 20px 5px 30px;
    font-weight: bold;
    }

/* Contact Form */
#contact {
   margin-bottom: 20px;
    padding: 15px;

}
#contact h2 {
     color: #2c3e50;
  margin-bottom: 8px;
  display: inline-block;   /* shrink to text width */
  border-bottom: 4px solid #087ef5;
  border-radius:20%;
}
form {
    display: flex;
    flex-direction: column;
}

label {
    margin-top: 10px;
    font-weight: bold;
}

input, textarea {
    padding: 10px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 1em;
}

textarea {
    resize: vertical;
    min-height: 100px;
}

button {
    margin-top: 15px;
    padding: 10px;
    background-color: #3498db;
    color: white;
    border: none;
    border-radius: 4px;
    font-size: 1em;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: #2980b9;
}

/* Footer */
footer {
  background-color: #222;
  padding: 20px 0;
  text-align: center;
}

.social-icons a {
   
   padding-left:50px; 
  color: #fff;
  margin: 0 10px;
  font-size: 24px;
  transition: color 0.3s ease;
}

.social-icons a:hover {
  color: #1da1f2; /* Twitter blue or customize per platform */
}
 p {
    color: #ccc;
    margin: 20px 0 0 0;
}
 .dr {
    color: red;
    font-size: 18px;
    font-style: italic;
}
/*footer {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 15px 0;
    font-size: 0.9em;
}*/

/* Responsive Design */
@media (max-width: 600px) {
    .nav-link {
        display: block;
        margin: 10px 0;
    }

    section {
        padding: 20px 10px;
    }
}
</style>
</head>
<body>
  
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
             <a href="#home" class = "nav-link">Home</a>
              <a href="#about" class = "nav-link">About</a>
               <a href="#skills" class = "nav-link">Skills</a>
                 <a href="#personality" class = "nav-link">Personality</a>
                <a href="#education" class = "nav-link">Education</a>
                <a href="#projects" class = "nav-link">Projects</a>
                 <a href="#blog" class = "nav-link">Blog</a>
                 <a href="#cl" class = "nav-link">CL</a>
                  <a href="#contact" class = "nav-link">Contact</a>
                  
          
        </nav>
       </header>
      
    <section id="home">
         <div class ="container">
      
      <sect class="left-sect">
      <iframe src = "C:\Users\LENOVO\OneDrive\Videos\Captures\Copy of UBER-DATASET-PRESENTATION - Google Vids - Google Chrome 2026-05-19 11-35-54.mp4"></iframe>
    </sect>
    <sect class="right-sect">
      <img src ="C:\Users\LENOVO\OneDrive\Pictures\Hareesh.jpg"
        alt="Tech Enthusiast" />

      <h1>A Data Researcher</h1>
      <p>
        Meet Harish, a dedicated data researcher with over a decade of experience 
        in market research and data analytics. Passionate about uncovering insights
         from complex datasets, specialized in qualitative and quantitative studies.
         With a strong foundation in Economics and
          complemented by advanced Business-German proficiency,
           Known for analytical problem-solving and clear communication.
          Explore the sections below to learn more about skills,
           personality, education, projects, and how to get in touch.
      </p>
      </sect>
       </div>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>I am a seasoned market researcher and data analytics professional
           with over a decade of experience in qualitative and quantitative studies.
            My expertise spans consumer profiling, brand tracking, survey design,
             and statistical evaluation, enabling businesses to make informed, data-driven decisions i.e. 
              strong fundamentals in data-driven analysis and driving meaningful insights. I'm
              skilled in managing Fields, Analytics, and Reports in research processes. I have successfully led segmentation studies, Ad-testing,
               and concept evaluations that enhanced marketing efficiency and client satisfaction.
                I'm known for my analytical problem-solving and clear communication, 
                I excelled at coordinating teams and delivering actionable insights under tight deadlines.
                 With a strong academic foundation in Economics and Indo-Germanic studies, complemented by advanced Business-German proficiency,
                 and experienced in applying DIQ technologies widely adopted across market research.
                  I can bring both technical rigor and cross-cultural perspective to my work.
</p>
    </section>
    <section id="skills">
    <h2>My-Skills</h2>
    <div class="skill-grid">
      <div class="skill-card"><i class="fas fa-chart-bar"></i> Power BI</div>
      <div class="skill-card"><i class="fas fa-file-excel"></i> Excel</div>
      <div class="skill-card"><i class="fas fa-chart-pie"></i> SAS</div>
      <div class="skill-card"><i class="fab fa-python"></i> Python</div>
      <div class="skill-card"><i class="fab fa-r-project"></i> R</div>
      <div class="skill-card"><i class="fas fa-chart-line"></i> Tableau</div>
      <div class="skill-card"><i class="fas fa-database"></i> SQL</div>
      <div class="skill-card"><i class="fab fa-js"></i> JS</div>
    </div>
  </section>
    
     <section id="personality">
        <h2>Personality</h2>
        <div class = 'per-grid'>
          <div class ="per-card">Communicator</div>
          <div class ="per-card">Problem Solver</div>
          <div class ="per-card">Team Player</div>
          <div class ="per-card">Hardworking</div>
          <div class ="per-card">Professional</div>
          <div class ="per-card">Creative</div>
          <div class ="per-card">Detail-Oriented</div>
          <div class ="per-card">Motivated</div>
          <div class ="per-card">Analytical</div>
          <div class ="per-card">Adaptable</div>
          <div class ="per-card">Curious</div>
          <div class ="per-card">Organized</div>
         </div>
    </section>
    <section id="education">
        <h2>My-Education</h2>
       <p><span>1992.</span>Goethe Certificate (Deutsch)** – Goethe Institute </p><br> 
        <p><span>1991.</span>Indo-Germanic Language, Graduation** – DU </p><br> 
         <p><span>1985.</span>Economics, Graduation** – Delhi University</p><br>
       <p><span>1982.</span>Diploma in Tourism (Domestic / International) ** – Datamatic </p><br> 
      <p><span>1982.</span>Commerce & Accounts (CBSE)</p> <br>
 </section>

    <section id="projects">
        <h2>My-Projects</h2>
        <div class="project-grid">
        
          <div class="pro-card">
          <h4>Doc-Pat-Relation PBI</h4>
        <iframe src = "C:\Users\LENOVO\OneDrive\Videos\Captures\NEWTON-DocPati 2025-10-14 20-37-57.mp4" ></iframe>
        
        </div>
        <div class="pro-card">
        <h4>Company Ranks Tableau</h4>
        <iframe src = "C:\Users\LENOVO\OneDrive\Videos\Captures\Ranking of 5000 Companies _ Tableau Public and 4 more pages - Personal - Microsoft​ Edge 2025-11-10 18-40-38.mp4"></iframe>
        </div>
           
        <div class="pro-card">
     <h4>Iris Dataset in Python</h4>
        <iframe src = "C:\Users\LENOVO\OneDrive\Videos\Captures\lab - JupyterLab - Google Chrome 2025-11-10 19-00-38.mp4"></iframe>
        </div>
          
        <div class="pro-card">
       <h4>SAS Studio Linear Regression</h4>
         <iframe src ="C:\Users\LENOVO\OneDrive\Videos\Captures\SAS Studio and 1 more page - Personal - Microsoft​ Edge 2025-11-24 18-42-44.mp4"></iframe>
         </div>
        
       </div>
    </section>
    <section id="blog">
  <h2>My Blogs</h2>
  <div class="blog-cards-container">
    <div class="blog-card">
      <h3>The Leading Digital Technologies</h3>
      <a href=https://data-analytics-blogger.blogspot.com/2025/12/the-digital-technology.html>Read More</a>
    </div>
    <div class="blog-card">
      <h3>Market Research And it's Imperitives</h3>
      <a href=https://data-analytics-blogger.blogspot.com/2024/08/market-research-domains.html>Read More</a>
    </div>
    <div class="blog-card">
      <h3>An Eos Of Generative AI</h3>
      <a href=https://data-analytics-blogger.blogspot.com/2026/01/an-eos-of-ai-generalist-how-generative.html>Read More</a>
    </div>
    <div class="blog-card">
      <h3>AI Ethics</h3>
      <a href=https://www.blogger.com/blog/post/edit/6249969930096732575/1428423605420292439>Read More</a>
    </div>
    <div class="blog-card">
      <h3>Market Research and AI</h3>
      <a href=https://www.blogger.com/blog/post/edit/6249969930096732575/6141626090884697004>Read More</a>
    </div>
    
  </div>
</section>
 <section id="cl">
   <h2>Covering Letter</h2>

  <p> Dear Hiring Manager,
With sufficient experience designing and optimizing Power BI dashboards, I specialize in translating complex datasets 
into actionable insights that drive business outcomes. My expertise in DAX, data modeling, and scalable BI solutions ens
ures performance and reliability across diverse environments. I have successfully collaborated with stakeholders to capture 
requirements and deliver intuitive, high impact reports validated against key business metrics. My understanding about BRD and FRD
 is above par. Which has honed my ability to balance governance with agility. Guided by values of integrity, teamwork, passion, 
 and inclusivity, I thrive in dynamic settings where innovation meets accountability. I am eager to bring this blend of technical 
 acumen and collaborative spirit to Interpath’s mission of delivering data driven excellence.</p>
<P>Sincerely,
Harish Kumar</p>                                                      

   <!----------<p>Dear Hiring Manager,

I am excited to apply for the Research Manager role at Agram. With 10+ years in market research, analytics, and compliance, I specialize in managing client projects end‑to‑end and delivering actionable insights across diverse sectors.

Proven track record in customized quantitative studies — from project costing and questionnaire design to execution, analysis, and reporting.

Skilled in client management, consistently exceeding expectations through consultative recommendations that support key business objectives.

Experienced in multi‑project management, coordinating cross‑functional teams and proactively resolving challenges to ensure seamless delivery.

Expertise in questionnaire design and analysis, synthesizing primary and secondary research into clear, impactful insights.

Strong communicator, adept at reporting via PowerPoint, interpreting multivariate data, and presenting findings with clarity and confidence.

Collaborative contributor in client and internal meetings, adding value through structured thinking and actionable recommendations.

I am confident my blend of technical expertise and client‑centric approach aligns with your team’s goals. I look forward to the opportunity to contribute to Agram’s success and would welcome a conversation to discuss how my experience can add value.

Best regards,
Harish Kumar</p>
    <p>I am writing to express my interest in the Data Analyst position at [Company Name],
       as advertised on [Job Board/Company Website]. With over a decade of experience in market research 
       and data analytics, I am confident in my ability to contribute effectively to your team and
        help drive data-informed decision-making process.</p>-------->

 </section>
      <section id="contact">
        <h2>Contact Me</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <div class="social-icons">
    <a href="https://facebook.com" target="_blank" aria-label="Facebook">
      <i class="fab fa-facebook-f"></i>
    </a>
    <a href="https://twitter.com" target="_blank" aria-label="Twitter">
      <i class="fab fa-twitter"></i>
    </a>
    <a href="https://instagram.com" target="_blank" aria-label="Instagram">
      <i class="fab fa-instagram"></i>
    </a>
    <a href="https://linkedin.com" target="_blank" aria-label="LinkedIn">
      <i class="fab fa-linkedin-in"></i>
    </a>
  </div>
      <p>&copy; 2025 My Portfolio<span class="dr"> @ Data Researcher</span></p>
    </footer>
     <script src="index.js"></script>
     <!------------------Market Research & Analytics Professional with 10+ years of experience delivering actionable insights
      through both qualitative and quantitative methods. Skilled in focus groups, ethnographic studies, in-depth interviews,
       and advanced data visualization, I specialize in transforming complex data into consultative storytelling that drives client decisions.
        Adept at managing end-to-end research projects, building strong client relationships, and advising mid-level stakeholders with empathy and strategic clarity.
      Proficient in Power BI, Tableau, Excel, R, SAS, and multilingual communication (English & German), I combine technical rigor with business acumen to
       deliver high-quality insights, innovative methodologies, and measurable impact. Experienced in team leadership and passionate 
       about continuous innovation in qualitative research to uncover new business opportunities.-->
       <script src = "script.js">
         

window.addEventListener("scroll", function() {
  const header = document.querySelector("header");
  if (window.scrollY > 110) {   // adjust threshold
    header.classList.add("fixed");
  } else {
    header.classList.remove("fixed");
  }
});
</script>
 </body>

</html>


