[index1.html](https://github.com/user-attachments/files/25028411/index1.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
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
