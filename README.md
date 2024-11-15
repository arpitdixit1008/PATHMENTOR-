<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PathMentor</title>
    <!-- Link to Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <!-- Link to Google Fonts for Enhanced Typography -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
            color: #333;
        }
        .header, .footer {
            background: #007BFF;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        .nav {
            display: flex;
            justify-content: center;
            background: #333;
            padding: 0.5em 0;
        }
        .nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        .nav a:hover {
            background: #575757;
        }
        .container {
            padding: 20px;
            max-width: 1000px;
            margin: auto;
            background: white;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            margin-top: 20px;
            border-radius: 10px;
        }
        .section {
            margin-bottom: 20px;
        }
        .section h2 {
            color: #007BFF;
            font-weight: 500;
        }
        .section p {
            margin: 10px 0;
        }
        .services ul {
            list-style: none;
            padding: 0;
        }
        .services li {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }
        .services i {
            margin-right: 10px;
            color: #007BFF;
        }
        .testimonials, .faq {
            background: #e0e0e0;
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
        }
        .footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>PathMentor</h1>
        <p>Empowering Futures Together</p>
    </div>

    <div class="nav">
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#careers">Careers</a>
        <a href="#faq">FAQ</a>
        <a href="#contact">Contact Us</a>
    </div>

    <div id="home" class="container">
        <div class="section">
            <h2>Welcome to PathMentor</h2>
            <p>Welcome to PathMentor, your partner in academic and career success. We are dedicated to empowering students, parents, and professionals with personalized mentoring and comprehensive resources. Our mission is to provide the support and guidance you need to achieve your goals and reach your full potential.</p>
        </div>
    </div>

    <div id="about" class="container">
        <div class="section">
            <h2>About Us</h2>
            <p>At PathMentor, we believe in the transformative power of mentorship. Our team of experienced mentors offers one-on-one guidance tailored to your unique needs and aspirations. Whether you’re a student striving for academic excellence, a parent seeking to support your child’s educational journey, or a professional aiming to advance in your career, PathMentor is here to help you every step of the way.</p>
        </div>
    </div>

    <div id="services" class="container services">
        <div class="section">
            <h2>Our Services</h2>
            <ul>
                <li><i class="fas fa-chalkboard-teacher"></i><strong>Personalized Mentoring:</strong> Receive individualized support from our dedicated mentors.</li>
                <li><i class="fas fa-users"></i><strong>Workshops and Webinars:</strong> Join interactive sessions on a variety of topics.</li>
                <li><i class="fas fa-child"></i><strong>Parent Coaching:</strong> Empower yourself with practical advice and strategies.</li>
                <li><i class="fas fa-briefcase"></i><strong>Career Assessment and Planning:</strong> Discover your strengths and interests.</li>
                <li><i class="fas fa-book"></i><strong>Educational Resources:</strong> Access study tips, exam strategies, and guidance.</li>
                <li><i class="fas fa-comments"></i><strong>Community Forum:</strong> Connect with others and share experiences.</li>
            </ul>
        </div>
    </div>

    <div id="testimonials" class="container testimonials">
        <div class="section">
            <h2>Testimonials</h2>
            <p>"PathMentor helped me achieve my academic goals and set a clear path for my future. The personalized mentoring made all the difference." - Student</p>
            <p>"As a parent, I found the guidance and support from PathMentor invaluable. Their services have been a game-changer for my child's education." - Parent</p>
        </div>
    </div>

    <div id="careers" class="container">
        <div class="section">
            <h2>Careers</h2>
            <p>Join the PathMentor family and be part of a team dedicated to empowering individuals through mentorship. We offer a variety of roles including:</p>
            <ul>
                <li><i class="fas fa-user-tie"></i><strong>Mentors:</strong> Provide personalized guidance and support.</li>
                <li><i class="fas fa-people-carry"></i><strong>HR Professionals:</strong> Manage recruitment, training, and employee relations.</li>
                <li><i class="fas fa-code"></i><strong>Software Engineers:</strong> Develop and maintain our digital platform.</li>
                <li><i class="fas fa-bullhorn"></i><strong>Marketing Specialists:</strong> Promote our services and build our brand.</li>
                <li><i class="fas fa-headset"></i><strong>Customer Support:</strong> Assist clients and ensure a positive experience.</li>
            </ul>
        </div>
    </div>

    <div id="faq" class="container faq">
        <div class="section">
            <h2>FAQ</h2>
            <h3>What is PathMentor?</h3>
            <p>PathMentor is a platform that offers personalized mentoring and comprehensive resources to help individuals achieve their academic, career, and personal goals.</p>
            <h3>How can I join PathMentor?</h3>
            <p>You can join PathMentor by visiting our website and signing up for our services. If you have any questions, feel free to contact us for more information.</p>
        </div>
    </div>

    <div id="contact" class="container">
        <div class="section">
            <h2>Contact Us</h2>
            <p>Ready to learn more? Contact us today to get started on your journey with PathMentor. Our team is here to answer your questions and provide the guidance you need to succeed.</p>
            <p>Email: info@pathmentor.com</p>
            <p>Phone: (123) 456-7890</p>
        </div>
    </div>

    <div class="footer">
        <p>&copy; 2024 PathMentor. All rights reserved.</p>
    </div>
</body>
</html>
