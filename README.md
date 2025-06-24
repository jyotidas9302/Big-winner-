# Big-winner-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Big Winner - ₹50 UPI Cash</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(45deg, #ff4b2b, #ff416c);
      color: white;
      text-align: center;
      padding: 20px;
    }

    .container {
      background: white;
      color: black;
      max-width: 400px;
      margin: 40px auto;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0,0,0,0.2);
    }

    input[type="text"] {
      width: 90%;
      padding: 12px;
      margin-top: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }

    button {
      background: #6c2ed9;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 16px;
    }

    button:hover {
      background: #4d1cb3;
    }

    ol {
      text-align: left;
      margin: 20px;
    }

    .highlight {
      color: #e60000;
      font-weight: bold;
    }

    .logo {
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1 class="logo">🎉 <span style="color:#e60000;">Big</span> Winner</h1>
    <h2>AngelOne</h2>
    <p style="color: orange;"><strong>Free ₹50 UPI Cash</strong></p>

    <form onsubmit="redirectUser(event)">
      <input type="text" id="upiId" placeholder="Enter UPI ID" required>
      <button type="submit">Submit</button>
    </form>

    <h3>How To Complete Offer?</h3>
    <ol>
      <li><span class="highlight">Click on Submit</span></li>
      <li><span class="highlight">Download and open the app</span></li>
      <li><span class="highlight">Register with your mobile no</span></li>
    </ol>
  </div>

  <script>
    function redirectUser(event) {
      event.preventDefault();
      const upi = document.getElementById("upiId").value.trim();
      if (upi) {
        // 🔁 Replace this with your app link or redirection page
        window.location.href = "https://yourappdownloadlink.com";
      }
    }
  </script>
</body>
</html>
