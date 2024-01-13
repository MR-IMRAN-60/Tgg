<html lang="en">
<head>
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-8736240299050572"
            crossorigin="anonymous"></script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="https://i.imgur.com/T78fhJk.jpeg" type="image/x-icon" />
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
    <title>PHOENIX-MD QR</title>
    <style>
        .bg {
            width: 100%;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background-size: 400% 400%;
            animation: AnimateBG 25s ease infinite;
        }

        @keyframes AnimateBG {
            0% {
                background-position: 0% 50%
            }
            50% {
                background-position: 100% 50%
            }
            100% {
                background-position: 0% 50%
            }
        }

        body {
            margin: 0;
            padding: 0;
            font-family: "Outfit";
            background: linear-gradient(-45deg, #0032f9, #ff0000, #3f10e8, #00ffc3);
            background-size: 400% 400%;
            animation: gradient 10s ease infinite;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        @keyframes gradient {
            0% {
                background-position: 0% 50%;
            }
            50% {
                background-position: 100% 50%;
            }
            100% {
                background-position: 0% 50%;
            }

        }

        jsl.code {
            overflow: hidden;
            background: linear-gradient(-45deg, #ff023d, #0051ff, #ff0000, #0059ff, hsl(250, 100%, 50%), #ff0000);
            background-size: 400% 400%;
            animation: gradient 8s ease infinite;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            font-family: 'Montserrat', sans-serif;
            height: 110vh;
            margin: 0px;

        }

        p.legend {
            color: hsl(220, 15%, 55%);
            font-size: 1em;
            font-weight: 400;
            padding: 0em 1.1em;
            margin-top: 0.1em;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            overflow: hidden;
        }

        :root {
            --main-color: hsl(212, 45%, 89%);
            --principalText-color: hsl(218, 44%, 22%);
            --secondText-color: hsl(220, 15%, 55%);
        }

        #content {
            display: flex;
            flex-direction: column;
            width: 22rem;
            text-align: center;
            background-color: #000000;
            padding: 1rem;
            border-radius: 14px;
        }

        #QR-content {
            text-align: center;
            position: relative;
        }

        #logo {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 1;
        }

        #logo img {
            width: 60px; /* Adjust the width of the logo as needed */
            height: auto; /* Maintain aspect ratio */
        }

        #qr-image {
            border-radius: 10px;
            width: 20rem;
            z-index: 0;
        }

        #title-container {
            padding: 1rem 1rem 0 1rem;
            color: #fff;
            font-weight: 700;
            margin-bottom: 1rem;
        }

        #description-container {
            padding: 0 2.5rem 0 2.5rem;
            color: #fff;
            margin-bottom: 2rem;
        }

        #p-legend {
            color: hsl(220, 15%, 55%);
            font-size: 1em;
            font-weight: 400;
            padding: 0em 1.1em;
            margin-top: 0.1em;
        }
    </style>
    <script>
        var timeleft = 30;
        var downloadTimer = setInterval(function () {
            if (timeleft <= 0) {
                clearInterval(downloadTimer);
                document.getElementById("progressBar").remove()
                document.getElementById("main").innerHTML = "QR Expired! Please reload"
                document.getElementById("legend").innerHTML = ""
            }
            document.getElementById("progressBar").value = 30 - timeleft;
            timeleft -= 1;
        }, 1000);
    </script>
</head>
<body>
<div class="bg">
    <div id="content">
        <div id="QR-content">
            <div id="logo">
                
            </div>
            <img id="qr-image" src="../session" alt=PHOENIX-MD QR CODE">
        </div>
        <div id="title-container">
            <h2 id="main">PHOENIX-MD QR</h2>
            <br>
            <p class="legend" id="legend">refresh this page to get QR code</p>
        </div>
        <div id="description-container">
        </div>
    </div>
</div>
</body>
</html>
