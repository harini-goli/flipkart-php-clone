# Flipkart-Clone-PHP

Full Stack Flipkart Clone Using LAMP Stack

## Tech Stack

For an interactive view of the tech stack and related features, please open the [Tech Stack Features](techstack_features.html) page.

- HTML5
- CSS3
- Tailwind CSS
- JavaScript
- jQuery
- PHP
- MySQL

## Features

<div style="display: flex; flex-wrap: wrap; gap: 10px; margin-top: 10px;">

<button style="background-color: #4CAF50; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;" onclick="featureAction('signup')">Secure Signup</button>

<button style="background-color: #2196F3; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;" onclick="featureAction('login')">User Authentication</button>

<button style="background-color: #f44336; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;" onclick="featureAction('ajax')">AJAX Data Fetch</button>

<button style="background-color: #ff9800; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;" onclick="featureAction('wishlist')">Wishlist Management</button>

<button style="background-color: #9c27b0; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;" onclick="featureAction('cart')">Cart Management</button>

<button style="background-color: #3f51b5; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;" onclick="featureAction('payment')">Payment Gateway</button>

<button style="background-color: #009688; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;" onclick="featureAction('profile')">Profile Management</button>

<button style="background-color: #e91e63; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;" onclick="featureAction('update')">Personal Info Update</button>

<button style="background-color: #607d8b; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;" onclick="featureAction('product')">Product Details</button>

<button style="background-color: #795548; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;" onclick="featureAction('purchase')">Buy & Add to Cart</button>

<button style="background-color: #673ab7; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;" onclick="featureAction('orders')">Order Tracking</button>

</div>

<div id="featureOutput" style="margin-top: 20px; font-family: monospace; white-space: pre-wrap; background-color: #f4f4f4; padding: 10px; border-radius: 5px; min-height: 50px;"></div>

<script>
function featureAction(feature) {
    let output = '';
    switch(feature) {
        case 'signup':
            output = 'Triggering secure OTP email verified signup process...';
            break;
        case 'login':
            output = 'Handling user login, signup, and logout authentication...';
            break;
        case 'ajax':
            output = 'Performing AJAX requests for seamless data retrieval...';
            break;
        case 'wishlist':
            output = 'Managing wishlist additions and removals...';
            break;
        case 'cart':
            output = 'Managing shopping cart operations...';
            break;
        case 'payment':
            output = 'Processing payments via Cashfree gateway...';
            break;
        case 'profile':
            output = 'Accessing and updating user profile information...';
            break;
        case 'update':
            output = 'Updating personal info and mobile number...';
            break;
        case 'product':
            output = 'Enhancing product details with dynamic effects...';
            break;
        case 'purchase':
            output = 'Facilitating buy now and add to cart options...';
            break;
        case 'orders':
            output = 'Tracking basic order statuses...';
            break;
        default:
            output = 'Unknown feature selected.';
    }
    document.getElementById('featureOutput').textContent = output;
}
</script>

---


### How to connect buttons to code

- The buttons above are simple HTML buttons with inline CSS for styling.
- Each button has an `onclick` event that calls the JavaScript function `featureAction` with a feature identifier.
- You can replace the `featureAction` function's switch cases with actual code to connect to backend APIs or frontend logic.
- For example, you can make AJAX calls inside the function or trigger UI changes.
- The output area below the buttons shows the current action message.
- To integrate with backend, use JavaScript `fetch` or `XMLHttpRequest` to call your PHP endpoints.
- For frontend logic, you can manipulate DOM elements or trigger other JavaScript functions.

If you want, I can help you implement specific feature connections or provide example code snippets for integration.


**Author:** Goli Harini ❤️

---