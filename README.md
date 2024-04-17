<html>

<head>
    <style>
        body {
            background-image: url('https://images.pexels.com/photos/6847584/pexels-photo-6847584.jpeg');
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
            color: black; /* Set text color to black */
            font-family: Georgia, serif; /* Set font to Georgia */
            margin: 0; /* Remove default margin */
            padding: 0; /* Remove default padding */
        }

        /* Container to center content vertically */
        .container {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: flex-start; /* Align items to the left */
            min-height: 100vh; /* Full height of viewport */
            padding: 20px; /* Add padding for spacing */
        }

        /* Adjustments for better readability */
        h1,
        p {
            text-align: center;
            margin: 0; /* Remove default margin */
            padding: 20px;
            border-radius: 10px;
        }

        /* Email button */
        .email-button {
            background-color: #ffb6c1; /* Cozy pastel pink */
            padding: 10px 20px;
            border: none;
            border-radius: 30px; /* Rounded corners */
            cursor: pointer;
            text-decoration: none;
            color: black;
            font-family: Georgia, serif;
            transition: background-color 0.3s ease; /* Smooth hover transition */
            position: fixed; /* Set position to fixed */
            top: 20px; /* Distance from top */
            right: 20px; /* Distance from right */
        }

        .email-button:hover {
            background-color: #ff99ac; /* Lighter shade of pink on hover */
        }

        /* Contact me text */
        .contact-me {
            position: absolute; /* Set position to absolute */
            bottom: 20px; /* Distance from bottom */
            right: 20px; /* Distance from right */
            background-color: rgba(255, 255, 255, 0.5); /* Semi-transparent white background */
            padding: 10px 20px;
            border-radius: 10px;
        }
    </style>
</head>

<body>

    <div class="container">
        <h1 style="font-size: 40px;">Bogdan Luchian</h1>
        <p>Welcome to Bogdan Luchian's Cozy Corner of Motion Design!</p>

        <h2>About Me</h2>
        <p>Hello there! I'm Bogdan Luchian, a passionate motion designer with a love for creativity and aesthetics. I believe in the power of motion to tell stories, evoke emotions, and captivate audiences.</p>
    </div>
    <!-- Contact me text -->
    <div class="contact-me">
        <h2>Contact Me</h2>
        <p>If you're interested in collaborating or have any inquiries, feel free to reach out to me:</p>
        <a class="email-button" href="mailto:bogdanel.luchian@gmail.com">bogdanel.luchian@gmail.com</a>
    </div>

</body>

</html>

