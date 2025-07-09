<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>UAH Navigation Page</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      display: flex;
      height: 100vh;
    }

    /* Sidebar */
    .sidebar {
      width: 220px;
      background-color: #002868; /* UAH Blue */
      color: white;
      display: flex;
      flex-direction: column;
      padding-top: 20px;
    }

    .sidebar h2 {
      text-align: center;
      margin-bottom: 20px;
    }

    .nav-link {
      padding: 15px 20px;
      text-decoration: none;
      color: white;
      transition: background 0.3s;
    }

    .nav-link:hover {
      background-color: #fed100; /* UAH Yellow */
      color: #002868;
    }

    /* Main Content */
    .main-content {
      flex: 1;
      padding: 30px;
      background-color: #fff;
    }

    .main-content h1 {
      color: #002868;
    }

    .btn {
      padding: 10px 20px;
      background-color: #002868;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    .btn:hover {
      background-color: #fed100;
      color: #002868;
    }
  </style>
</head>
<body>

  <div class="sidebar">
    <h2>Navigation</h2>
    <a class="nav-link" href="https://www.uah.edu/ccre" target="_blank">Visit UAH CCRE</a>
  </div>

  <div class="main-content">
    <h1>Welcome to the Cyber Education Portal</h1>
    <p>This page provides easy access to key resources and cybersecurity education tools.</p>
    <button class="btn" onclick="goToCCRE()">Go to UAH CCRE</button>
  </div>

  <script>
    function goToCCRE() {
      window.open("https://www.uah.edu/ccre", "_blank");
    }
  </script>

</body>
</html>
