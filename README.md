<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GenAI Music Album</title>
    <style>
        /* Basic Reset */
        body, h1, p, a { margin: 0; padding: 0; }
        
        /* Body & Background Styling */
        body { 
            font-family: 'Arial', sans-serif; 
            background-color: #282c34; 
            color: #FFF; 
            line-height: 1.6; 
            padding: 20px;
            text-align: center;
        }
        
        /* Container for Content */
        .container { 
            max-width: 800px; 
            margin: auto; 
            overflow: hidden; 
            padding: 20px; 
        }
        
        /* Styling for Video and Its Wrapper */
        .video-wrapper { 
            overflow: hidden; 
            padding-top: 56.25%; /* 16:9 Aspect Ratio */
            position: relative; 
        }
        video { 
            left: 0;
            top: 0;
            height: 100%; 
            position: absolute; 
            width: 100%; 
        }
        
        /* Typography & Button Styling */
        h1 { 
            font-size: 2.5rem; 
            margin-bottom: 20px;
        }
        p { 
            margin-bottom: 20px; 
        }
        .btn { 
            display: inline-block; 
            background-color: #007bff; 
            color: #ffffff; 
            padding: 10px 20px; 
            margin: 20px 0; 
            border-radius: 5px; 
            transition: background-color 0.3s ease;
        }
        .btn:hover { 
            background-color: #0056b3;
        }
        
        /* Animation */
        @keyframes fadeInUp {
            from {
                transform: translate3d(0, 40px, 0);
                opacity: 0;
            }
            to {
                transform: translate3d(0, 0, 0);
                opacity: 1;
            }
        }
        .fade-in-up {
            animation: fadeInUp 1.5s ease-out;
        }
    </style>
</head>
<body>
    <div class="container fade-in-up">
        <div class="video-wrapper">
            <video autoplay muted loop>
                <source src="intro-video.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
        <h1>GenAI Music Album</h1>
        <p>Welcome to the official page of the GenAI Music Album! Dive into the revolutionary sounds of AI-generated music, blending genres, emotions, and unheard melodies. Explore the unique compositions that challenge the boundaries of music creation.</p>
        <a href="content.html" class="btn">Explore Album Tracks</a>
    </div>

    <script>
        // You can add some JavaScript here for interactive elements or more complex animations if needed in the future
    </script>
</body>
</html>
