[index2.html](https://github.com/user-attachments/files/25027403/index2.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AK Property Cleaning Services - Hamilton, Ontario</title>
    <style>
        /* CSS for more vibrant and professional styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff; /* Light blue-ish for vibrancy */
            color: #333;
        }
        header {
            background: linear-gradient(135deg, #007bff, #00bfff); /* Vibrant blue gradient */
            color: white;
            padding: 40px 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        header h1 {
            margin: 0;
            font-size: 3em;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        .hero {
            background-color: #ffffff;
            padding: 60px 20px;
            text-align: center;
            border-bottom: 4px solid #ff4500; /* Vibrant orange accent */
        }
        .hero h2 {
            color: #ff4500; /* Orange for energy */
            font-size: 2.2em;
        }
        .hero p {
            max-width: 800px;
            margin: 20px auto 0;
            font-size: 1.3em;
            line-height: 1.8;
            color: #444;
        }
        .services {
            padding: 60px 20px;
            background: linear-gradient(135deg, #e9ecef, #ffffff); /* Subtle gradient for depth */
            text-align: center;
        }
        .services h2 {
            color: #007bff;
            font-size: 2.5em;
            margin-bottom: 40px;
        }
        .services ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }
        .services li {
            background-color: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
            width: 320px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .services li:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.2);
        }
        .services h3 {
            color: #28a745; /* Green for freshness */
            font-size: 1.8em;
        }
        .eco-tips {
            padding: 60px 20px;
            background: linear-gradient(135deg, #d4edda, #ffffff); /* Greenish gradient for eco theme */
            text-align: center;
        }
        .eco-tips h2 {
            color: #28a745; /* Green for eco-friendliness */
            font-size: 2.5em;
            margin-bottom: 40px;
        }
        .eco-tips ul {
            list-style: none;
            padding: 0;
            max-width: 800px;
            margin: 0 auto;
            text-align: left;
        }
        .eco-tips li {
            background-color: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        .eco-tips li:hover {
            transform: translateY(-5px);
        }
        .eco-tips h3 {
            color: #007bff;
            font-size: 1.6em;
            margin-bottom: 10px;
        }
        .eco-tips p {
            font-size: 1.1em;
            line-height: 1.6;
            color: #555;
        }
        .quote-form {
            padding: 60px 20px;
            background-color: #ffffff;
            text-align: center;
            border-top: 4px solid #28a745; /* Green accent */
        }
        .quote-form h2 {
            color: #ff4500;
            font-size: 2.5em;
            margin-bottom: 40px;
        }
        .quote-form form {
            max-width: 700px;
            margin: 0 auto;
            background: #f8f9fa;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        .quote-form label {
            display: block;
            margin: 15px 0 5px;
            text-align: left;
            font-weight: bold;
            color: #007bff;
        }
        .quote-form input[type="text"],
        .quote-form input[type="email"],
        .quote-form textarea {
            width: 100%;
            padding: 12px;
            margin-bottom: 20px;
            border: 2px solid #007bff;
            border-radius: 6px;
            transition: border-color 0.3s ease;
        }
        .quote-form input[type="text"]:focus,
        .quote-form input[type="email"]:focus,
        .quote-form textarea:focus {
            border-color: #ff4500;
            outline: none;
        }
        .quote-form input[type="checkbox"] {
            margin-right: 10px;
            accent-color: #28a745; /* Green checkbox */
        }
        .quote-form button {
            background: linear-gradient(135deg, #28a745, #32cd32); /* Vibrant green gradient */
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 1.2em;
            transition: background 0.3s ease;
        }
        .quote-form button:hover {
            background: linear-gradient(135deg, #218838, #2e8b57);
        }
        .payment-section {
            padding: 60px 20px;
            background: linear-gradient(135deg, #f8f9fa, #e9ecef);
            text-align: center;
        }
        .payment-section h2 {
            color: #007bff;
            font-size: 2.5em;
        }
        .payment-section p {
            font-style: italic;
            color: #555;
            font-size: 1.2em;
        }
        footer {
            background: linear-gradient(135deg, #007bff, #00bfff);
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 1.1em;
        }
        /* Vibrant accents */
        a {
            color: #ff4500;
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            color: #ff6347;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>AK Property Cleaning Services</h1>
        <p>Professional Cleaning Solutions in Hamilton, Ontario</p>
    </header>

    <section class="hero">
        <h2>Welcome to AK Property Cleaning Services</h2>
        <p>At AK Property Cleaning Services, we deliver top-tier residential, commercial, and industrial cleaning solutions tailored to meet the unique needs of our clients in Hamilton, Ontario. With a team of experienced professionals using eco-friendly products and state-of-the-art equipment, we ensure spotless results that exceed expectations. Businesses and individuals choose us for our reliability, attention to detail, competitive pricing, and commitment to customer satisfaction. Whether it's a one-time deep clean or ongoing maintenance, we're dedicated to making your space shine—because a clean environment is the foundation of productivity and well-being.</p>
    </section>

    <section class="services">
        <h2>Our Services</h2>
        <ul>
            <li>
                <h3>Residential Cleaning</h3>
                <p>Thorough cleaning for homes, apartments, and condos to keep your living space fresh and inviting.</p>
            </li>
            <li>
                <h3>Commercial Cleaning</h3>
                <p>Office and retail space cleaning to maintain a professional and hygienic work environment.</p>
            </li>
            <li>
                <h3>Industrial Cleaning</h3>
                <p>Heavy-duty cleaning for factories, warehouses, and industrial sites to ensure safety and efficiency.</p>
            </li>
        </ul>
    </section>

    <section class="eco-tips">
        <h2>Eco-Friendly Cleaning Tips</h2>
        <ul>
            <li>
                <h3>Use Natural Ingredients</h3>
                <p>Opt for vinegar, baking soda, and lemon juice for effective, non-toxic cleaning. These household items can tackle grease, stains, and odors without harming the environment.</p>
            </li>
            <li>
                <h3>Reduce Water Waste</h3>
                <p>Turn off the tap while scrubbing and use microfiber cloths that require less water and no chemicals. This conserves resources and keeps your space clean efficiently.</p>
            </li>
            <li>
                <h3>Choose Reusable Tools</h3>
                <p>Switch to reusable sponges, cloths, and mop heads instead of disposable ones. Wash and reuse them to minimize waste and promote sustainability in your daily cleaning routine.</p>
            </li>
            <li>
                <h3>Ventilate Spaces</h3>
                <p>Open windows during cleaning to improve air quality and reduce the need for chemical air fresheners. Fresh air helps in drying surfaces faster and naturally freshens the environment.</p>
            </li>
            <li>
                <h3>Recycle and Upcycle</h3>
                <p>Sort cleaning waste properly and repurpose old containers for storage. This not only keeps your space organized but also supports a circular economy.</p>
            </li>
        </ul>
    </section>

    <section class="quote-form">
        <h2>Get a Free Quote</h2>
        <form action="#" method="post"> <!-- Replace '#' with your backend endpoint if needed -->
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Phone:</label>
            <input type="text" id="phone" name="phone">

            <label>Services Interested In:</label>
            <div>
                <input type="checkbox" id="residential" name="services" value="Residential">
                <label for="residential">Residential Cleaning</label>
            </div>
            <div>
                <input type="checkbox" id="commercial" name="services" value="Commercial">
                <label for="commercial">Commercial Cleaning</label>
            </div>
            <div>
                <input type="checkbox" id="industrial" name="services" value="Industrial">
                <label for="industrial">Industrial Cleaning</label>
            </div>

            <label for="message">Additional Details:</label>
            <textarea id="message" name="message" rows="4"></textarea>

            <button type="submit">Submit Quote Request</button>
        </form>
    </section>

    <section class="payment-section">
        <h2>Payment Options</h2>
        <p>We accept various payment methods. Bitcoin payment system integration is planned here. (Backend placeholder: Integrate your Bitcoin payment gateway API in this section, e.g., using libraries like Blockcypher or Coinbase API for processing BTC transactions.)</p>
    </section>

    <footer>
        <p>&copy; 2026 AK Property Cleaning Services. All rights reserved. | Hamilton, Ontario | Contact: AKPropertyservicesinc@gmail.com</p>
    </footer>

    <script>
        // Basic JS for form submission alert (for demo purposes)
        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your quote request! We will get back to you soon.');
        });
    </script>
</body>
</html>
