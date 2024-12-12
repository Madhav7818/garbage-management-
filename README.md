# garbage-management-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Waste Management Services</title>
    <link rel="stylesheet" href="WASTE CSS.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Waste Management Services</h1>
            <nav>
                <ul>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="hero">
            <h2>Keep Your Environment Clean</h2>
            <p>Your reliable partner in waste management.</p>
            <a href="#contact" class="btn">Get a Quote</a>
        </section>

        <section id="services" class="container">
            <h2>Our Services</h2>
            <div class="service">
                <h3>Residential Waste Collection</h3>
                <p>Regular collection of household waste.</p>
            </div>
            <div class="service">
                <h3>Commercial Waste Management</h3>
                <p>Tailored solutions for businesses.</p>
            </div>
            <div class="service">
                <h3>Recycling Services</h3>
                <p>We help you recycle and reduce waste.</p>
            </div>
        </section>

        <section id="about" class="container">
            <h2>About Us</h2>
            <p>We are committed to providing efficient and sustainable waste management solutions.</p>
        </section>

        <section id="contact" class="container">
            <h2>Contact Us</h2>
            <form>
                <input type="text" placeholder="CONTIBUTER Name" required>
                <input type="email" placeholder="CONTRIBUTER Email" required>
                <textarea placeholder=" Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

</body>
</html>

css
* {
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
}

header {
    background: #4CAF50;
    color: white;
    padding: 1rem 0;
    animation: fadeIn 1s;
}

header h1 {
    margin: 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #ffeb3b;
}

#hero {
    background: #f2f2f2;
    text-align: center;
    padding: 50px 0;
    animation: slideIn 1s;
}

#hero h2 {
    margin: 0;
}

#hero .btn {
    background: #4CAF50;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    transition: background 0.3s;
}

#hero .btn:hover {
    background: #388E3C;
}

#services, #about, #contact {
    padding: 20px 0;
}

.service {
    border: 1px solid #ccc;
    padding: 20px;
    margin: 10px 0;
    transition: transform 0.3s, box-shadow 0.3s;
}

.service:hover {
    transform: translateY(-5px);
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
}

form {
    display: flex;
    flex-direction: column;
}
