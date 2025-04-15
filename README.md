<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Website</title>
  <style>
    @import url('https://fonts.googleapis.com/css?family=Montserrat:700|Nunito:400');

    :root {
      --text: #050316;
      --background: #fdfcfd;
      --primary: #726f90;
      --secondary: #c5b4bf;
      --accent: #ad9499;
    }

    body {
      font-family: 'Nunito', sans-serif;
      font-weight: 400;
      margin: 0;
      padding: 0;
      background-color: var(--background);
      color: var(--text);
    }

    h1, h2, h3, h4, h5 {
      font-family: 'Montserrat', sans-serif;
      font-weight: 700;
    }

    html { font-size: 100%; }

    h1 { font-size: 4.210rem; }
    h2 { font-size: 3.158rem; }
    h3 { font-size: 2.369rem; }
    h4 { font-size: 1.777rem; }
    h5 { font-size: 1.333rem; }
    small { font-size: 0.750rem; }

    .container {
      display: flex;
      flex-direction: row;
      gap: 20px;
      padding: 10px;
      justify-content: flex-start;
    }

    .section {
      padding: 10px;
      min-height: 200px;
      border-radius: 10px;
      font-family: 'Nunito', sans-serif;
      display: flex;
      align-items: center;
      box-sizing: border-box;
    }

    .section-3 {
      background-color: var(--accent);
      color: var(--text);
      flex: 7;
      justify-content: flex-start;
      padding-left: 20px;
    }

    .about-content {
      display: flex;
      align-items: center;
      gap: 20px;
    }

    .about-divider {
      width: 2px;
      height: 60%;
      background-color: var(--text);
    }

    .section-4 {
      background-color: var(--primary);
      color: var(--background);
      flex: 3;
      text-align: center;
      justify-content: center;
    }

    .section-achievement {
      background-color: var(--secondary);
      width: 100%;
      padding: 40px 10px;
      text-align: center;
      box-sizing: border-box;
    }

  </style>
</head>
<body>
  <header>
    <h1>My Website</h1>
  </header>

  <div class="container">
    <!-- Side-by-side boxes -->
    <section class="section section-3">
      <div class="about-content">
        <h2>About Me</h2>
        <div class="about-divider"></div>
        <p>Learn more about me and my journey here.</p>
      </div>
    </section>

    <section class="section section-4">
      <div>
        <h2>Contact</h2>
        <p>Feel free to reach out for any inquiries.</p>
      </div>
    </section>
  </div>

  <!-- Full-width achievement section -->
  <section class="section section-achievement">
    <h2>My Recent Achievement</h2>
    <p>This is where my recent achievements will be displayed.</p>
  </section>
</body>
</html>
