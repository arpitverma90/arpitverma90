<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile Header</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 1200px;
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
        }

        .header {
            position: relative;
            overflow: hidden;
            padding: 60px 40px;
            text-align: center;
            min-height: 400px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        .animated-bg {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                radial-gradient(circle at 20% 50%, rgba(102, 126, 234, 0.4) 0%, transparent 50%),
                radial-gradient(circle at 80% 80%, rgba(118, 75, 162, 0.4) 0%, transparent 50%);
            animation: gradientShift 6s ease infinite;
        }

        @keyframes gradientShift {
            0%, 100% {
                background: 
                    radial-gradient(circle at 20% 50%, rgba(102, 126, 234, 0.4) 0%, transparent 50%),
                    radial-gradient(circle at 80% 80%, rgba(118, 75, 162, 0.4) 0%, transparent 50%);
            }
            50% {
                background: 
                    radial-gradient(circle at 80% 20%, rgba(102, 126, 234, 0.4) 0%, transparent 50%),
                    radial-gradient(circle at 20% 80%, rgba(118, 75, 162, 0.4) 0%, transparent 50%);
            }
        }

        .floating-shapes {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
        }

        .shape {
            position: absolute;
            opacity: 0.1;
        }

        .circle {
            border-radius: 50%;
        }

        .circle1 {
            width: 300px;
            height: 300px;
            background: white;
            top: -100px;
            left: -100px;
            animation: float 8s ease-in-out infinite;
        }

        .circle2 {
            width: 200px;
            height: 200px;
            background: white;
            bottom: -50px;
            right: -50px;
            animation: float 10s ease-in-out infinite reverse;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(20px); }
        }

        .content {
            position: relative;
            z-index: 2;
        }

        .greeting {
            font-size: 24px;
            color: #64b5f6;
            font-weight: 500;
            margin-bottom: 15px;
            animation: fadeInDown 0.8s ease;
        }

        h1 {
            font-size: 56px;
            font-weight: 800;
            color: white;
            margin-bottom: 20px;
            background: linear-gradient(135deg, #64b5f6, #81c784);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            animation: fadeInUp 0.8s ease;
        }

        .tagline {
            font-size: 24px;
            color: #b0bec5;
            margin-bottom: 40px;
            animation: fadeInUp 1s ease;
        }

        .cta-buttons {
            display: flex;
            gap: 15px;
            justify-content: center;
            flex-wrap: wrap;
            animation: fadeInUp 1.2s ease;
        }

        .btn {
            padding: 12px 30px;
            border: 2px solid white;
            background: transparent;
            color: white;
            border-radius: 25px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
        }

        .btn-primary {
            background: linear-gradient(135deg, #667eea, #764ba2);
            border-color: #667eea;
        }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(102, 126, 234, 0.4);
        }

        .btn-secondary {
            border-color: #64b5f6;
        }

        .btn-secondary:hover {
            background: rgba(100, 181, 246, 0.2);
            transform: translateY(-2px);
        }

        .stats {
            display: flex;
            gap: 40px;
            justify-content: center;
            margin-top: 50px;
            flex-wrap: wrap;
            animation: fadeInUp 1.4s ease;
        }

        .stat-item {
            text-align: center;
        }

        .stat-number {
            font-size: 32px;
            font-weight: 800;
            color: #64b5f6;
            margin-bottom: 5px;
        }

        .stat-label {
            font-size: 14px;
            color: #b0bec5;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
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

        @media (max-width: 768px) {
            h1 {
                font-size: 36px;
            }

            .tagline {
                font-size: 18px;
            }

            .stats {
                gap: 30px;
            }

            .header {
                padding: 40px 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="animated-bg"></div>
            <div class="floating-shapes">
                <div class="shape circle circle1"></div>
                <div class="shape circle circle2"></div>
            </div>
            
            <div class="content">
                <div class="greeting">👋 Welcome to my GitHub!</div>
                <h1>Your Name Here</h1>
                <p class="tagline">Full Stack Developer | Problem Solver | Tech Enthusiast</p>
                
                <div class="cta-buttons">
                    <button class="btn btn-primary">View My Projects</button>
                    <button class="btn btn-secondary">Contact Me</button>
                </div>

                <div class="stats">
                    <div class="stat-item">
                        <div class="stat-number">15+</div>
                        <div class="stat-label">Projects</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-number">50+</div>
                        <div class="stat-label">Repositories</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-number">200+</div>
                        <div class="stat-label">Contributions</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
