<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to STCAST</title>
    <style>
        /* General Body Styling */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('school-22.jpg'); /* Replace with your school image */
            background-size: cover;
            background-position: center;
            color: #fff;
        }

        /* Header Section Styling */
        header {
            background-color: rgba(0, 0, 0, 0.5); /* Dark transparent overlay */
            color: white;
            padding: 50px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        header p {
            margin: 10px 0;
            font-size: 1.5em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }

        /* Navigation Styling */
        nav {
            background-color: rgba(28, 32, 238, 0.51); /* Semi-transparent navbar */
            color: white;
            text-align: center;
            padding: 15px 0;
            position: sticky;
            top: 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            margin: 0 10px;
            display: inline-block;
        }
        nav a:hover {
            background-color: #0e1329;
            border-radius: 5px;
        }

        /* Main Content Area */
        .container {
            width: 80%;
            margin: 30px auto;
        }

        /* Section Styling */
        section {
            background-color: rgb(155, 191, 253); /* White background with transparency */
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }

        section h2 {
            color: #2d87f0;
            font-size: 2.5em;
            margin-bottom: 15px;
        }
        section p {
            font-size: 1.2em;
            line-height: 1.6;
            margin-bottom: 20px;
        }

        /* About Us Section */
        .about img {
            width: 100%;
            border-radius: 8px;
            margin-top: 20px;
        }

        /* School Activities Section */
        .activity-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }
        .activity-item img {
            width: 45%;
            border-radius: 8px;
        }
        .activity-info {
            width: 50%;
        }

        .activity-info h3 {
            font-size: 1.6em;
            color: #2d87f0;
        }
        .activity-info p {
            font-size: 1.1em;
            line-height: 1.6;
            color: #555;
        }

        /* Contact Form Styling */
        form input,
        form textarea {
            width: 100%;
            padding: 14px;
            margin-bottom: 20px;
            border-radius: 5px;
            border: 1px solid #ddd;
            font-size: 1.1em;
        }
        form input[type="submit"] {
            background-color: #2d87f0;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 1.2em;
        }
        form input[type="submit"]:hover {
            background-color: #0e1329;
        }

        /* Footer Section */
        footer {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 1.1em;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .activity-item {
                flex-direction: column;
                text-align: center;
            }
            .activity-item img {
                width: 80%;
                margin-bottom: 15px;
            }
            .activity-info {
                width: 100%;
            }
            .container {
                width: 90%;
            }
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>
Santo Tomas College of Agriculture, Sciences and Technology (STCAST)</h1>
        <p>Where Learning Meets Passion</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#about">About Us</a>
        <a href="#programs">Programs</a>
        <a href="#activities">School Activities</a>
        <a href="#contact">Contact Us</a>
    </nav>

    <!-- Main Content -->
    <div class="container">
        
        <!-- School Promotion Section -->
        <section id="about" class="about">
            <h2>Why Choose Santo Tomas College of Agriculture, Sciences and Technology?</h2>
            <p>At STCAST, we are dedicated to providing a nurturing and stimulating environment that empowers students to excel academically and personally. Our commitment to excellence, inclusive learning, and personal growth sets us apart from other schools. Here, students are not just prepared for exams—they are prepared for life!</p>
            <img src="STCAST.JPG"Our School Campus">
            <p>We offer a wide variety of academic and extracurricular programs that foster creativity, critical thinking, and leadership. Our team of experienced educators are passionate about ensuring each student's success, and we actively involve families in our vibrant school community.</p>
        </section>

        <!-- School Programs Section -->
        <section id="programs" class="programs">
            <h2>Our Programs</h2>
            <p>We offer a range of academic programs designed to prepare students for diverse careers::</p>

            <h3>Academic Excellence</h3>
            <p>We offer programs that emphasize academic excellence and are designed to equip students with the knowledge, skills, and competencies needed for success in their chosen fields.</p>

            <h3>We offer programs such as;</h3>
            <p>BSOA (Bachelor of Science in Office Administration): Prepares students for administrative roles with a focus on office management, business communication, and organizational skills.

BSAB (Bachelor of Science in Agriculture Business): Equips students with knowledge in agriculture, economics, and business management for careers in the agri-business sector.

BTVTED (Bachelor of Technical-Vocational Teacher Education): A program that trains students to become educators in technical-vocational fields, emphasizing hands-on teaching skills and industry knowledge.

Bachelor of Science in Entrepreneurship (BS Entrep) is a program designed to equip students with the knowledge, skills, and mindset needed to start and manage their own businesses. The program focuses on key areas such as business planning, marketing, financial management, operations, and innovation.

BPA (Bachelor of Public Administration): A program that develops leadership and management skills for careers in public service, governance, and policy-making.

BSISM (Bachelor of Science in Information Systems Management): Combines information technology with business management, preparing students for careers in IT and system administration.</p>

            <h3>Leadership Development</h3>
            <p>We believe in cultivating leadership skills in our students. Through student government, community service projects, and leadership workshops, we prepare our students to become responsible citizens and leaders in their communities.</p>
        </section>

        <!-- School Activities Section -->
        <section id="activities" class="activities">
            <h2>Exciting School Activities</h2>
            <p>At STCAST, learning extends beyond the classroom. We host a variety of events and activities that enrich our students’ educational experience and create lasting memories. Here are just a few of the exciting activities that we offer:</p>

            <div class="activity-item">
                <img src="https://via.placeholder.com/600x400" alt="Sports Day">
                <div class="activity-info">
                    <h3>Intramurals</h3>
                    <p>Our Annual Sports Day is a highlight of the school year. Students participate in a variety of events, from sprints to relay races, and cheer on their classmates. It's a great opportunity for team building and school spirit!</p>
                </div>
            </div>

            <div class="activity-item">
                <img src="https://via.placeholder.com/600x400" alt="Art Exhibition">
                <div class="activity-info">
                    <h3>Art & Science Exhibition</h3>
                    <p>Our students showcase their creative and scientific projects during our annual Art & Science Exhibition. From artwork to innovative science experiments, the exhibition celebrates our students' hard work and talent.</p>
                </div>
            </div>

            <div class="activity-item">
                <img src="https://via.placeholder.com/600x400" alt="Cultural Festival">
                <div class="activity-info">
                    <h3>Annual Cultural Festival</h3>
                    <p>Our cultural festival is a vibrant celebration of diversity and community. Students present performances, music, dances, and food from various cultures, enriching the entire school community.</p>
                </div>
            </div>
        </section>

        <!-- Contact Us Section -->
        <section id="contact" class="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions or would like to learn more about our school, please feel free to reach out to us. We are here to help!</p>

            <form action="#" method="post">
                <div class="form-group">
                    <label for="name">Your Name:</label>
                    <input type="text" id="name" name="name" required>
                </div>

                <div class="form-group">
                    <label for="email">Your Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>

                <div class="form-group">
                    <label for="message">Your Message:</label>
                    <textarea id="message" name="message" rows="4" required></textarea>
                </div>

                <input type="submit" value="Send Message">
            </form>
        </section>

    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Santo Tomas College of Agriculture, Sciences and Technology (STCAST). All rights reserved.</p>
    </footer>Santo Tomas College of Agriculture, Sciences and Technology (STCAST)

</body>
</html>
