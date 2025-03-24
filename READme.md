<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Experience</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            background: #121212;
            color: white;
            text-align: center;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        .section {
            width: 80%;
            max-width: 600px;
            background: #1e1e1e;
            padding: 20px;
            margin: 20px 0;
            border-radius: 10px;
            transition: all 0.3s ease-in-out;
            cursor: pointer;
            overflow: hidden;
        }
        .section:hover {
            background: #333;
            transform: scale(1.05);
        }
        .section h2 {
            margin-bottom: 10px;
        }
        .hidden-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.5s ease-in-out;
        }
        .section:hover .hidden-content {
            max-height: 200px;
        }
        .back-button {
            display: inline-block;
            margin-top: 30px;
            padding: 10px 20px;
            background: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: 0.3s;
        }
        .back-button:hover {
            background: #45a049;
        }
    </style>
</head>
<body>

    <h1>🏆 My Work Experience</h1>
    <p>Hover over each section to view details.</p>

    <div class="container">

        <div class="section">
            <h2>⚽ Sports & Fitness</h2>
            <div class="hidden-content">
                <p>✅ Coaching & Athlete Development</p>
                <p>✅ Sports Management</p>
                <p>✅ Nutrition & Fitness Training</p>
                <p>✅ Training Programs</p>
            </div>
        </div>

        <div class="section">
            <h2>🛍️ E-Commerce & Retail</h2>
            <div class="hidden-content">
                <p>✅ Shopify Store Management</p>
                <p>✅ Product Listing & Inventory</p>
                <p>✅ Customer Orders & Fulfillment</p>
            </div>
        </div>

        <div class="section">
            <h2>📦 Warehousing & Logistics</h2>
            <div class="hidden-content">
                <p>✅ Leadership Roles</p>
                <p>✅ Pick Packing & Order Fulfillment</p>
                <p>✅ Inventory Management</p>
                <p>✅ Administrative Work</p>
            </div>
        </div>

        <div class="section">
            <h2>📢 Customer Service & Sales</h2>
            <div class="hidden-content">
                <p>✅ Client Engagement</p>
                <p>✅ Sales at Football Club</p>
                <p>✅ Problem-Solving</p>
            </div>
        </div>

        <a href="index.html" class="back-button">⬅ Back to Home</a>

    </div>

</body>
</html>
