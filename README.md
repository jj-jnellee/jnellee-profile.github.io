<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <style>
        @import url('https://fonts.googleapis.com/css?family=Montserrat:700|Nunito:400');
        
        body {
            font-family: 'Nunito';
            font-weight: 400;
            margin: 0;
            padding: 0;
            background-color: #faf8e8; /* Default background color */
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
            display: flex;
            flex-direction: column;
            gap: 20px; /* Adjust space between sections */
        }

        .section {
            padding: 50px;
            text-align: center;
            min-height: 300px; /* Ensures all sections have consistent height */
        }

        .section-1 {
            background-color: #faf8e8; /* Soft light color */
        }

        .section-2 {
            background-color: #f3f2f0; /* Slightly different color */
        }

        .section-3 {
            background-color: #fefffa; /* Soft yellow */
        }

        .section-4 {
            background-color: #FFF9C4; /* Light yellow */
        }

        .achievement-box {
            background-color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            max-width: 100%;
            margin: 0 auto;
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
