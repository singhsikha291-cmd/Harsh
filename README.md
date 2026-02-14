<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Harsh Singh | Profile</title>

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
        }

        header {
            background: rgba(0, 0, 0, 0.3);
            padding: 25px;
            text-align: center;
        }

        header h1 {
            font-size: 40px;
            margin: 0;
        }

        header p {
            font-size: 18px;
        }

        .container {
            max-width: 1000px;
            margin: auto;
            padding: 20px;
        }

        .card {
            background: rgba(255, 255, 255, 0.15);
            border-radius: 15px;
            padding: 25px;
            margin: 20px 0;
            box-shadow: 0 0 15px rgba(0,0,0,0.3);
            transition: transform 0.3s;
        }

        .card:hover {
            transform: scale(1.03);
        }

        h2 {
            color: #ffdd59;
            border-bottom: 2px solid white;
            padding-bottom: 5px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            background: rgba(0,0,0,0.3);
            padding: 10px;
            margin: 8px 0;
            border-radius: 8px;
        }

        .skills span {
            display: inline-block;
            background: #ff9f1a;
            color: black;
            padding: 8px 15px;
            margin: 6px;
            border-radius: 20px;
            font-weight: 500;
        }

        footer {
            text-align: center;
            background: rgba(0,0,0,0.4);
            padding: 15px;
            margin-top: 30px;
            font-size: 14px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Harsh Singh</h1>
        <p>SKJI Computer Coaching Institute</p>
    </header>

    <div class="container">

        <!-- About Section -->
        <div class="card">
            <h2>Personal Information</h2>
            <ul>
                <li><strong>Name:</strong> Harsh Singh</li>
                <li><strong>Institute:</strong> SKJI Computer Coaching Institute</li>
                <li><strong>Course:</strong> DDCTT</li>
                <li><strong>Subject:</strong> English</li>
            </ul>
        </div>

        <!-- Language Section -->
        <div class="card">
            <h2>Language Skills</h2>
            <ul>
                <li><strong>Narrative:</strong> English</li>
                <li><strong>Advance:</strong> Hindi</li>
            </ul>
        </div>

        <!-- Skills Section -->
        <div class="card">
            <h2>My Skills</h2>
            <div class="skills">
                <span>Computer</span>
                <span>Karate</span>
                <span>Dance</span>
                <span>Drone Assembly</span>
            </div>
        </div>

        <!-- About Section -->
        <div class="card">
            <h2>About Me</h2>
            <p>
                I am Harsh Singh, a student of SKJI Computer Coaching Institute. 
                Currently, I am pursuing DDCTT course. I am interested in technology, 
                physical fitness, and creative activities. I always try to improve 
                my skills and knowledge.
            </p>
        </div>

    </div>

    <footer>
        © 2026 | Designed by Harsh Singh | All Rights Reserved
    </footer>

</body>
</html>
