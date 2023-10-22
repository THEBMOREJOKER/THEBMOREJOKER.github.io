<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Joker Stake Pool</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" integrity="NEW-INTEGRITY-VALUE-GOES-HERE" crossorigin="anonymous">
    <!-- <link rel="stylesheet" href="styles.css"> -->
    <style>
        body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #1a1a2e;
    color: #e0e0e0;
}

.container {
    width: 80%;
    max-width: 1200px;
    margin: 90px auto;
    background-color: #2a2a3e;
    padding: 40px;
    border-radius: 10px;
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.2);
}

.logo {
    float: left;
    margin-right: 20px;
}

.logo img {
    max-width: 100px;
}

h1 {
    font-size: 2.5em;
    margin-top: 50px;
}

.features {
    clear: both;
    list-style-type: none;
    padding: 0;
    margin-top: 50px;
}

.features li {
    margin-bottom: 10px;
    padding-left: 20px;
    position: relative;
}

.features li::before {
    content: '•';
    position: absolute;
    left: 0;
    color: #007acc;
}

.about {
    margin: 30px 0;
    margin-top: 50px;
}

.about h2 {
    font-size: 2em;
    margin-bottom: 20px;
}

.buttons {
    display: flex;
    justify-content: flex-start;
    gap: 10px;
    margin-top: 50px;
}

button {
    padding: 10px 25px;
    border: 2px solid #6e6edf; /* blueish outline */
    border-radius: 25px; /* Rounded corners */
    background: linear-gradient(135deg, #6e6edf, #9393f9);
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px; /* Spacing between the icon and text */
}

button:hover {
    background: linear-gradient(135deg, #5a5ac9, #8080e3); /* Slightly darker gradient on hover */
    color: #fff;
}

.pool-tools::before, .stake::before {
    content: url('path_to_your_icon.svg'); /* Replace with the path to your icon */
    display: inline-block;
    margin-right: 5px;
}

/* Social Icons Styling */
.social-icons {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    gap: 15px;
    margin-top: 20px;
    margin-bottom: 20px;
}

.icon i {
    font-size: 40px; /* Adjust icon size */
    border: 2px solid #6e6edf;
    border-radius: 50%;
    padding: 5px;
    transition: transform 0.3s, background-color 0.3s, color 0.3s;
    color: #6e6edf; /* Icon color */
}

.icon:hover i {
    transform: scale(1.1);
    background-color: #6e6edf;
    color: #fff; /* Icon color on hover */
}

.pool-tools {
    /* Button styles here */
    display: inline-block; /* makes the anchor tag behave like a block element */
    padding: 10px 20px;
    border: none;
    border-radius: 25px;
    background: linear-gradient(to right, #673ab7, #512da8); /* Sample gradient */
    color: white;
    text-decoration: none; /* removes underline from anchor tag */
    cursor: pointer;
    transition: background 0.3s ease;
}

.pool-tools:hover, .stake:hover {
    /* Hover styles here, e.g., */
    background: linear-gradient(to right, #512da8, #673ab7);
}

    </style>
</head>
<body>
    <div class="container">
        <div class="logo">
            <img src="Joker.jpg" alt="Joker Logo">
        </div>
        <h1>Joker stake pool</h1>
        <ul class="features">
            <li>Only Bare-Metal servers</li>
            <li>In 2 different geographical locations</li>
            <li>Multi-layered security</li>
            <li>Emergency power source for each server node</li>
            <li>Dedicated pool operator</li>
            <li>Server monitoring 24/7</li>
        </ul>
        <div class="about">
            <h2>About US</h2>
            <p>Joker Pool is here to bring none Tech people into the Cardano ecosystem and help educate them. It is our belief that it is the SPO's job to help all people understand how the Cardano blockchain works and give the forgotten men and women the tools for self sovereignty & economic freedom. No matter where they are located in the world, we believe that understanding the fundamentals behind this technology will change their life for the better. We also believe that it is the SPO's role to help build out reliable infrastructure and actively participate in CIP-1694 that will define the governance structure for Cardano.</p>
        </div>
        <div class="buttons">
            <a href="https://pooltool.io/pool/48cfc42a91bfd8f0aeb03722e53c6f88661b5d4e0e5b94069459e703/epochs" class="pool-tools" target="_blank" rel="noopener noreferrer">See us on Pool Tool</a>
            <!-- <a href="https://pooltool.io/pool/48cfc42a91bfd8f0aeb03722e53c6f88661b5d4e0e5b94069459e703/epochs" class="pool-tools" target="_blank" rel="noopener noreferrer">Stake with Joker</a> -->
        </div>
        <div class="social-icons">
            <div class="icon">
                <a href="https://twitter.com/The_Bmore_Joker" target="_blank">
                    <i class="fab fa-twitter"></i>
                </a>
            </div>
            <div class="icon">
                <a href="https://t.me/+hThDf23oI_dhM" target="_blank">
                    <i class="fab fa-telegram-plane"></i>
                </a>
            </div>
        </div>
        <iframe style="width:100%;height:60px" frameborder="0" src="https://img.cexplorer.io/w/widget-wide.html?pool=pool1fr8ug253hlv0pt4sxu3w20r03pnpkh2wpedegp55t8nsx28rkma&theme=dark">
            <a href="https://cexplorer.io/pool/pool1fr8ug253hlv0pt4sxu3w20r03pnpkh2wpedegp55t8nsx28rkma">pool detail on cexplorer.io</a>
        </iframe>
    </div>

</body>
</html>
