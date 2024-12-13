 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Exercise</title>
    <style>
        body {
            background-color: #FFE4E1; /* Light pink background */
            color: black;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .title {
            text-align: center;
            font-weight: bold;
            font-size: 2rem;
            margin-top: 20px;
            margin-bottom: 20px;
        }
        .welcome-message {
            text-align: center;
            background-color: #E794B6; /* Slightly darker pink for the welcome message */
            padding: 15px;
            border-radius: 5px;
            font-size: 1.5rem;
            margin-bottom: 20px;
        }
        .nav {
            text-align: center;
            background-color: #E794B6; /* Light pink for navigation */
            padding: 10px;
        }
        .nav a {
            margin: 0 15px;
            text-decoration: none;
            color: black;
        }
        .nav a:hover {
            text-decoration: underline;
        }
        .section {
            margin-bottom: 40px;
        }
        .topic-img {
            display: block;
            margin: 20px auto;
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .audio, .image {
            text-align: center;
        }
        form {
            background-color: rgba(0, 0, 0, 0.1);
            padding: 20px;
            border-radius: 10px;
        }
        form label {
            display: block;
            margin-bottom: 5px;
        }
        form input, form select, form textarea {
            width: 100%;
            margin-bottom: 15px;
            padding: 10px;
            border: none;
            border-radius: 5px;
        }
        form input[type="submit"] {
            background-color: #000;
            color: white;
            font-weight: bold;
            cursor: pointer;
        }
        form input[type="submit"]:hover {
            background-color: lightgray;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Title -->
        <div class="title">
            E2 COMPUTER LAB EXERCISE
        </div>
        <!-- Welcoming Message -->
        <div class="welcome-message">
            <p>Welcome to Our Informative Web Page!</p>
            <p>Explore various topics, watch videos, and share your feedback with us.</p>
        </div>
        <div class="nav">
            <a href="#">Home</a>
            <a href="#">Article</a>
            <a href="#">Blog</a>
            <a href="#">Form</a>
        </div>
        <!-- Blog on Viruses, Malware, Spam, and Antiviruses -->
        <div class="section">
            <h2>Blog: Understanding Malware, Spam, Viruses, and Antiviruses</h2>
            <p>Malware is any software intentionally designed to cause harm to a computer, server, client, or network. This can include viruses, worms, trojans, ransomware, spyware, and adware. Malware typically gains unauthorized access to a system, often stealing sensitive information or causing operational disruptions.</p>
            <img src="images (6).jpeg" class="topic-img">
            <p>Spam refers to unsolicited or irrelevant messages sent over the internet, typically in bulk. It is a common vector for malware distribution, phishing scams, and unwanted advertisements.</p
            <p>Viruses are a type of malware that attach themselves to files or programs. When executed, they replicate and spread to other systems, often corrupting files, stealing data, or causing other damage.</p> 
            <p>Antivirus software is designed to detect, prevent, and remove malware. It scans files, monitors network traffic, and identifies suspicious activities. Keeping antivirus software updated is essential for effective protection against emerging threats.</p>
        </div>
        <!-- Web Page on Plagiarism -->
        <div class="section">
            <h2>Plagiarism: Cases and Punishments</h2>
            <p>Plagiarism involves using someone else's work, ideas, or intellectual property without proper attribution. It is a severe ethical and legal offense in academic, creative, and professional fields.</p>
            <img src="images (8).jpeg" alt="Plagiarism Illustration" class="topic-img">
            <p><strong>Reported Cases:</strong></p>
            <ul>
                <li>In 2012, a German politician was forced to resign after it was revealed that large portions of his doctoral thesis were plagiarized.</li>
                <li>A famous author faced backlash when it was discovered that several passages in their best-selling book were lifted from another source without credit.</li>
                <li>Many students face expulsion or academic penalties for submitting plagiarized assignments.</li>
            </ul>
            <p><strong>Punishments in Different Countries:</strong></p>
            <ul>
                <li><strong>United States:</strong> Plagiarism can lead to lawsuits, financial penalties, expulsion from academic institutions, and reputational damage.</li>
                <li><strong>Germany:</strong> Academic titles can be revoked, and public figures may face significant career setbacks.</li>
                <li><strong>India:</strong> Plagiarism in research can lead to blacklisting, retraction of published papers, and loss of employment.</li>
                <li><strong>United Kingdom:</strong> Plagiarism is considered a breach of copyright laws, leading to legal action and loss of academic credibility.</li>
            </ul>
            <!-- Video Embed -->
            <p><strong>Video Explanation on Plagiarism:</strong></p>
            <div class="video">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/EbWKUiLjGBs?si=IBvB0yQ-s2tM2FXu" frameborder="0" allowfullscreen></iframe>
            </div>
        </div>
        <!-- Embedded Media -->
        <div class="section">
            <h2>Media</h2>
            <div class="audio">
                <h3>Audio Example</h3>
                <audio controls>
                    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
                    Your browser does not support the audio element.
                </audio>
            </div>
        </div>
        <!-- Form Section -->
        <div class="section">
            <h2>Feedback Form</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required>
                <label for="gender">Gender:</label>
                <input type="radio" id="male" name="gender" value="Male">
                <label for="male">Male</label>
                <input type="radio" id="female" name="gender" value="Female">
                <label for="female">Female</label>
                <label for="interests">Select Interests:</label>
                <input type="checkbox" id="web-design" name="interests" value="Web Design">
                <label for="web-design">Web Design</label>
                <input type="checkbox" id="programming" name="interests" value="Programming">
                <label for="programming">Programming</label>
                <label for="country">Country:</label>
                <select id="country" name="country">
                    <option value="USA">USA</option>
                    <option value="UK">UK</option>
                    <option value="India">India</option>
                    <option value="Germany">Germany</option>
                </select>
                <label for="comments">Comments:</label>
                <textarea id="comments" name="comments" rows="5" placeholder="Enter your comments here"></textarea>
                <input type="submit" value="Submit Feedback">
            </form>
        </div>
        <!-- Navigation Links at the bottom -->
        <div class="nav" style="margin-top: 20px;">
            <a href="#">Home</a>
            <a href="#">Article</a>
            <a href="#">Blog</a>
            <a href="#">Form</a>
        </div>
    </div>
</body>
</html>
