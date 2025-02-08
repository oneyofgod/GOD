<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About God</title>
    <style>
        /* General styling */
        body {
            background-color: black;
            color: white;
            font-family: 'Courier New', Courier, monospace;
            margin: 0;
            padding: 0;
            text-align: center;
            overflow-x: hidden;
        }

        h1 {
            font-family: 'Caveat', cursive;
            font-size: 4em;
            color: white;
            margin-top: 50px;
            animation: fadeIn 2s ease-in-out;
        }

        /* Styling for the content section */
        .content {
            margin-top: 30px;
            animation: fadeInUp 3s ease-out;
        }

        .video-container {
            margin-top: 40px;
            animation: fadeInUp 3s ease-out;
        }

        iframe {
            width: 80%;
            height: 500px;
            border: none;
            border-radius: 10px;
        }

        p {
            font-size: 1.2em;
            margin-top: 20px;
            line-height: 1.8;
            animation: fadeInUp 4s ease-out;
        }

        .verse {
            font-size: 1.4em;
            margin-top: 20px;
            font-style: italic;
            animation: fadeInUp 4s ease-out;
        }

        /* Animations */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateX(-100%);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        /* Animation for background music */
        .audio-container {
            display: none;
        }

        /* Google Fonts */
        @import url('https://fonts.googleapis.com/css2?family=Caveat&display=swap');
    </style>
</head>
<body>
    <!-- Background Music -->
    <div class="audio-container">
        <audio autoplay loop>
            <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mp3">
            Your browser does not support the audio element.
        </audio>
    </div>

    <!-- Main Title -->
    <h1>About God</h1>

    <!-- Main Content -->
    <div class="content">
        <p>God is the Creator of all that exists. He is our Father, our Guide, and the source of all love and wisdom. He is eternal, unchanging, and always present.</p>

        <div class="verse">
            <p>"In the beginning, God created the heavens and the earth." - Genesis 1:1</p>
        </div>

        <p>Through His power, God formed the universe, shaping every star, planet, and living being. His love encompasses all of creation, and He calls us to live according to His will, with kindness, compassion, and justice.</p>

        <div class="verse">
            <p>"For God so loved the world that He gave His only Son, that whoever believes in Him should not perish but have eternal life." - John 3:16</p>
        </div>

        <p>God's love is unconditional. He gives us His grace even when we fall short. His forgiveness and mercy are beyond measure, and He wants all to come to know Him through faith, hope, and love.</p>

        <div class="verse">
            <p>"The Lord is my shepherd; I shall not want. He makes me lie down in green pastures. He leads me beside still waters." - Psalm 23:1-2</p>
        </div>

        <p>We find peace in God's presence, for He is our shepherd, guiding us through life's trials and triumphs. He offers us rest and restoration when we feel weary.</p>

        <p>Let us take a moment to reflect on God's greatness and beauty through LeeLand's creation:</p>
    </div>

    <!-- Embedded Video -->
    <div class="video-container">
        <iframe src="https://www.youtube.com/embed/iJCV_2H9xD0" title="About God Video" allowfullscreen></iframe>
    </div>
    
    <p>May we always remember the love and grace of our Creator. Let His light guide our path and bring us closer to His truth.</p>

    <script>
        // Scroll animations on page load
        const elements = document.querySelectorAll('.content, .verse, iframe');
        window.addEventListener('scroll', function() {
            elements.forEach(element => {
                if (element.getBoundingClientRect().top < window.innerHeight) {
                    element.style.animation = 'fadeInUp 1s ease-out forwards';
                }
            });
        });
    </script>
</body>
</html>
