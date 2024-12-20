# group6psuwebsite
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Homepage PANGASINAN STATE UNIVERSITY</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: white; /* Default text color */
            background-image: url('psubackground.jpg'); /* Full page background image */
            background-size: cover; /* Cover the entire page */
            background-position: center; /* Center the image */
            min-height: 100vh; /* Ensure it takes at least full viewport height */
        }
        .header {
            background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent background for header */
            color: white;
            padding: 10px 20px;
            text-align: left;
        }
        .selection {
            margin: 20px;
            display: flex;
            align-items: center;
        }
        .button {
            background-color: #008CBA; /* Blue */
            border: none;
            color: white;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            margin-right: 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #005f73; /* Darker blue */
        }
        .content {
            display: flex; /* Use flexbox for layout */
            justify-content: space-between; /* Space between the boxes */
            padding: 20px;
            min-height: 100vh; /* Ensure it takes at least full viewport height */
        }
        .box {
            background-color: rgba(0, 0, 0, 0.5); /* Dark background for boxes */
            padding: 20px;
            border-radius: 5px;
            width: 45%; /* Set width for boxes */
        }
        .overlay {
            position: absolute; /* Position absolute to cover content */
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.5); /* Dark overlay */
            z-index: 1; /* Ensure overlay is above the background */
        }
        .content-inner {
            position: relative; /* Position relative for z-index */
            z-index: 2; /* Ensure content is above the overlay */
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>PANGASINAN STATE UNIVERSITY</h1>
        <div class="selection">
            <a href="home.html" class="button">Home</a>
            <a href="colleges.html" class="button">Colleges</a>
            <a href="C:\Users\geral\OneDrive\Desktop\GROUP 6 FINAL LAB\HOME PAGE\aboutus.html" class="button">About us</a>
        </div>
    </div>

    <div class="content">
        <div class="box">
            <h1>GROUP 6 - CC101 BSIT1</h1>
            <h2>Bumatay, Mica Jean A.<h2>
<h2>Del Fierro, Gerald Jr S.</h2>
<h2>Laurencio, Karl Cedrik R.</h2>
<h2>Leonor, Jhe lourd</h2>
<h2>Ochinang, Messi Leah S.</h2>
<h2>Sinopera, James Michael</h2>
        </div>
        <div class="box">
            <h1>VISION</h1>
            <h2>To be a leading industry-driven State University in the ASEAN region by 2030.</h2>
            <h1>MISION</h1>
            <h2>The Pangasinan State University, shall provide a human-centric, resilient , and sustainable academic environment to produce dynamic, responsive, and future-ready individuals capable of meeting the requirements of the local and global communities and industries.</h2>
        </div>
    </div>

</body>
</html>
