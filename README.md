# Instituteshaan
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shaan Institute | Skill Development Academy</title>
    <style>
        /* CSS Styles */
        :root {
            --primary-blue: #1a2a6c;
            --gold: #b8860b;
            --light-gray: #f4f4f4;
            --white: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            line-height: 1.6;
            color: #333;
        }

        /* Navigation */
        nav {
            background: var(--primary-blue);
            color: var(--white);
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo-area { font-weight: bold; font-size: 1.5rem; }
        .reg-no { font-size: 0.8rem; display: block; color: var(--gold); }

        nav ul { list-style: none; display: flex; margin: 0; }
        nav ul li { margin-left: 20px; }
        nav ul li a { color: white; text-decoration: none; font-weight: 500; }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            height: 60vh;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
        }

        .btn {
            background: var(--gold);
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
            transition: 0.3s;
        }

        /* Sections */
        section { padding: 60px 10%; }
        .bg-light { background: var(--light-gray); }

        h2 { border-bottom: 2px solid var(--gold); display: inline-block; margin-bottom: 30px; }

        /* Courses Table */
        .table-container { overflow-x: auto; }
        table { width: 100%; border-collapse: collapse; background: white; margin-bottom: 20px; }
        table th, table td { padding: 15px; border: 1px solid #ddd; text-align: left; }
        table th { background: var(--primary-blue); color: white; }

        /* Grid for Cards */
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .card { background: white; padding: 20px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }

        /* Footer */
        footer { background: #222; color: white; text-align: center; padding: 40px 10%; }
        
        @media (max-width: 768px) {
            nav ul { display: none; } /* Simplified for mobile preview */
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo-area">
            SHAAN INSTITUTE
            <span class="reg-no">Regd No. MAH/943/08</span>
        </div>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#courses">Courses</a></li>
            <li><a href="#enroll">Enroll</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section class="hero">
        <h1>Empowering Women Through Skill Development</h1>
        <p>A Government Registered Trustable Institute Since 2008</p>
        <a href="#courses" class="btn">View Our Courses</a>
    </section>

    <section id="about">
        <h2>About Shaan Institute</h2>
        <p>Shaan Institute is a trustable institute, we are giving our service in training and empowering women since 2008. Many of our students are exploring their career path by upgrading their skill in Shaan Institute. Our institute is registered by the government (MAH/943/08), ensuring quality education and professional standards.</p>
    </section>

    <section id="courses" class="bg-light">
        <h2>Our Professional Courses</h2>
        <div class="table-container">
            <table>
                <thead>
                    <tr>
                        <th>Course Name</th>
                        <th>Duration</th>
                        <th>Details</th>
                        <th>Fees (INR)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Fashion Designing</strong></td>
                        <td>2 Years</td>
                        <td>18 months course + 6 months internship</td>
                        <td>₹60,000 (Instalments available)</td>
                    </tr>
                    <tr>
                        <td><strong>Tailoring</strong></td>
                        <td>6 Months</td>
                        <td>Designing making, measurement, stitching, cutting</td>
                        <td>₹5,000</td>
                    </tr>
                    <tr>
                        <td><strong>Advance Tailoring</strong></td>
                        <td>8 Months</td>
                        <td>Pattern making (Ladies outfit) & complete stitching</td>
                        <td>₹5,000</td>
                    </tr>
                    <tr>
                        <td><strong>Painting</strong></td>
                        <td>3 Months</td>
                        <td>Fibre, Pot, Glass, Sand, Nib, Emboss, Copper</td>
                        <td>₹3,000</td>
                    </tr>
                    <tr>
                        <td><strong>Cooking</strong></td>
                        <td>Practical</td>
                        <td>40 dishes using homemade masala</td>
                        <td>₹5,000</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <div class="grid">
            <div class="card">
                <h3>Embroidery</h3>
                <p>Aari work, Mirror work, Zardozi, Hand embroidery, Fancy work, Qureishi work, and Ribbon work.</p>
            </div>
            <div class="card">
                <h3>Beautician</h3>
                <p>Makeup artist training, Bridal packages, Hairstyle, Saree and Sharara dripping.</p>
            </div>
            <div class="card">
                <h3>Mehendi</h3>
                <p>All types of designs, Organic cone making. Become a professional mehendi artist.</p>
            </div>
        </div>
    </section>

    <section id="enroll">
        <h2>How to Enroll</h2>
        <p>Take the next step in your career. Send your <strong>Name</strong> and <strong>Selected Course</strong> to:</p>
        <p>📧 <strong>Email:</strong> <a href="mailto:instituteshaan@gmail.com">instituteshaan@gmail.com</a></p>
        <p>📞 <strong>WhatsApp/Call:</strong> 9819228098</p>
    </section>

    <section id="contact" class="bg-light">
        <h2>Visit Us</h2>
        <p><strong>Location:</strong> <a href="https://maps.app.goo.gl/8rTfqzbT3E3nL6uj8?g_st=atm" target="_blank">Click here for Google Maps</a></p>
        <p>Mumbai, Maharashtra, India</p>
    </section>

    <footer>
        <p><strong>Shaan Institute</strong> - Established 2008</p>
        <p>Regd No. MAH/943/08 | Empowering Women Since 2008</p>
    </footer>

</body>
</html>
