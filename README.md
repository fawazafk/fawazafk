<html lang="en">


  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
      .fa {
      display: unset;
      padding: 10px;
      font-size: 20px;
      width: 30px;
      text-align: center;
      text-decoration: none;
      margin: 5px 5px;
      border-radius: 50%;
        }
      .fa:hover {
            opacity: 0.7;
        }
      .fa-linkedin {
        background: #007bb5;
        color: white;
      }
      .fa-github {
        background: black;
        color: white;
      }
      .fa-envelope {
        background: black;
        color: white;
      }
    </style>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="">
    <link rel="icon" href="../../../../favicon.ico">
    <title>Fawaz Kserawi</title>
    <link rel="stylesheet" href="https://django-portfolio-fawazafk.s3.amazonaws.com/static/css/bootstrap.min.css">
  </head>

  <body>
    <main role="main">
      <section class="jumbotron text-center" style="padding-bottom: 0px;">
        <div class="container">Hi, my name is
          <h1 class="jumbotron-heading">Fawaz Kserawi</h1>
          <h1 class="lead text-muted">I am a full stack developer with a passion for programming</h1>
          <p class="lead text-muted">I create and maintain scalable applications using different tech stacks with focus on Frameworks such as Oracle Apex, Java Spring, Python Django, Dart Conduit and Flutter.</p>
          <img src="https://django-portfolio-fawazafk.s3.amazonaws.com/static/fawaz.jpg" height="260"  style="border: 5px solid;color: rgb(176, 189, 190);"  />
          
          <div style="margin-top: 3%;"> 
          <p>
            
            <a href="mailto:fawazafk@gmail.com" class="fa fa-envelope"></a>
            <a href="https://www.linkedin.com/in/fawaz-kserawi/" class="fa fa-linkedin"></a>
            <a href="https://github.com/fawazafk/" class="fa fa-github"></a>
          </p>
          </div>

          <div class="jumbotron text-left" style="padding-top: 1%;">
            <h1>About me</h1>      
            Hello,<br>
              My Name is Fawaz, my love for programming started when I was around 10 years old and I received an Atari 800XL computer with an Atari basic language book. This may show that I am “sort of… a little bit… “ old :), however I received them years after release.
            
            <p id="textArea">...</p>
            <a id="toggleButton" onclick="toggleText()" href="javascript:void(0);">See More</a>
            
          </div> 
        </div>
      </section>
      
      <div class="album py-5 bg-light">
        <div class="container">
          <h2>Projects I've worked on:</h2>
          <div class="row">
            

            <div class="col-md-4">
              <a href="/jobs/1">
              <div class="card mb-4 box-shadow">
                <img class="card-img-top" src="https://django-portfolio-fawazafk.s3.amazonaws.com/media/images/code.jpg">
                <div class="card-body">
                  <p class="card-text">Test</p>
                </div>
              </div>
              </a>
            </div>

            
          </div>

        </div>
      </div>

    </main>

    <!-- Bootstrap core JavaScript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
    <script src="https://django-portfolio-fawazafk.s3.amazonaws.com/static/js/bootstrap.js" ></script>
    <script src="https://django-portfolio-fawazafk.s3.amazonaws.com/static/jquery-3.3.1.min.js" ></script>
    <script>
      var status = "less";
      function toggleText()
      {
          var text="I finished my Bachelor in Computer Engineering from Amman Al-Ahlia University in Jordan 2007 and landed a job at a university in Qatar as an application developer. My responsibilities are creating applications (mainly business apps) with intuitive api for different departments at the university using various technologies, mostly Oracle PL/SQL, Oracle Apex, JavaScript and Java.<br> I worked with small start-ups, creating applications on frameworks such as Oracle Apex, Java Spring, Python Django, Dart Conduit and Flutter, and took part in the Arab Innovation Academy 2019.<br>I challenged myself and continued my studies, having a steady job and a family with 2 children, and finished my Master’s Degree in Computer Science at Qatar University at the end of Spring-2021. In my studies, I upgraded my knowledge on computer science concepts such as new security concepts, machine learning, IoT, cloud computing and blockchain.<br>My love for learning made me take part in several courses/workshops/self taught online courses, such as: NDG Linux from Cisco Networking Academy, ISO 90012015 Awareness Course, Oracle Express workshop from Oracle University, Android Mobile Development, in addition to, a steady pace of online courses that you’ll find posted on my LinkedIn profile.<br>Below are some projects that I worked on.";
      
          if (status == "less") {
              document.getElementById("textArea").innerHTML=text;
              document.getElementById("toggleButton").innerText = "See Less";
              status = "more";
          } else if (status == "more") {
              document.getElementById("textArea").innerHTML = "...";
              document.getElementById("toggleButton").innerText = "See More";
              status = "less"
          }
      }
      </script>
  </body>
</html>
