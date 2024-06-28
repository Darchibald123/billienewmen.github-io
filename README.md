<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Billie Newman - Full Stack Developer</title>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@300;400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Oswald', sans-serif;
            line-height: 1.6;
            background-color: #e6f7ff;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #3399ff;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #0056b3 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        .showcase {
            min-height: 400px;
            background: url('background.jpg') no-repeat 0 -400px;
            text-align: center;
            color: #fff;
        }
        .showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        .showcase p {
            font-size: 20px;
        }
        .main {
            padding: 20px;
            background: #fff;
            color: #333;
        }
        .main h2 {
            color: #0056b3;
        }
        footer {
            background: #3399ff;
            color: #fff;
            text-align: center;
            padding: 30px;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>Billie Newman</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="showcase">
        <div class="container">
            <h1>Billie Newman - Full Stack Developer</h1>
            <p>Passionate Full Stack Developer with expertise in JavaScript, iOS development, and creative problem solving. </p>
        </div>
    </div>

    <div class="main container">
        <h2 id="projects">Project History</h2>

        <h3>E-Commerce Web Application</h3>
        <p><strong>Role:</strong> Full Stack Developer</p>
        <p><strong>Company:</strong> Zenith Solutions LLC</p>
        <p><strong>Duration:</strong> January 2021 - December 2021</p>
        <p><strong>Location:</strong> Remote</p>
        <p><strong>Description:</strong> Developed a comprehensive e-commerce web application using React.js, Node.js, and MongoDB. This application included user authentication, product management, shopping cart functionality, and payment gateway integration. Collaborated with designers to implement responsive design and optimized performance for a seamless user experience.</p>
        <p><strong>Responsibilities:</strong></p>
        <ul>
            <li>Designed and developed RESTful APIs for the backend.</li>
            <li>Implemented secure user authentication and authorization.</li>
            <li>Integrated third-party payment gateways (Stripe, PayPal).</li>
            <li>Ensured cross-browser compatibility and mobile responsiveness.</li>
            <li>Collaborated with the design team to create an intuitive user interface.</li>
        </ul>

        <h3>Inventory Management System</h3>
        <p><strong>Role:</strong> Backend Developer</p>
        <p><strong>Company:</strong> Apex Tech Solutions</p>
        <p><strong>Duration:</strong> June 2019 - December 2020</p>
        <p><strong>Location:</strong> Atlanta, GA</p>
        <p><strong>Description:</strong> Worked on developing an inventory management system for small to medium-sized businesses using Node.js and PostgreSQL. The system included features for tracking inventory levels, orders, sales, and deliveries, as well as generating detailed reports.</p>
        <p><strong>Responsibilities:</strong></p>
        <ul>
            <li>Developed and maintained server-side logic.</li>
            <li>Designed database schema and optimized queries.</li>
            <li>Implemented robust error handling and logging mechanisms.</li>
            <li>Integrated APIs for real-time data synchronization with third-party applications.</li>
            <li>Conducted unit and integration testing to ensure reliability and performance.</li>
        </ul>

        <h3>Mobile Application for Task Management</h3>
        <p><strong>Role:</strong> iOS Developer</p>
        <p><strong>Company:</strong> Innovatech</p>
        <p><strong>Duration:</strong> March 2018 - May 2019</p>
        <p><strong>Location:</strong> San Francisco, CA</p>
        <p><strong>Description:</strong> Developed a task management mobile application for iOS using Swift. The app allowed users to create, update, and manage tasks, set reminders, and synchronize data across multiple devices. Focused on providing a smooth user experience and efficient data handling.</p>
        <p><strong>Responsibilities:</strong></p>
        <ul>
            <li>Developed the application using Swift and Xcode.</li>
            <li>Integrated Core Data for local storage of tasks.</li>
            <li>Implemented push notifications for task reminders.</li>
            <li>Worked closely with UX/UI designers to ensure a user-friendly interface.</li>
            <li>Performed thorough testing and debugging to maintain app stability.</li>
        </ul>

        <h2 id="education">Education</h2>

        <h3>Georgia Tech School of Modern Languages</h3>
        <p><strong>Degree:</strong> Bachelor of Science in Computer Science</p>
        <p><strong>Field of Study:</strong> Computer Science</p>
        <p><strong>Location:</strong> Atlanta, GA</p>
        <p><strong>Graduation Year:</strong> 2023</p>

        <h2 id="certificates">Certificates</h2>

        <h3>Full Stack Web Development Certification</h3>
        <p><strong>Institution:</strong> FreeCodeCamp</p>
        <p><strong>Date:</strong> April 2022</p>

        <h3>iOS App Development Certification</h3>
        <p><strong>Institution:</strong> Udacity</p>
        <p><strong>Date:</strong> January 2021</p>

        <h2 id="contact">Contact</h2>
        <p>Email: Billienewman@gmail.com</p>
        <p>Phone: 323-498-8860</p>
        <p>Address: 146 Edison Dr, Stockbridge, GA 30281</p>
    </div>

    <footer>
        <p>Billie Newman &copy; 2024</p>
    </footer>
</body>
</html>
