---
title: Sustainability Assessment
image: assets/img/icons/3.png
description: Our team provides sustainability assessments for financial institutions, helping them understand their current sustainability practices and identify areas for improvement.
---
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }}</title>
    <style>
        /* Styles for sticky footer */
        body {
            display: flex;
            flex-direction: column;
            min-height: 100vh; /* make sure the body takes at least the full height of the viewport */
        }

        main {
            flex: 1 0 auto; /* this will ensure it takes up all available space and pushes the footer down */
        }

        footer {
            flex-shrink: 0; /* this ensures the footer doesn't shrink if there's a lot of content */
            background-color: #7818e7; /* adjusted purple color for the footer */
        }
    </style>
</head>

<body>

    <!-- Header with Image, Title, and Description -->
    <header style="background: linear-gradient(to bottom, rgba(120, 24, 231, 0.6), rgba(120, 24, 231, 0.6)), url({{ page.image }}) no-repeat center center; background-size: cover; height: 60vh;">
        <div style="background-color: rgba(0, 0, 0, 0.7); padding: 20px 40px; border-radius: 10px; text-align: center; max-width: 800px; margin: 0 auto;">
            <h1 style="color: white; font-size: 2.5em; margin-bottom: 15px;">{{ page.title }}</h1>
            <p style="color: white; font-size: 1.2em;">{{ page.description }}</p>
        </div>
    </header>

    <!-- Main Content Area -->
    <main style="padding: 50px 20px;">
        <div style="max-width: 800px; margin: 0 auto;">
            <p>
                More detailed content about {{ page.title }} can go here. This section provides ample space to expand upon the service, share case studies, or provide related resources.
            </p>
            <!-- You can add more sections, images, and other content elements here -->
        </div>
    </main>

    <!-- Optional Footer -->
    <footer style="padding: 20px; text-align: center;">
        <p style="color: white; margin: 0;">&copy; 2023 Circunetics Research</p>
    </footer>

</body>
</html>
