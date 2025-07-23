<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flipkart Clone - Feature Demo</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom styles for a more refined look */
        body {
            font-family: 'Inter', sans-serif; /* Using Inter font */
            background: #f0f2f5;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }
        h1 {
            text-align: center;
            color: #333;
            margin-bottom: 30px;
            font-size: 2.5rem; /* Larger heading */
            font-weight: 700;
        }
        .tech-stack-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
            margin-bottom: 40px;
        }
        .tech-stack-container a {
            display: inline-block; /* Ensure links behave like blocks for padding/margin */
            transition: transform 0.2s ease-in-out;
        }
        .tech-stack-container a:hover {
            transform: translateY(-3px) scale(1.05); /* Lift and slightly enlarge on hover */
        }
        .tech-stack-container img {
            border-radius: 6px; /* Rounded corners for badges */
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Subtle shadow */
        }
        h2 {
            font-size: 1.8rem;
            font-weight: 600;
            color: #333;
            margin-top: 40px;
            margin-bottom: 20px;
            text-align: center;
        }
        .button-container {
            display: flex;
            flex-wrap: wrap;
            gap: 15px; /* Increased gap for better spacing */
            justify-content: center;
            margin-top: 20px;
            max-width: 900px; /* Max width for button container */
            width: 100%;
        }
        .feature-button {
            padding: 12px 25px; /* Larger padding for buttons */
            border: none;
            border-radius: 8px; /* More rounded corners */
            color: white;
            font-weight: 600; /* Slightly bolder font */
            cursor: pointer;
            transition: all 0.2s ease-in-out; /* Smooth transition for all properties */
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Subtle shadow */
            flex-grow: 1; /* Allow buttons to grow */
            min-width: 180px; /* Minimum width for buttons */
            text-align: center;
        }
        .feature-button:hover {
            transform: translateY(-3px) scale(1.02); /* Lift and slightly enlarge on hover */
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15); /* Enhanced shadow on hover */
            opacity: 1; /* Ensure full opacity */
        }
        /* Color classes from original, adjusted for Tailwind-like feel */
        .bg-green-500 { background-color: #4CAF50; }
        .bg-blue-500 { background-color: #2196F3; }
        .bg-red-500 { background-color: #f44336; }
        .bg-orange-500 { background-color: #ff9800; }
        .bg-purple-500 { background-color: #9c27b0; }
        .bg-indigo-500 { background-color: #3f51b5; }
        .bg-teal-500 { background-color: #009688; }
        .bg-pink-500 { background-color: #e91e63; }
        .bg-gray-700 { background-color: #607d8b; } /* Darker gray for better contrast */
        .bg-amber-700 { background-color: #795548; } /* Brown */
        .bg-violet-700 { background-color: #673ab7; } /* Deep Purple */
        .bg-blue-700 { background-color: #2a65a3; } /* Custom blue for orders */
 #output {
            margin-top: 40px; /* More space above output */
            background: #fff;
            padding: 20px; /* More padding */
            border-radius: 10px; /* More rounded corners */
            box-shadow: 0 2px 10px rgba(0,0,0,0.08); /* Finer shadow */
            font-family: 'Segoe UI Mono', monospace; /* Monospace font for output */
            min-height: 80px; /* Taller output area */
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: #555;
            font-size: 1.1rem;
            width: 100%;
            max-width: 700px; /* Max width for output */
            border: 1px solid #e0e0e0; /* Subtle border */
        }
 .footer {
            text-align: center;
            margin-top: auto; /* Push footer to the bottom */
            padding-top: 40px;
            color: #777;
            font-size: 0.9rem;
        }
 /* Connect Me section styling */
        .connect-me {
            margin-top: 50px;
            text-align: center;
            font-size: 1.2rem;
            color: #333;
        }
        .connect-me strong {
            color: #007bff; /* A nice blue for the name */
        }
 /* Responsive adjustments */
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            .tech-stack-container {
                gap: 8px;
            }
            .tech-stack-container img {
                height: 30px; /* Smaller badges on mobile */
            }
            h2 {
                font-size: 1.5rem;
            }
            .button-container {
                gap: 10px;
                padding: 0 10px;
            }
            .feature-button {
                padding: 10px 20px;
                min-width: unset; /* Allow smaller width on mobile */
                width: calc(50% - 10px); /* Two columns on smaller screens */
            }
            #output {
                padding: 15px;
                font-size: 1rem;
            }
            .connect-me {
                font-size: 1rem;
            }
        }
  @media (max-width: 480px) {
            .feature-button {
                width: 100%; /* Single column on very small screens */
            }
        }
    </style>
</head>
<body>
<h1>🔗 Flipkart-Clone-PHP</h1>
    <p class="text-center text-gray-600 mb-8">Full Stack Flipkart Clone Using LAMP Stack</p>
<h2>🛠️ Tech Stack</h2>
    <div class="tech-stack-container">
        <!-- Tech Stack Badges with Links -->
        <a href="https://www.google.com/search?q=HTML5" target="_blank" rel="noopener noreferrer">
            <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Badge"/>
        </a>
        <a href="https://www.google.com/search?q=CSS3" target="_blank" rel="noopener noreferrer">
            <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3 Badge"/>
        </a>
        <a href="https://www.google.com/search?q=Tailwind+CSS" target="_blank" rel="noopener noreferrer">
            <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS Badge"/>
        </a>
        <a href="https://www.google.com/search?q=JavaScript" target="_blank" rel="noopener noreferrer">
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript Badge"/>
        </a>
        <a href="https://www.google.com/search?q=jQuery" target="_blank" rel="noopener noreferrer">
            <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery Badge"/>
        </a>
        <a href="https://www.google.com/search?q=PHP" target="_blank" rel="noopener noreferrer">
            <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP Badge"/>
        </a>
        <a href="https://www.google.com/search?q=MySQL" target="_blank" rel="noopener noreferrer">
            <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL Badge"/>
        </a>
    </div>

 <h2>✨ Features</h2>
    <div class="button-container">
        <!-- Buttons with Tailwind-like color classes and enhanced styling -->
        <button class="feature-button bg-green-500" onclick="featureAction('signup')">
            <span class="mr-2">🚀</span>OTP Email Verified Signup
        </button>
        <button class="feature-button bg-blue-500" onclick="featureAction('login')">
            <span class="mr-2">🔐</span>Login, Signup & Logout
        </button>
        <button class="feature-button bg-red-500" onclick="featureAction('ajax')">
            <span class="mr-2">💬</span>AJAX Requests
        </button>
        <button class="feature-button bg-orange-500" onclick="featureAction('wishlist')">
            <span class="mr-2">❤️</span>Wishlist Management
        </button>
        <button class="feature-button bg-purple-500" onclick="featureAction('cart')">
            <span class="mr-2">🛒</span>Cart Management
        </button>
        <button class="feature-button bg-indigo-500" onclick="featureAction('save_for_later')">
            <span class="mr-2">💡</span>Save For Later
        </button>
        <button class="feature-button bg-teal-500" onclick="featureAction('payment')">
            <span class="mr-2">💳</span>Cashfree Payment Gateway
        </button>
        <button class="feature-button bg-pink-500" onclick="featureAction('profile')">
            <span class="mr-2">👤</span>Profile Page
        </button>
        <button class="feature-button bg-gray-700" onclick="featureAction('update')">
            <span class="mr-2">📱</span>Personal Info Update
        </button>
        <button class="feature-button bg-amber-700" onclick="featureAction('product')">
            <span class="mr-2">📦</span>Product Details Enhancement
        </button>
        <button class="feature-button bg-violet-700" onclick="featureAction('purchase')">
            <span class="mr-2">🛍️</span>Buy Now & Add To Cart
        </button>
        <button class="feature-button bg-blue-700" onclick="featureAction('orders')">
            <span class="mr-2">🚚</span>Basic Orders Tracking
        </button>
    </div>

 <div id="output" class="text-gray-800">Click a button to see feature response...</div>
    <div class="connect-me">
        Developed with ❤️ by <strong>Goli Harini</strong>
    </div>

<div class="footer">
        <p class="text-gray-600">© 2023 Flipkart Clone. All rights reserved.</p>
    </div>

<script>
     // Function to handle button clicks and update the output area
        function featureAction(feature) {
            let output = '';
            switch(feature) {
                case 'signup':
                    output = '🚀 Ensures secure and verified user registrations with OTP-based email verification.';
                    break;
                case 'login':
                    output = '🔐 Provides smooth and secure authentication processes for users, including login, registration, and session management.';
                    break;
                case 'ajax':
                    output = '💬 Enhances the user experience with seamless data retrieval and updates without full page reloads.';
                    break;
                case 'wishlist':
                    output = '❤️ Allows users to effortlessly add and remove products from their personalized wishlists.';
                    break;
                case 'cart':
                    output = '🛒 Streamlines shopping experiences with easy product addition, removal, and quantity management in the shopping cart.';
                    break;
                case 'save_for_later':
                    output = '💡 Enables users to save products for future consideration, moving them out of the active cart.';
                    break;
                case 'payment':
                    output = '💳 Facilitates secure and efficient online transactions through integration with the Cashfree payment gateway.';
                    break;
                case 'profile':
                    output = '👤 Provides a centralized hub for managing account details, personal information, and preferences.';
                    break;
                case 'update':
                    output = '📱 Allows users to update their personal information and mobile number directly from their profile.';
                    break;
                case 'product':
                    output = '📦 Improves product browsing with dynamic hover effects and detailed product specifications.';
                    break;
                case 'purchase':
                    output = '🛍️ Offers convenient purchase options, allowing users to either buy immediately or add items to their cart.';
                    break;
                case 'orders':
                    output = '🚚 Keeps users informed with simple order tracking functionalities, from placement to delivery.';
                    break;
                default:
                    output = '❌ Unknown feature selected.';
            }
            document.getElementById('output').textContent = output;
        }
    </script>

</body>
</html>
