<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sophiedoni Foundation</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Reset & Fonts */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Montserrat', sans-serif; background: #fdf6f5; color: #333; }

        /* Header */
        header {
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://images.unsplash.com/photo-1598369772086-fb7c3d47c206?auto=format&fit=crop&w=1650&q=80') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 120px 20px 80px;
        }
        header h1 { font-size: 3em; margin-bottom: 20px; }
        header p { font-size: 1.3em; max-width: 700px; margin: 0 auto 30px; }

        /* Buttons */
        .btn {
            background-color: #ff4c4c;
            color: white;
            padding: 15px 40px;
            font-size: 1.2em;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: 0.3s;
            text-decoration: none;
        }
        .btn:hover { background-color: #e04343; }

        /* Navigation */
        nav { background: #ff6666; text-align: center; padding: 12px 0; }
        nav a { color: white; text-decoration: none; margin: 0 20px; font-weight: 600; transition: 0.3s; }
        nav a:hover { text-decoration: underline; }

        /* Sections */
        section { padding: 80px 20px; text-align: center; }
        section h2 { font-size: 2.2em; margin-bottom: 20px; color: #ff4c4c; }
        section p { font-size: 1.1em; max-width: 700px; margin: 0 auto 40px; line-height: 1.6; }

        /* Donation Cards */
        .cards { display: flex; flex-wrap: wrap; justify-content: center; gap: 30px; margin-top: 40px; }
        .card {
            background: white;
            padding: 30px 20px;
            border-radius: 12px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
            width: 280px;
            transition: 0.3s;
        }
        .card:hover { transform: translateY(-5px); box-shadow: 0 12px 30px rgba(0,0,0,0.15); }
        .card h3 { color: #ff4c4c; margin-bottom: 15px; }
        .card p { font-size: 0.95em; color: #555; }

        /* Footer */
        footer { background: #ff4c4c; color: white; padding: 40px 20px; text-align: center; }
        footer a { color: white; margin: 0 10px; text-decoration: none; font-size: 1.2em; }
        footer a:hover { text-decoration: underline; }

        /* Responsive */
        @media (max-width: 900px) { .cards { flex-direction: column; align-items: center; } }
    </style>
</head>
<body>

    <header>
        <h1>Sophiedoni Foundation</h1>
        <p>Helping children in need with food, shelter, medical care, and education. Your contribution can change lives.</p>
        <a href="#donate" class="btn">Donate Now</a>
    </header>

    <nav>
        <a href="#about">About Us</a>
        <a href="#donate">Donate</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Us</h2>
        <p>The Sophiedoni Foundation is dedicated to improving the lives of children facing hardship. We provide essentials such as food, shelter, education, and medical support, making a tangible difference for those who need it most.</p>
        <div class="cards">
            <div class="card">
                <h3>Food & Nutrition</h3>
                <p>We ensure children have access to healthy meals and proper nutrition every day.</p>
            </div>
            <div class="card">
                <h3>Medical Care</h3>
                <p>Supporting children with medical treatment, medications, and regular check-ups.</p>
            </div>
            <div class="card">
                <h3>Education & Shelter</h3>
                <p>Providing safe housing and educational support to give children a brighter future.</p>
            </div>
        </div>
    </section>

    <section id="donate">
        <h2>Make a Donation</h2>
        <p>Your generosity helps us reach more children and provide essential support. Every donation counts and goes directly to those in need.</p>
        <a href="#" class="btn">Donate Now</a>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@sophiedoni.foundation</p>
        <p>Whatsapp: +1 (323) 801-8399</p>
        <p>Follow us: 
            <a href="#">Facebook</a> | 
            <a href="#">Instagram</a> | 
            <a href="#">Twitter</a>
        </p>
    </section>

    <footer>
        <p>&copy; 2025 Sophiedoni Foundation. All Rights Reserved.</p>
    </footer>

</body>
</html>
