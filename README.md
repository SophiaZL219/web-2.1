<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adobe XD Project Embed</title>
    <style>
        /* Reset margin, padding, and box-sizing for all elements */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Style body and html to fill the screen and center content */
        body, html {
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #e6e6e6; /* Soft background color */
            overflow: hidden;
            font-family: Arial, sans-serif;
        }

        /* Container to center iframe and add optional styling */
        .iframe-container {
            width: 90vw; /* 90% of the viewport width */
            height: 90vh; /* 90% of the viewport height */
            max-width: 1920px;
            max-height: 1080px;
            border-radius: 8px; /* Rounded corners */
            overflow: hidden;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); /* Subtle shadow */
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #ffffff; /* Container background color */
        }

        /* Responsive iframe styling */
        iframe {
            width: 100%;
            height: 100%;
            border: none;
        }

        /* Responsive styling for small screens */
        @media (max-width: 768px) {
            .iframe-container {
                width: 100vw;
                height: 100vh;
                border-radius: 0; /* Remove rounded corners for full screen */
            }
        }
    </style>
</head>
<body>
    <div class="iframe-container">
        <iframe src="https://xd.adobe.com/embed/a9cb50fe-b8ea-417b-95f6-c0f924a3092f-fc98/?fullscreen" allowfullscreen></iframe>
    </div>
</body>
</html>
