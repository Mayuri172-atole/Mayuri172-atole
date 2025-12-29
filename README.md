<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mayuri's GitHub README Preview</title>
    <style>
        :root {
            color-scheme: light dark;
        }

        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            padding: 20px;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            line-height: 1.6;
            max-width: 1000px;
            margin: 0 auto;
        }

        /* Your GIF - Full width responsive */
        .hero-gif {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 15px;
            margin-bottom: 20px;
        }

        /* Auto-adjusting gradient card */
        .gradient-card {
            background: linear-gradient(135deg, #eab9fa 0%, #d946ef 33%, #a855f7 66%, #3b82f6 100%);
            padding: 35px;
            border-radius: 25px;
            margin: 20px 0;
            box-shadow: 10px 20px 50px rgba(234,185,250,0.4);
            text-align: center;
            isolation: isolate;
        }

        /* SVG Typing Animation - Auto visible */
        .typing-svg {
            filter: brightness(0) invert(1) drop-shadow(0 2px 4px rgba(0,0,0,0.3));
            max-width: 100%;
            height: auto;
        }

        /* Name & Bio - Auto contrast */
        .name {
            color: light-dark(#292524, #f5f5f4);
            font-size: 2em;
            font-weight: bold;
            margin: 20px 0 10px;
            text-align: center;
        }

        .bio {
            color: light-dark(#4b5563, #d1d5db);
            font-size: 1.1em;
            text-align: center;
            margin: 20px 0;
            max-width: 800px;
        }

        /* Social Badges Row */
        .socials {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
            margin: 30px 0;
        }

        /* Tech Stack Grid */
        .tech-stack {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin: 30px 0;
        }

        .tech-badge {
            padding: 8px 16px;
            border-radius: 25px;
            font-weight: 600;
            text-align: center;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.2);
        }

        /* Stats Cards */
        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 20px;
            margin: 40px 0;
        }

        .stats-card {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(20px);
            border-radius: 20px;
            padding: 20px;
            border: 1px solid rgba(255,255,255,0.2);
        }

        /* Dark mode override */
        body.dark {
            background: #0f0f23;
            color: #f5f5f4;
        }

        body.dark .gradient-card {
            background: linear-gradient(135deg, #4a1a5e 0%, #2d0b40 33%, #1a0f3d 66%, #0c1b3a 100%);
        }

        .toggle-btn {
            position: fixed;
            top: 20px;
            right: 20px;
            padding: 10px 20px;
            background: rgba(255,255,255,0.9);
            border: none;
            border-radius: 25px;
            cursor: pointer;
            font-weight: bold;
            z-index: 1000;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .socials { gap: 8px; }
            .tech-stack { grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); }
        }
    </style>
</head>
<body>
    <button class="toggle-btn" onclick="document.body.classList.toggle('dark')">🌙 Toggle Dark</button>

    <!-- Your GIF -->
    <img src="https://github.com/Mayuri172-atole/Mayuri172-atole/blob/main/Welcome-To-My-Profile-Image-DG123309.gif?raw=true" 
         alt="Welcome GIF" class="hero-gif">

    <!-- Auto-adjusting Typing SVG -->
    <div class="gradient-card">
        <div style="display: block;">
            <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=32&pause=1000&color=FFFFFF&center=true&vCenter=true&width=900&lines=Hi+there%21+%F0%9F%91%8B;I'm+Mayuri+Atole;Welcome+to+my+profile%21+%F0%9F%8C%90;" 
                 alt="Typing SVG" class="typing-svg" />
        </div>
    </div>

    <!-- Name & Bio -->
    <h1 class="name">Mayuri Atole</h1>
    
    <p class="bio">
        🔥 Data Analytics & Machine Learning enthusiast | MCA student specializing in Python, Power BI, Tableau, Machine Learning, Deep Learning, HTML, CSS | Seeking Data Analytics Intern roles to apply skills on real-world, data-driven projects
    </p>

    <!-- Socials -->
    <div class="socials">
        [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/__atole_myu_172)
        [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/mayuri-atole-9a4b25288)
        [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/@AtoleMayuri172)
        [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://youtube.com/@@Coding247)
        [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:atolemayuri17@gmail.com)
    </div>

    <!-- Tech Stack -->
    <h2 style="color: light-dark(#1f2937, #f9fafb); text-align: center;">💻 Tech Stack:</h2>
    <div class="tech-stack">
        ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
        ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
        ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
        ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
        ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
        ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
        <!-- Add more as needed -->
    </div>

    <!-- GitHub Stats (Placeholder - use your actual URLs) -->
    <div class="stats-container">
        <div class="stats-card">
            <img src="https://github-readme-stats.vercel.app/api?username=Mayuri172-atole&theme=dark&hide_border=false&include_all_commits=true&count_private=true" 
                 alt="GitHub Stats" style="width: 100%; border-radius: 15px;" />
        </div>
    </div>

    <!-- Visit Counter -->
    [![](https://visitcount.itsvg.in/api?id=Mayuri172-atole&icon=0&color=0)](https://visitcount.itsvg.in)

    <div style="text-align: center; margin-top: 40px; color: light-dark(#6b7280, #9ca3af); font-style: italic;">
        > # ❤️ Thank you for visiting!....
    </div>

    <script>
        if (window.matchMedia('(prefers-color-scheme: dark)').matches) {
            document.body.classList.add('dark');
        }
    </script>
</body>
</html>
