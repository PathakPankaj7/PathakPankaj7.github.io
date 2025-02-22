<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>

    <!-- Include Vanta.js and Three.js -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r134/three.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/vanta/0.5.24/vanta.dots.min.js"></script>

    <style>
        /* Ensures Vanta.js Background Covers the Page */
        #vanta-bg {
            position: fixed;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            z-index: -1;
        }

        /* Page Styling */
        .content {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.6;
            color: #333333;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            text-align: justify;
            font-size: 16px;
            position: relative;
            z-index: 1; /* Ensures content stays above background */
            background: rgba(255, 255, 255, 0.9); /* Light background for readability */
            border-radius: 10px;
            padding: 30px;
        }

        .logo-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            font-size: 12px;
        }

        .logo-column {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .logo-column img {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>

    <!-- Animated Background -->
    <div id="vanta-bg"></div>

    <!-- Content Section -->
    <div class="content">
        <h1>About Me</h1>
        <p>Thank you for visiting my website.</p>
        <p>
            I am a Postdoctoral Research Associate at the University of Cambridge, specializing in spintronics and magnetism. My research focuses on exploring novel physics and device applications in next-generation spintronic technologies. I earned my Ph.D. in Electrical Engineering from  
            <a href="https://home.iitd.ac.in/" style="color: #007A87; text-decoration: none;">IIT Delhi</a>, where I worked with  
            <a href="https://sites.google.com/site/dhimanmallick/home" style="color: #007A87; text-decoration: none;">Prof. Dhiman Mallick</a> in the 
            <a href="https://iec.iitd.ernet.in/" style="color: #007A87; text-decoration: none;">Integrated Electronics and Circuits group</a>. My doctoral research centered on magnetoelectric-based spintronic and Lab-on-a-Chip devices, aiming to develop energy-efficient and multifunctional magnetoelectric device platforms for sensing and computing applications.  
        </p>

        <p>
            Currently, I am part of the  
            <a href="https://www.phy.cam.ac.uk/" style="color: #007A87; text-decoration: none;">Cavendish Laboratory</a> at the <a href="https://www.cam.ac.uk/" style="color: #007A87; text-decoration: none;">University of Cambridge</a>, working in the <a href="https://www.me.phy.cam.ac.uk/" style="color: #007A87; text-decoration: none;">Microelectronics group</a> with  
            <a href="https://www.ciccarelli.phy.cam.ac.uk/" style="color: #007A87; text-decoration: none;">Prof. Chiara Ciccarelli</a>. At Cambridge, my work focuses on superconducting spintronics, exploring the interplay between superconductivity and magnetism to advance ultra-low-power computing devices.
        </p>
    </div>

    <!-- Logos Section -->
    <div class="logo-container">
        <div class="logo-column">
            <a href="https://www.cam.ac.uk/" target="_blank">
                <img src="/images/l1.jpg" alt="Logo 1" style="width: 320px;">
            </a>
            <a href="https://home.iitd.ac.in/" target="_blank">
                <img src="/images/i1.png" alt="Logo 3" style="width: 370px;">
            </a>
        </div>

        <div class="logo-column">
            <img src="/images/c1 (1).jpg" alt="Logo C1" style="width: 150px;">
            <a href="https://www.phy.cam.ac.uk/" target="_blank">
                <img src="/images/l2.jpeg" alt="Logo 2" style="width: 290px;">
            </a>
        </div>
    </div>

    <!-- Vanta.js Background Script -->
    <script>
        VANTA.DOTS({
            el: "#vanta-bg",
            color: 0x007A87, // Custom dot color
            backgroundColor: 0xffffff, // Background color
            spacing: 20.0, // Adjust dot spacing
            showLines: true, // Connect dots with lines
            size: 3.0 // Dot size
        });
    </script>

</body>
</html>
