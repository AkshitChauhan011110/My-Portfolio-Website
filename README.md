# My-Portfolio-Website
Welcome to my personal portfolio website repository! This project serves as a digital showcase of my skills, projects, certifications, and academic journey in the fields of web development, machine learning, and software engineering.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Akshit Chauhan - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }

        header {
            background-color: #333;
            padding: 10px;
            text-align: left;
        }

        nav button {
            background-color: #008CBA;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
        }

        nav button:hover {
            background-color: #005f73;
        }

        .profile-container {
            display: flex;
            align-items: center;
            justify-content: flex-start;
            max-width: 80%;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .profile-img {
            flex-shrink: 0;
            margin-right: 20px;
        }

        .profile-img img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 3px solid #333;
        }

        .profile-info {
            text-align: left;
        }

        .profile-info h1 {
            margin: 10px 0;
            font-size: 24px;
        }

        .profile-info a {
            color: #0073e6;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        .profile-info a:hover {
            color: #ff6600;
            text-decoration: underline;
        }

        .Acedmics {
        max-width: 80%;
        margin: 50px auto;
        background: white;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        text-align: center;
    }

    .Acedmics h2 {
        text-align: center;
        font-size: 28px;
        margin-bottom: 20px;
    }

    table {
        width: 100%;
        border-collapse: collapse;
        margin-top: 20px;
    }

    table, th, td {
        border: 1px solid #ddd;
    }

    th, td {
        padding: 12px;
        text-align: center;
    }

    th {
        background-color: #333;
        color: white;
        font-weight: bold;
    }

    tr:nth-child(even) {
        background-color: #f2f2f2;
    }

    tr:hover {
        background-color: #ddd;
    }

    .Technical-Skill {
        max-width: 80%;
        margin: 50px auto;
        background: white;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .Technical-Skill h2 {
        text-align: center;
        font-size: 28px;
        margin-bottom: 20px;
    }

    .Technical-Skill ul {
        list-style-type: disc;
        padding-left: 20px;
        font-size: 18px;
        line-height: 1.6;
    }

    .Technical-Skill ul li {
        margin-bottom: 8px;
    }

        .Project {
            max-width: 80%;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Projects Heading */
        .Project h2 {
            text-align: center;
            font-size: 28px;
            margin-bottom: 20px;
        }

        .Project-content {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .Project-content > div {
            flex: 1;
            min-width: 250px;
            margin: 10px;
            background: rgb(243, 240, 240);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        @media (max-width: 768px) {
            .profile-container {
                flex-direction: column;
                text-align: center;
                align-items: center;
            }
            
            .profile-img {
                margin: 0 0 15px 0;
            }

            .profile-info {
                text-align: center;
            }

            .Project-content {
                flex-direction: column;
            }
        }
        .Certification {
            max-width: 80%;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
    
        .Certification h2 {
            text-align: center;
            font-size: 28px;
            margin-bottom: 20px;
        }

        .Certification div {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
    
        .Certification img {
            width: 150px;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
    
        .Certification img:hover {
            transform: scale(1.1);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
        }
    
        /* Responsive Design */
        @media (max-width: 600px) {
            .Certification img {
                width: 120px;
            }
        }

    </style>
</head>
<body>

    <header>
        <nav>
            <button>Menu</button> 
        </nav>
    </header>

    <div class="profile-container">
        
        <div class="profile-img">
            <img src="pinkpanthor.png" alt="Akshit's Profile Picture">
        </div>

        <div class="profile-info">
            <h1>Akshit Chauhan</h1>
            <p>
                <a href="https://www.linkedin.com/in/akshit-chauhan-238052288" >LinkedIn</a> - 
                <a href="https://www.instagram.com/_.akshit_chauhan._/" >Instagram</a>-
                <a href="https://github.com/AkshitChauhan011110/Akshit-Chauhan">GitHub</a>
                <h3>akshitchauhan344@gmail.com</h3>
                
            </p>
        </div>

        
    </div>

    <div class="Acedmics">
        <h2>Education</h2> 
        <table>
            <tr>
                <td>
                    Degree
                </td>
                <td>
                    Institute
                </td>
                <td>
                    Year
                </td>
                <td>
                    Result
                </td>
            </tr>
            <tr>
                <td>
                    B.Tech (CSE)
                </td>
                <td>
                    Graphic Era Hill University
                </td>
                <td>
                    2022-2026
                </td>
                <td>
                    7.7475 / 10
                </td>
            </tr>
            <tr>
                <td>
                    XII
                </td>
                <td>
                    Baluni Public School
                </td>
                <td>
                    2021
                </td>
                <td>
                    77.8%
                </td>
            </tr>
            <tr>
                <td>
                    X
                </td>
                <td>
                    Doon's Pride Public School
                </td>
                <td>
                    2019
                </td>
                <td>
                    78.16%
                </td>
            </tr>
        </table>
    </div>

    <div class="Technical-Skill">
        <h2>Technical Skills</h2>
        <ul>
            <li><strong>Programming Languages:</strong> C, C++, Java, Python, JavaScript, SQL</li>
            <li><strong>Web Development:</strong> HTML, CSS, JavaScript</li>
            <li><strong>Tools & Libraries:</strong> Visual Studio Code, GitHub, Code Blocks, Pandas, NumPy, TensorFlow.js, Web Speech API</li>
            <li><strong>Operating Systems:</strong> Linux, Windows</li>
            <li><strong>Frameworks/Other:</strong> Java Swing, File Handling, Object Detection</li>
        </ul>
    </div>

    <div class="Project">
        <h2>Projects</h2> 
        <div class="Project-content">
            <div>
                <h3>Dynamic Web Application for University</h3>
                <p>Built a web application for Graphic Era Hill University, focusing on enhancing user experience with features
                    such as image display and dropdown menus.</p>
            </div>
            <div>
                <h3>Object Detection and Voice Feedback System</h3>
                <p>Designed and developed a real-time object detection system using TensorFlow.js and integrated a voice feedback
                    system through the Web Speech API.</p>
            </div>
            <div>
                <h3>Course Recommendation System</h3>
                <p>Designed and implemented a machine learning model using RandomForestClassifier to recommend courses
                    based on high school marks, subjects, and hobbies.</p>
            </div>
        </div>
    </div>

    <div class="Certification">
    <h2>Certifications</h2>
    <div>
        <a href="https://unstop.com/certificate-preview/c75d159a-7948-4534-8073-40542a4b472c" target="_blank">
            <img src="amazon.jpg" alt="Amazon Certificate">
        </a>
        <a href="https://unstop.com/certificate-preview/c8d7a9af-0ba7-478d-a919-107ddc4beba0" target="_blank">
            <img src="flipcart.jpg" alt="Flipkart Certificate">
        </a>
        <a href="https://unstop.com/certificate-preview/9b13bc83-430f-4536-9232-696c10b6dd6d" target="_blank">
            <img src="hp.jpg" alt="HP Certificate">
        </a>
        <a href="https://unstop.com/certificate-preview/abc33d2c-1009-415d-978c-7e1f9f881858" target="_blank">
            <img src="tata1.jpg" alt="TATA Certificate 1">
        </a>
        <a href="https://unstop.com/certificate-preview/3087a1b2-cda1-4a21-9e0e-cb07e7c44d23" target="_blank">
            <img src="tata2.jpg" alt="TATA Certificate 2">
        </a>
        <a href="https://d8it4huxumps7.cloudfront.net/lambda-pdfs/certificate-images/9537658d-1636-49b1-be32-67f4fbc4fc21.jpg" target="_blank">
            <img src="tvs.jpg" alt="TVS Certificate">
        </a>
    </div>
</div>

</body>
</html>
