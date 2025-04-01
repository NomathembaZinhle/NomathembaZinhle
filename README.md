<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nomathemba Zinhle Ndlovu - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Nomathemba Zinhle Ndlovu</h1>
        <p>Welcome to my portfolio</p>
    </header>

    <section class="about">
        <h2>About Me</h2>
        <p>I am a dedicated, organized and methodical individual. I have good interpersonal skills, am an excellent team worker, and am keen and very willing to learn and develop new skills. I have basic knowledge of network and some programming languages such as Java, C++, Python, and HTML.</p>
        <p>Contact me at:</p>
        <ul>
            <li>Phone: +27 76 700 4548</li>
            <li>Email: <a href="mailto:nomathembazinhle383@gmail.com">nomathembazinhle383@gmail.com</a></li>
        </ul>
    </section>

    <section class="experience">
        <h2>Experience</h2>
        <h3> Admin Clerk</h3>

        <ul>
            <li>Receive shipments and sign paperwork upon receipt</li>
            <li>Verify packages according to order and invoices (quantity, quality, price, etc.)</li>
            <li>Contact supplier or shipper if a mistake is identified</li>
            <li>Assume responsibility for returning unsatisfactory shipments or receiving replacements</li>
            <li>Ensure invoices are signed and paid for satisfactory deliveries</li>
            <li>Maintain accurate records and assist in inventory control</li>
        </ul>
    </section>

    <section class="education">
        <h2>Education</h2>
        <h3>Duck Ponds High School</h3>
        <p><strong>Grade 12 (Matric) - 2018</strong></p>
        <ul>
            <li>Isizulu Home Language</li>
            <li>English First Additional Language</li>
            <li>Physical Science</li>
            <li>Mathematics</li>
            <li>Geography</li>
            <li>Life Science</li>
            <li>Life Orientation</li>
        </ul>
        <h3>Tshwane University of Technology</h3>
        <p><strong>Diploma - Information Technology </strong></p>
    </section>

    <section class="expertise">
        <h2>Expertise</h2>
        <ul>
            <li>Problem Solving</li>
            <li>Time Management</li>
            <li>Active Listening</li>
            <li>Creativity</li>
            <li>Microsoft Office</li>
            <li>Circuit Connection</li>
            <li>Python</li>
            <li>Java</li>
            <li>C++</li>
            <li>HTML</li>
        </ul>
    </section>

    <footer>
        <p>Reference:  Ntombi Mlotshwa - 0781975342</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

/* Basic reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

header h1 {
    margin-bottom: 10px;
}

header p {
    font-style: italic;
}

section {
    margin: 20px;
    padding: 20px;
    background-color: white;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

section h2 {
    color: #333;
    margin-bottom: 10px;
}

section ul {
    list-style-type: none;
}

section ul li {
    margin-bottom: 8px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
}

footer p {
    font-size: 0.9rem;
}

a {
    color: #0066cc;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

h3 {
    margin-top: 15px;
}
// JavaScript to toggle additional details
document.querySelectorAll('.toggle-btn').forEach(button => {
    button.addEventListener('click', () => {
        const content = button.nextElementSibling;
        content.style.display = content.style.display === 'none' ? 'block' : 'none';
    });
});

