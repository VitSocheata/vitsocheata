<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Socheata's Portfolio</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
            background-color: #fefefe;
        }
        h1 {
            color: #ff7f50;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 15px;
        }
        .skill-card {
            flex: 0 0 100px;
            text-align: center;
            padding: 15px;
            border-radius: 10px;
            background-color: #f0f0f0;
            transition: transform 0.2s, background-color 0.2s;
            cursor: pointer;
        }
        .skill-card:hover {
            transform: translateY(-5px);
            background-color: #ffe5d4;
        }
        .skill-card i {
            font-size: 2rem;
            margin-bottom: 10px;
            color: #ff7f50;
        }
        .skill-card span {
            display: block;
            margin-top: 5px;
            font-weight: bold;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <div class="container text-center">
        <h1>🐣 I'm Socheata</h1>
        <p>💡 Beginner Web Developer | 🌱 Just getting started</p>

        <h3>🧠 About Me</h3>
        <p>🔁 I'm restarting my web development journey — and I'm excited to learn new skills!</p>

        <h3>💻 Skills & Frameworks</h3>
        <div class="skills justify-content-center">
            <div class="skill-card">
                <i class="fab fa-html5"></i>
                <span>HTML</span>
            </div>
            <div class="skill-card">
                <i class="fab fa-css3-alt"></i>
                <span>CSS</span>
            </div>
            <div class="skill-card">
                <i class="fab fa-bootstrap"></i>
                <span>Bootstrap</span>
            </div>
            <div class="skill-card">
                <i class="fab fa-js-square"></i>
                <span>JavaScript</span>
            </div>
            <div class="skill-card">
                <i class="fab fa-vuejs"></i>
                <span>Vue.js</span>
            </div>
            <div class="skill-card">
                <i class="fas fa-pencil-ruler"></i>
                <span>UX/UI</span>
            </div>
        </div>
    </div>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


