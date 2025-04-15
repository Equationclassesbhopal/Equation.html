<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EQUATION classes</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0; padding: 0; box-sizing: border-box;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background: #f2f7ff;
            color: #333;
        }
        header {
            background: #4f95f0;
            padding: 20px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            color: white;
        }
        header h1 {
            font-size: 26px;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 600;
        }
        nav a:hover {
            color: #ffa500;
        }
        section {
            padding: 60px 20px;
        }
        .section-title {
            text-align: center;
            margin-bottom: 40px;
            font-size: 28px;
            color: #0c356a;
        }
        .content-box {
            max-width: 1000px;
            margin: 0 auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
        }
        footer {
            background: #0c356a;
            color: white;
            text-align: center;
            padding: 20px;
        }
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
                margin-top: 15px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Equation Classes</h1>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#admissions">Admissions</a></li>
                <li><a href="#faculty">Faculty</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2 class="section-title">About Us</h2>
        <div class="content-box">
            <p>Equation Classes is a premier coaching institute for students from Class 9 to Class 12. We provide dedicated and result-oriented coaching for IIT-JEE, NEET, NDA, and all State & CBSE Boards. Our mission is to build strong academic foundations, develop critical thinking, and foster competitive excellence among students.</p>
        </div>
    </section>

    <section id="admissions">
        <h2 class="section-title">Admissions</h2>
        <div class="content-box">
            <p>Admissions are open for the academic year 2025–2026. We offer:</p>
            <ul>
                <li>IIT-JEE (Main + Advanced)</li>
                <li>NEET (UG) Medical Coaching</li>
                <li>NDA Entrance Preparation</li>
                <li>Board Exam Preparation (Class 9–12)</li>
            </ul>
            <p>To apply, fill out Contact Us or Visit us!</p>
        </div>
    </section>

    <section id="faculty">
        <h2 class="section-title">Our Faculty</h2>
        <div class="content-box">
            <p>Our team includes experienced and passionate educators:</p>
            <ul>
                <li><strong>Mr. Manish. Tiwari</strong> – Physics (M.Sc Physics)</li>
                <li><strong>Dr. Noreen. Khan</strong> – Chemistry (PhD Chemistry)</li>
                <li><strong>Mr. Shubham. Dubey</strong> – Mathematics (B.Tech - NIT Raipur)</li>
                <li><strong>Mr. Saquib. Ali</strong> – Biology (M.Sc Biotechnology)</li>
            </ul>
        </div>
    </section>

    <section id="contact">
        <h2 class="section-title">Contact Us</h2>
        <div class="content-box">
            <p><strong>Phone:</strong> +91-9425687909, +91-7898520565</p>
            <p><strong>Email:</strong> equationclassesbhopal@gmail.com</p>
            <p><strong>Address:</strong> MIG-16, 2nd Floor, Seedlings School, Housing Board Coloney, Koh e Fiza Bhopal</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Equation Classes. All rights reserved.</p>
    </footer>

</body>
</html>
