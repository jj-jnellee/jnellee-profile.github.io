<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <style>
        @import url('https://fonts.googleapis.com/css?family=Montserrat:700|Nunito:400');
        
        /* Color Scheme Variables */
        :root {
            --text: #050315;
            --background: #fcfbfd;
            --primary: #837f98;
            --secondary: #d39dcb;
            --accent: #a6b891;
        }

        body {
            font-family: 'Nunito';
            font-weight: 400;
            margin: 0;
            padding: 0;
            background-color: var(--background); /* Set background color */
            color: var(--text); /* Set text color */
        }

        h1, h2, h3, h4, h5 {
            font-family: 'Montserrat';
            font-weight: 700;
        }

        html {font-size: 100%;} /* 16px */

        h1 {font-size: 4.210rem; /* 67.36px */}

        h2 {font-size: 3.158rem; /* 50.56px */}

        h3 {font-size: 2.369rem; /* 37.92px */}

        h4 {font-size: 1.777rem; /* 28.48px */}

        h5 {font-size: 1.333rem; /* 21.28px */}

        small {font-size: 0.750rem; /* 12px */}

        .container {
            display: grid;
            grid-template-columns: repeat(2, 1fr); /* 2 columns */
            gap: 0; /* Removed gap */
            padding: 20px;
        }

        .section {
            padding: 5px; /* Reduced padding */
            text-align: center;
            min-height: 200px; /* Minimum height to ensure uniformity */
            background-color: white; /* White background for each section */
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 10px; /* Rounded edges */
        }

        .section-1 {
            background-color: var(--primary); /* Primary color */
            grid-column: span 1; /* Default width */
        }

        .section-2 {
            background-color: var(--secondary); /* Secondary color */
            grid-column: span 2; /* Spans across 2 columns */
        }

        .section-3 {
            background-color: var(--accent); /* Accent color */
            grid-column: span 1; /* Default width */
        }

        .section-4 {
            background-color: var(--primary); /* Primary color */
            grid-column: span 2; /* Spans across 2 columns */
        }

        .achievement-box {
            background-color: white;
            padding: 10px;
            text-align: center;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            max-width: 100%;
            margin: 0 auto;
            border-radius: 10px; /* Rounded edges */
        }
    </style>
</head>
<body>
    <header>
        <h1>My Website</h1>
    </header>

    <div class="container">
        <section class="section section-1">
            <h2>Introduction</h2>
            <p>Welcome to my website. This is the first section.</p>
        </section>

        <section class="section section-2">
            <h2>My Recent Achievement</h2>
            <div class="achievement-box">
                <p>This is where my recent achievements will be displayed.</p>
            </div>
        </section>

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
