<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
      body {
        margin: 0;
        padding: 0;
        font-family: Arial, sans-serif;
        box-sizing: border-box;
        height: 100vh; 
      }
      .navbar {
        width: 100%;
        position: fixed;
        top: 0;
        left: 0;
        background-color: #336633;
        padding: 10px 20px;
      }

      .navbar img {
        max-width: 100%;
        height: auto;
      }

      .content {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        height: 100vh; /* Full height of the viewport */
        margin-top: -60px; /* Compensate for the fixed navbar height */
      }

      h1 {
        margin: 0;
      }

      @media (max-width: 768px) {
        .content {
          padding: 10px;
        }

        .navbar {
          padding: 10px;
        }

        h1 {
          font-size: 1.5rem; /* Smaller font size for smaller screens */
        }
      }
    </style>
  </head>
  <body>
    <div>
      <nav class="navbar">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">
            <img src="https://static.wixstatic.com/media/f6f74b_37b4531648964a5398f95156ffd7f6cb~mv2.png/v1/fill/w_4000,h_4000,al_c/gmu_logo.png" alt="Logo" width="100" height="60" class="d-inline-block align-text-top">
          </a>
        </div>
      </nav>
    </div>

    <div class="content" itemscope itemtype="https://schema.org/teaches">
      <h1 itemprop="name">AIT 582 DL1 - Applications of Metadata in Complex Big Data Problems</h1>
      <div itemprop="professor" itemscope itemtype="https://schema.org/Role">
        Professor: <span itemprop="name">Dr. Can Nguyen</span>
      </div>
      <p>
        Assignment 3 </br>
        Final Project Start Date: 
        <time itemprop="startDate" datetime="2023-08-27">08/27/23</time>
      </p>
      <a href="https://mason.gmu.edu/~spuchak/" itemprop="url">Link</a>
    </div>
    <script src="script.js"></script>
  </body>
</html>
