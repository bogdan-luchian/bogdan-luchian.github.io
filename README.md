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
        #aboutContainer {
            display: none; /* Initially hide about container */
        }
    </style>
</head>

<body>

    <div class="container">
        <div id="aboutContainer">
            <h1>Bogdan Luchian</h1>
            <h2>About Me</h2>
            <p>Hello there! I'm Bogdan Luchian, a passionate motion designer with a love for creativity and aesthetics. I believe in the power of motion to tell stories, evoke emotions, and captivate audiences.</p>
        </div>

        <!-- About button -->
        <button class="about-button" onclick="toggleAbout()">About Me</button>
    </div>

    <script>
        function toggleAbout() {
            var aboutContainer = document.getElementById('aboutContainer');
            if (aboutContainer.style.display === 'none') {
                aboutContainer.style.display = 'block';
            } else {
                aboutContainer.style.display = 'none';
            }
        }
    </script>

</body>

</html>





