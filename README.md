<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Website</title>
  <style>
    @import url('https://fonts.googleapis.com/css?family=Montserrat:700|Nunito:400');

    :root {
      --text: #050315;
      --background: #fcfbfd;
      --primary: #837f98;
      --secondary: #d39dcb;
      --accent: #a6b891;
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
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 0;
      padding: 20px;
      row-gap: 20px; /* Add vertical spacing between rows */
    }

    .section {
      padding: 5px;
      text-align: center;
      min-height: 200px;
      background-color: white;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      border-radius: 10px;
    }

    .section-1 {
      background-color: var(--primary);
      grid-column: span 2; /* Full width row */
    }

    .section-2 {
      background-color: var(--secondary);
      grid-column: span 2; /* Full width row */
    }

    .section-3 {
      background-color: var(--accent); /* Green */
      grid-column: span 1; /* Half width */
    }

    .section-4 {
      background-color: var(--primary); /* Grey */
      grid-column: span 1; /* Half width */
    }

    .achievement-box {
      background-color: white;
      padding: 10px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      max-width: 100%;
      margin: 0 auto;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Website</h1>
  </header>

  <div class="container">
    <!-- Full-width section -->
    <section class="section section-1">
      <h2>Introduction</h2>
      <p>Welcome to my website. This is the first section.</p>
    </section>

    <!-- Full-width section with inner white box -->
    <section class="section section-2">
      <h2>My Recent Achievement</h2>
      <div class="achievement-box">
        <p>This is where my recent achievements will be displayed.</p>
      </div>
    </section>

    <!-- Two boxes side by side with spacing below -->
    <section class="section section-3">
      <h2>About Me</h2>
      <p>Learn more about me and my journey here.</p>
    </section>

    <section class="section section-4">
      <h2>Contact</h2>
      <p>Feel free to reach out for any inquiries.</p>
    </section>
  </div>
</body>
</html>
