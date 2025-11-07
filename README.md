<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Text Tutorial</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background: #eee;
      padding: 0.5rem;
      text-align: center;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #4CAF50;
    }
    main {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
      background: white;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h2 {
      color: #4CAF50;
    }
    footer {
      background: #ddd;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>How to setup Git and link GitHub account</h1>
  </header>
  <nav>

  </nav>
  <main>
  
    <section id="Install">
      <h2>How to install Git and GitHub</h2>
      <ol>
      <li> Go to their website <code>https://git-scm.com/install/ </code>
      <li>Download and Install Git based on your operating system.
      <li>Create a new folder, right click inside the new folder and click open Git Bash here. In Windows 11,       right click inside the folder then click "show more options".</li>
             </section>
    <section id="Checking">
      <h2>How to check if Git is installed properly</h2>
      <ol>
<li>Click on the directory and type cmd.<li>After typing cmd, type <code> code .</code> <li>	If it doesn't open VStudio and show a text with the folder name, Do step 3 in installation again.</li>

      </ol>
    </section>
    <section id="Link">
      <h2>How to link Git to GitHub</h2>
      <ol>
       <li>Open Git again and type the following </li>
       <ul> 
      <li> <code>$ git config --global user.name "Your Name"
      <li> $ git config --global user.email "your email address used in your GitHub account"
      <li> $ git config --global push.default matching
      <li> $ git config --global alias.co checkout
      <li> $ git init</code></ul>
      <li>Create a new repository and type your desired name. 
      Then you should see </li>
      <ul> <li> <code>git init
      <li> git add README.md
      <li> git commit -m "first commit"
      <li> git branch -M main
      <li> git remote add origin (your own link)
      <li> git push -u origin main </code>
      </ul>


      </ol>
    </section>
  </main>
  <footer>
    &copy; 2025 Text Tutorial Site. All rights reserved.
  </footer>
</body>
</html>