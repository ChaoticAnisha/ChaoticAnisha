# GitHub README with Night Sky Background

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anisha's GitHub Profile</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #0c0c2e 0%, #1a1a4a 50%, #0f0f36 100%);
            color: white;
            font-family: Arial, sans-serif;
            overflow-x: hidden;
            position: relative;
            min-height: 100vh;
        }

        .stars {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        .star {
            position: absolute;
            background: white;
            border-radius: 50%;
            animation: twinkle 2s infinite;
        }

        .star:nth-child(odd) {
            animation-duration: 3s;
        }

        .star:nth-child(3n) {
            animation-duration: 1.5s;
        }

        @keyframes twinkle {
            0%, 100% { opacity: 0.3; transform: scale(1); }
            50% { opacity: 1; transform: scale(1.2); }
        }

        .container {
            position: relative;
            z-index: 1;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .header {
            text-align: center;
            margin-bottom: 30px;
        }

        .title {
            font-size: 2.5rem;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
        }

        .wave {
            width: 30px;
            height: 30px;
        }

        .typing-animation {
            margin: 20px 0;
        }

        .computer-gif {
            width: 100%;
            max-width: 600px;
            margin: 20px 0;
        }

        .social-links {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
            margin: 30px 0;
        }

        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
            margin: 30px 0;
        }

        .stats-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
            margin: 30px 0;
        }

        .stats-container img {
            max-width: 100%;
            height: auto;
        }

        h1, h2 {
            text-align: center;
        }

        h2 {
            font-size: 1.8rem;
            margin: 40px 0 20px;
        }

        .trophy-container {
            text-align: center;
            margin: 30px 0;
        }

        .visit-counter {
            text-align: center;
            margin: 30px 0;
        }

        @media (max-width: 768px) {
            .title {
                font-size: 1.8rem;
                flex-direction: column;
            }
            
            .computer-gif {
                max-width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="stars"></div>
    
    <div class="container">
        <div class="header">
            <h1 class="title">
                Hey there! 
                <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/gifs/hi.gif" class="wave" alt="wave"/> 
                I'm Anisha
            </h1>
            
            <div class="typing-animation">
                <img src="https://readme-typing-svg.herokuapp.com?font=Time+New+Roman&color=cyan&size=25&center=true&vCenter=true&width=600&height=100&lines=BSc.+Hons+Computing+Student;Open+Source+Enthusiast;Web+Development+Ninja;Always+Learning+New+Things" alt="Typing SVG" />
            </div>
            
            <div>
                <img src="https://raw.githubusercontent.com/ChaoticAnisha/ChaoticAnisha/1a5476c42954b57a0ef7b33360e7534d614792e6/computer.gif" class="computer-gif" alt="Computer animation"/>
            </div>
        </div>

        <h2>Find me elsewhere</h2>
        <div class="social-links">
            <a href="https://bsky.app/profile/chaoswannabe.bsky.social">
                <img src="https://img.shields.io/badge/bluesky-0285FF?style=for-the-badge&logo=bluesky&logoColor=%23FFFFFF" alt="Bluesky"/>
            </a>
            <a href="https://discord.gg/https://discord.gg/aVHKKd3b">
                <img src="https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white" alt="Discord"/>
            </a>
            <a href="https://www.facebook.com/sah.sneha.0117/">
                <img src="https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white" alt="Facebook"/>
            </a>
            <a href="https://instagram.com/chaoswannabee">
                <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white" alt="Instagram"/>
            </a>
            <a href="https://www.linkedin.com/in/anisha-sah-a533b8282/">
                <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn"/>
            </a>
            <a href="https://pinterest.com/chaoswannabee">
                <img src="https://img.shields.io/badge/Pinterest-%23E60023.svg?logo=Pinterest&logoColor=white" alt="Pinterest"/>
            </a>
            <a href="https://reddit.com/user/https://www.reddit.com/user/Special_Avocado6698/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button">
                <img src="https://img.shields.io/badge/Reddit-%23FF4500.svg?logo=Reddit&logoColor=white" alt="Reddit"/>
            </a>
            <a href="mailto:anishashah0117@gmail.com">
                <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" alt="Email"/>
            </a>
        </div>

        <h2>Community Involvement</h2>
        <div class="tech-stack">
            <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
            <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
            <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript"/>
            <img src="https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin"/>
            <img src="https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white" alt="PHP"/>
            <img src="https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white" alt="Ruby"/>
            <img src="https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
            <img src="https://img.shields.io/badge/Apache%20Spark-FDEE21?style=for-the-badge&logo=apachespark&logoColor=black" alt="Apache Spark"/>
            <img src="https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white" alt="Django"/>
            <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" alt="Express.js"/>
            <img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white" alt="Flutter"/>
            <img src="https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next JS"/>
            <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="NodeJS"/>
            <img src="https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD" alt="Nodemon"/>
            <img src="https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white" alt="Qt"/>
            <img src="https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React Native"/>
            <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React"/>
            <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS"/>
            <img src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white" alt="Vite"/>
            <img src="https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white" alt="Yarn"/>
            <img src="https://img.shields.io/badge/WordPress-%23117AC9.svg?style=for-the-badge&logo=WordPress&logoColor=white" alt="WordPress"/>
            <img src="https://img.shields.io/badge/windicss-48B0F1.svg?style=for-the-badge&logo=windi-css&logoColor=white" alt="Windicss"/>
            <img src="https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white" alt="Apache"/>
            <img src="https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white" alt="Apache Maven"/>
            <img src="https://img.shields.io/badge/Apache%20Ant-A81C7D?style=for-the-badge&logo=Apache%20Ant&logoColor=white" alt="Apache Ant"/>
            <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
            <img src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
            <img src="https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34" alt="Firebase"/>
            <img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white" alt="MicrosoftSQLServer"/>
            <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="Postgres"/>
            <img src="https://img.shields.io/badge/blender-%23F5792A.svg?style=for-the-badge&logo=blender&logoColor=white" alt="Blender"/>
            <img src="https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white" alt="Canva"/>
            <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white" alt="Figma"/>
            <img src="https://img.shields.io/badge/invision-FF3366?style=for-the-badge&logo=invision&logoColor=white" alt="Invision"/>
            <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
            <img src="https://img.shields.io/badge/subversion-%23809CC9.svg?style=for-the-badge&logo=subversion&logoColor=white" alt="Apache Subversion"/>
            <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
            <img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
            <img src="https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab"/>
            <img src="https://img.shields.io/badge/Trello-%23026AA7.svg?style=for-the-badge&logo=Trello&logoColor=white" alt="Trello"/>
            <img src="https://img.shields.io/badge/nVIDIA-%2376B900.svg?style=for-the-badge&logo=nVIDIA&logoColor=white" alt="nVIDIA"/>
            <img src="https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white" alt="Unreal Engine"/>
            <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
        </div>

        <h2>GitHub Stats</h2>
        <div class="stats-container">
            <img src="https://github-readme-stats.vercel.app/api?username=ChaoticAnisha&theme=dark&hide_border=false&include_all_commits=false&count_private=false" alt="GitHub Stats"/>
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=ChaoticAnisha&theme=dark&hide_border=false" alt="GitHub Streak"/>
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ChaoticAnisha&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact" alt="Top Languages"/>
        </div>

        <h2>GitHub Trophies</h2>
        <div class="trophy-container">
            <img src="https://github-profile-trophy.vercel.app/?username=ChaoticAnisha&theme=bear&no-frame=false&no-bg=true&margin-w=4" alt="GitHub Trophies"/>
        </div>

        <hr style="border: 1px solid #444; margin: 40px 0;">
        
        <div class="visit-counter">
            <a href="https://visitcount.itsvg.in">
                <img src="https://visitcount.itsvg.in/api?id=ChaoticAnisha&icon=0&color=7" alt="Visit Counter"/>
            </a>
        </div>
    </div>

    <script>
        // Create twinkling stars
        function createStars() {
            const starsContainer = document.querySelector('.stars');
            const numberOfStars = 150;

            for (let i = 0; i < numberOfStars; i++) {
                const star = document.createElement('div');
                star.className = 'star';
                
                // Random position
                star.style.left = Math.random() * 100 + '%';
                star.style.top = Math.random() * 100 + '%';
                
                // Random size
                const size = Math.random() * 3 + 1;
                star.style.width = size + 'px';
                star.style.height = size + 'px';
                
                // Random animation delay
                star.style.animationDelay = Math.random() * 3 + 's';
                
                starsContainer.appendChild(star);
            }
        }

        // Initialize stars when page loads
        document.addEventListener('DOMContentLoaded', createStars);
    </script>
</body>
</html>
```

## Updated Markdown for GitHub README

```markdown
<h1 align="center">
  Hey there! <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/gifs/hi.gif" width="30px"/> I'm Anisha
</h1>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Time+New+Roman&color=cyan&size=25&center=true&vCenter=true&width=600&height=100&lines=BSc.+Hons+Computing+Student;Open+Source+Enthusiast;Web+Development+Ninja;Always+Learning+New+Things" />
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/ChaoticAnisha/ChaoticAnisha/1a5476c42954b57a0ef7b33360e7534d614792e6/computer.gif" width="600"/>
</div>

## Find me elsewhere
[![Bluesky](https://img.shields.io/badge/bluesky-0285FF?style=for-the-badge&logo=bluesky&logoColor=%23FFFFFF)](https://bsky.app/profile/chaoswannabe.bsky.social) [![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/https://discord.gg/aVHKKd3b) [![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://www.facebook.com/sah.sneha.0117/) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/chaoswannabee) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anisha-sah-a533b8282/) [![Pinterest](https://img.shields.io/badge/Pinterest-%23E60023.svg?logo=Pinterest&logoColor=white)](https://pinterest.com/chaoswannabee) [![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?logo=Reddit&logoColor=white)](https://reddit.com/user/https://www.reddit.com/user/Special_Avocado6698/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:anishashah0117@gmail.com) 

# Community Involvement
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Ruby](https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=for-the-badge&logo=apachespark&logoColor=black) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD) ![Qt](https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white) ![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![Yarn](https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white) ![WordPress](https://img.shields.io/badge/WordPress-%23117AC9.svg?style=for-the-badge&logo=WordPress&logoColor=white) ![Windicss](https://img.shields.io/badge/windicss-48B0F1.svg?style=for-the-badge&logo=windi-css&logoColor=white) ![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white) ![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white) ![Apache Ant](https://img.shields.io/badge/Apache%20Ant-A81C7D?style=for-the-badge&logo=Apache%20Ant&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34) ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Blender](https://img.shields.io/badge/blender-%23F5792A.svg?style=for-the-badge&logo=blender&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Invision](https://img.shields.io/badge/invision-FF3366?style=for-the-badge&logo=invision&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Apache Subversion](https://img.shields.io/badge/subversion-%23809CC9.svg?style=for-the-badge&logo=subversion&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white) ![Trello](https://img.shields.io/badge/Trello-%23026AA7.svg?style=for-the-badge&logo=Trello&logoColor=white) ![nVIDIA](https://img.shields.io/badge/nVIDIA-%2376B900.svg?style=for-the-badge&logo=nVIDIA&logoColor=white) ![Unreal Engine](https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

# GitHub Stats
![](https://github-readme-stats.vercel.app/api?username=ChaoticAnisha&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=ChaoticAnisha&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=ChaoticAnisha&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

## GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=ChaoticAnisha&theme=bear&no-frame=false&no-bg=true&margin-w=4)

---
[![](https://visitcount.itsvg.in/api?id=ChaoticAnisha&icon=0&color=7)](https://visitcount.itsvg.in)
```
