# ABOUT ME 
<WELCOME>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ujjwala Sanaye | Personal Website</title>

    <style>
        /* ---- GLOBAL ---- */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: "Segoe UI", Arial, sans-serif;
            background: #0d0d0d;
            color: #eee;
            line-height: 1.6;
        }
        section { padding: 40px 20px; max-width: 1000px; margin: auto; }

        /* ---- HEADER / HERO ---- */
        header {
            text-align: center;
            padding: 80px 20px;
            background: linear-gradient(135deg, #2575fc, #6a11cb);
            color: #fff;
        }
        header h1 { font-size: 42px; margin-bottom: 10px; }
        header p { font-size: 18px; opacity: 0.85; }

        /* ---- HEADINGS ---- */
        section h2 {
            color: #61dafb;
            font-size: 28px;
            margin-bottom: 15px;
            border-bottom: 2px solid rgba(97, 218, 251, 0.25);
            padding-bottom: 8px;
        }

        /* ---- LISTS ---- */
        ul { list-style-type: none; }
        li { margin-bottom: 8px; }

        /* ---- SKILLS BOXES ---- */
        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .box {
            background: #161616;
            border: 1px solid #333;
            padding: 18px;
            border-radius: 8px;
        }
        .box h3 { margin-bottom: 10px; color: #61dafb; }

        /* ---- CONTACT FORM ---- */
        .contact-container {
            background: #161616;
            padding: 30px;
            border-radius: 10px;
            border: 1px solid #333;
        }
        .contact-container label {
            display: block;
            margin: 12px 0 6px;
            font-size: 16px;
        }
        .contact-container input,
        .contact-container textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #444;
            border-radius: 6px;
            background: #0d0d0d;
            color: #fff;
            font-size: 15px;
        }
        .contact-container button {
            margin-top: 15px;
            padding: 12px 24px;
            background: #2575fc;
            border: none;
            border-radius: 6px;
            color: white;
            cursor: pointer;
            font-size: 16px;
            transition: 0.3s ease;
        }
        .contact-container button:hover {
            background: #1a5fc8;
        }

        footer {
            text-align: center;
            padding: 15px;
            background: #111;
            color: #aaa;
            font-size: 14px;
        }
    </style>
</head>

<body>

    <!-- HERO -->
    <header>
        <h1>👋 Hi, I’m Ujjwala Sanaye</h1>
        <p>Motivated student with a passion for growth and learning</p>
    </header>

    <!-- ABOUT -->
    <section>
        <h2>🙋‍♀ ABOUT ME</h2>
        <p>
            I am Ujjwala Sanaye, a dedicated and curious individual focused on
            continuous learning and personal growth. I enjoy taking on challenges
            that build skills and prepare me for future opportunities.
        </p>
    </section>

    <!-- EDUCATION -->
    <section>
        <h2>🎓 EDUCATION</h2>
        <ul>
            <li>📚 Currently studying BMS</li>
            <li>🏫 Aditya Institute of Management Studies and Research</li>
            <li>🌱 Actively doing projects & learning practical skills</li>
        </ul>
    </section>

    <!-- SKILLS -->
    <section>
        <h2>🛠 SKILLS</h2>
        <div class="skills">
            <div class="box">
                <h3>Technical Skills</h3>
                <ul>
                    <li>Basic Computer Knowledge</li>
                    <li>MS Word, Excel & PowerPoint</li>
                    <li>Internet & Email Handling</li>
                </ul>
            </div>
            <div class="box">
                <h3>Soft Skills</h3>
                <ul>
                    <li>Communication Skills</li>
                    <li>Time Management</li>
                    <li>Teamwork</li>
                    <li>Quick Learner</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- GOALS -->
    <section>
        <h2>🎯 MY GOALS</h2>
        <ul>
            <li>Gain knowledge & real-world experience</li>
            <li>Improve skills continuously</li>
            <li>Build a successful, meaningful career</li>
        </ul>
    </section>

    <!-- HOBBIES -->
    <section>
        <h2>🎨 HOBBIES & INTERESTS</h2>
        <ul>
            <li>Listening to music</li>
            <li>Learning new things</li>
            <li>Exploring creative ideas</li>
            <li>Self-improvement</li>
        </ul>
    </section>

    <!-- CONTACT -->
    <section>
        <h2>📩 CONTACT ME</h2>
        <div class="contact-container">
            <form>
                <label for="name">Your Name</label>
                <input type="text" id="name" placeholder="Enter your name">

                <label for="email">Email</label>
                <input type="email" id="email" placeholder="Enter your email">

                <label for="message">Message</label>
                <textarea id="message" rows="4" placeholder="Write your message"></textarea>

                <button type="submit">Send Message</button>
            </form>
        </div>
        <p style="margin-top: 15px; font-size: 18px;">
            Or email me directly at  
            <a href="mailto:sanayeujjwala@gmail.com" style="color:#61dafb;">
                sanayeujjwala@gmail.com
            </a>
        </p>
    </section>

    <footer>© 2026 Ujjwala Sanaye</footer>

</body>
</html>
