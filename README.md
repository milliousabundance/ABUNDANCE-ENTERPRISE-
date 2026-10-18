 ABUNDANCE-ENTERPRISE-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Abundance Enterprise</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header>
        <h1>🌱 Abundance Enterprise</h1>

        <nav>
            <a href="index.html">Home</a>
            <a href="catalog.html">Product Catalogue</a>
            <a href="#order">Place Order</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Welcome to Abundance Enterprise</h2>

        <p>
            Your trusted destination for agricultural supplies
            and pest-control enquiries.
        </p>

        <a href="catalog.html" class="button">
            View Our Products
        </a>
    </section>

    <section class="products">

        <h2>Our Products</h2>

        <div class="product-container">

            <div class="product">
                <img
                    src="https://placehold.co/300x200/e5f5e8/176b45?text=Insecticide"
                    alt="Insecticide product illustration"
                >

                <h3>Insecticide</h3>

                <p>For appropriate insect-control applications.</p>

                <a href="catalog.html">View Catalogue</a>
            </div>

            <div class="product">
                <img
                    src="https://placehold.co/300x200/e5f5e8/176b45?text=Herbicide"
                    alt="Herbicide product illustration"
                >

                <h3>Herbicide</h3>

                <p>For weed management through approved use.</p>

                <a href="catalog.html">View Catalogue</a>
            </div>

            <div class="product">
                <img
                    src="https://placehold.co/300x200/e5f5e8/176b45?text=Pesticide"
                    alt="Pesticide product illustration"
                >

                <h3>Pesticide</h3>

                <p>Explore suitable pest-management products.</p>

                <a href="catalog.html">View Catalogue</a>
            </div>

            <div class="product">
                <img
                    src="https://placehold.co/300x200/e5f5e8/176b45?text=Snake+Repellent"
                    alt="Snake repellent product illustration"
                >

                <h3>Snake Repellent</h3>

                <p>Ask about suitable, legally approved options.</p>

                <a href="catalog.html">View Catalogue</a>
            </div>

        </div>
    </section>

    <section class="order-section" id="order">

        <h2>Place Your Order</h2>

        <p>
            Enter your information and select the products you want.
        </p>

        <form id="orderForm">

            <h3>Customer Information</h3>

            <label for="name">Full Name</label>

            <input
                type="text"
                id="name"
                name="name"
                required
            >

            <label for="phone">Phone Number</label>

            <input
                type="tel"
                id="phone"
                name="phone"
                required
            >

            <label for="email">Email Address</label>

            <input
                type="email"
                id="email"
                name="email"
                required
            >

            <label for="state">State</label>

            <input
                type="text"
                id="state"
                name="state"
                required
            >

            <label for="lga">Local Government Area</label>

            <input
                type="text"
                id="lga"
                name="lga"
                required
            >

            <h3>Select Your Products</h3>

            <div id="orderItems"></div>

            <h3>Full Order List</h3>

            <div id="orderSummary">
                <p>No products selected yet.</p>
            </div>

            <div class="total">
                <h3>
                    Total Price:
                    <span id="totalPrice">₦0</span>
                </h3>
            </div>

            <label for="notes">Additional Information</label>

            <textarea
                id="notes"
                name="notes"
                rows="4"
                placeholder="Enter any additional information"
            ></textarea>

            <button type="submit" class="button">
                Submit Order Enquiry
            </button>

            <p id="message"></p>

            <p class="notice">
                Prices are estimates until confirmed.
                Orders for regulated pest-control products
                must comply with applicable laws and safety requirements.
            </p>

        </form>
    </section>

    <footer>
        <h3>Abundance Enterprise</h3>

        <p>Agricultural Supplies and Pest-Control Enquiries</p>

        <p>
            Email:
            <a href="mailto:milliousabundance@gmail.com">
                milliousabundance@gmail.com
            </a>
        </p>

        <p>© 2026 Abundance Enterprise</p>
    </footer>

    <script src="script.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@5/dist/email.min.js"></script>
</body>
</html> 
