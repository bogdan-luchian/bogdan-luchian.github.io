<!DOCTYPE html>
<html>

<head>
    <style>
        body {
            background-image: url('https://images.pexels.com/photos/6847584/pexels-photo-6847584.jpeg');
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
            color: #333; /* Set text color to dark gray */
            font-family: 'Apparel Bolt', serif; /* Set font to Apparel Bolt for normal text */
            margin: 0; /* Remove default margin */
            padding: 0; /* Remove default padding */
        }

        /* Container to center content vertically */
        .container {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center; /* Align items to the center */
            min-height: 100vh; /* Full height of viewport */
            padding: 20px; /* Add padding for spacing */
            position: relative; /* Make container position relative */
        }

        /* Adjustments for better readability */
        h1,
        h2,
        p {
            text-align: center;
            margin: 0; /* Remove default margin */
            padding: 10px; /* Add padding */
            border-radius: 10px;
        }

        /* Titles */
        h1,
        h2 {
            font-family: 'Apparel Black', serif; /* Set font to Apparel Black for titles */
            font-size: 36px; /* Increase font size for titles */
        }

        /* Contact button */
        .contact-button {
            position: absolute; /* Position button absolutely */
            top: 20px; /* Distance from top */
            right: 20px; /* Distance from right */
            background-color: #ffb732; /* Cozy orange-yellow */
            padding: 10px 20px;
            border: none;
            border-radius: 30px; /* Rounded corners */
            cursor: pointer;
            text-decoration: none;
            color: #333; /* Set text color to dark gray */
            font-family: 'Apparel Bolt', serif; /* Set font to Apparel Bolt for button text */
            transition: background-color 0.3s ease; /* Smooth hover transition */
            font-size: 16px; /* Set font size */
        }

        .contact-button:hover {
            background-color: #ffac2e; /* Lighter shade of orange-yellow on hover */
        }

        /* About button */
        .about-button {
            position: absolute; /* Position button absolutely */
            top: 20px; /* Distance from top */
            left: 20px; /* Distance from left */
            background-color: #ffb732; /* Cozy orange-yellow */
            padding: 10px 20px;
            border: none;
            border-radius: 30px; /* Rounded corners */
            cursor: pointer;
            text-decoration: none;
            color: #333; /* Set text color to dark gray */
            font-family: 'Apparel Bolt', serif; /* Set font to Apparel Bolt for button text */
            transition: background-color 0.3s ease; /* Smooth hover transition */
            font-size: 16px; /* Set font size */
        }

        .about-button:hover {
            background-color: #ffac2e; /* Lighter shade of orange-yellow on hover */
        }

        /* About text */
        #aboutText {
            display: none; /* Initially hide about text */
        }

        /* Contact info */
        .contact-info {
            text-align: center;
            margin-top: 50px; /* Add margin to separate from other content */
        }

        .email-button {
            background-color: #ffb6c1; /* Cozy pastel pink */
            padding: 10px 20px;
            border: none;
            border-radius: 30px; /* Rounded corners */
            cursor: pointer;
            text-decoration: none;
            color: #333; /* Set text color to dark gray */
            font-family: 'Apparel Bolt', serif; /* Set font to Apparel Bolt for button text */
            transition: background-color 0.3s ease; /* Smooth hover transition */
            font-size: 16px; /* Set font size */
            margin-top: 20px; /* Add margin to separate from other content */
        }

        .email-button:hover {
            background-color: #ff99ac; /* Lighter shade of pink on hover */
        }
    </style>
</head>

<body>

    <div class="container">
        <h1>Bogdan Luchian</h1>
        <p>Welcome to Bogdan Luchian's Cozy Corner of Motion Design!</p>

        <h2>About Me</h2>
        <p id="aboutText">Hello there! I'm Bogdan Luchian, a passionate motion designer with a love for creativity and aesthetics. I believe in the power of motion to tell stories, evoke emotions, and captivate audiences.</p>

        <!-- Contact button -->
        <button class="contact-button" onclick="toggleContact()">Contact Me</button>

        <!-- About button -->
        <button class="about-button" onclick="toggleAbout()">About Me</button>

        <!-- Contact info -->
        <div class="contact-info">
            <h2>Contact Me</h2>
            <p>If you're interested in collaborating or have any inquiries, feel free to reach out to me:</p>
            <a class="email-button" href="mailto:bogdanel.luchian@gmail.com">bogdanel.luchian@gmail.com</a>
        </div>
    </div>

    <script>
        function toggleContact() {
            var contactInfo = document.querySelector('.contact-info');
            if (contactInfo.style.display === 'none') {
                contactInfo.style.display = 'block';
            } else {
                contactInfo.style.display = 'none';
            }
        }

        function toggleAbout() {
            var aboutText = document.getElementById('aboutText');
            if (aboutText.style.display === 'none') {
                aboutText.style.display = 'block';
            } else {
                aboutText.style.display = 'none';
            }
        }
    </script>

</body>

</html>




