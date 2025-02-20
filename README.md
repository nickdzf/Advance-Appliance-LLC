<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advance Appliance LLC</title>
    <meta name="description" content="">
    
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        body {
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
        }
        .header {
            background: linear-gradient(90deg, #ff7e5f, #feb47b);
            color: white;
            padding: 2rem;
        }
        .container {
            max-width: 1100px;
            margin: 2rem auto;
            padding: 2rem;
            background: white;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
        }
        .button {
            background: #ff5722;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 1.2rem;
            cursor: pointer;
            transition: 0.3s;
        }
        .button:hover {
            background: #e64a19;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 1rem;
            margin-top: 2rem;
        }
        .brand-logos {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        .brand-logos img {
            max-width: 150px;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Advance Appliance LLC</h1>
        <p>Your trusted partner for appliance installation, repair, sales, and pick-up services in Contra Costa, California.</p>
    </div>
    
    <div class="container">
        <h2>About Us</h2>
        <p>Advance Appliance LLC is committed to providing top-notch appliance services, including installation, repair, sales of quality used appliances, and hassle-free appliance pick-up. We pride ourselves on reliability and excellent customer service. Serving Contra Costa, California.</p>
        
        <h2>Our Services</h2>
        <p><strong>Installation:</strong> Professional installation for all types of appliances. <span style="color: #ff5722; font-weight: bold;">Starts at $85</span></p>
        <p><strong>Repair:</strong> Fast and reliable repair services. <span style="color: #ff5722; font-weight: bold;">Service Fee $85</span></p>
        <p><strong>Used Appliance Sales:</strong> High-quality, affordable used appliances. <span style="color: #ff5722; font-weight: bold;">Make an Offer</span></p>
        <p><strong>Appliance Pick-Up:</strong> Convenient removal of old or unwanted appliances. <span style="color: #ff5722; font-weight: bold;">Let us know what you got!</span></p>
        
        <h2>Used Appliances for Sale</h2>
        <p>Check out our selection of fully functional and affordable used appliances. Click below to view our inventory:</p>
        <button class="button" onclick="window.open('https://www.facebook.com/profile.php?id=61570871977173', '_blank');">Inventory</button>
        
        <h2>Brands We Work With</h2>
        <div class="brand-logos">
           <img src="assets/images/samsung-logo.jpg" alt="Samsung" width="150">
          <img src="assets/images/whirlpool-logo.jpg" alt="Samsung" width="150">
         <img src="assets/images/smeg-logo.jpg" alt="Samsung" width="150">
          <img src="assets/images/siemens-logo.jpg" alt="Samsung" width="150">
          <img src="assets/images/liebherr-logo.jpg" alt="Samsung" width="150">
          <img src="assets/images/gorenje-logo.jpg" alt="Samsung" width="150">
         <img src="assets/images/electrolux-logo.jpg" alt="Samsung" width="150">
        </div>
        
        <h2>Our Service Area</h2>
        <p>We proudly serve Contra Costa, California. Check out the map below for our coverage area:</p>
        <img src="https://uscountymaps.com/wp-content/uploads/Contra-Costa-County-Map-California.jpg" alt="Service Area Map" style="max-width: 100%; height: auto; border-radius: 10px;">
    </div>
    
    <footer>
        <p>&copy; 2025 Advance Appliance LLC. Serving Contra Costa, California.</p>
    </footer>
</body>
</html>
