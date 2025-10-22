5.  Click the green **"Commit changes"** button at the bottom.

### Step 5: Create the Configuration File

You need a configuration file to tell GitHub to use the professional theme.

1.  In your repository, click **"Add file"** and then **"Create new file."**
2.  **File name:** `_config.yml` (The underscore is mandatory).
3.  **Content to Copy and Paste:**

| **File** | **Code to Copy and Paste** |
| :--- | :--- |
| **`_config.yml`** | ```yaml
theme: jekyll-theme-architect
title: Samsung Apple Store Uganda - The Best Deals on Apple & Samsung in Kampala
description: Your official source for original New and Used Apple iPhones and Samsung Galaxy devices in Uganda. Best deals, 6-Month Warranty, and instant WhatsApp support.
``` |
4.  Click the green **"Commit new file"** button.

---

## 📝 Phase 3: Customize Content (Copy/Paste HTML)

The theme is now set up! Your main content will be pulled from the **`index.html`** file, which is what we will create now. This file contains all your specific professional details.

### Step 6: Create the Main Website Page

1.  In your repository, click **"Add file"** and then **"Create new file."**
2.  **File name:** `index.html`
3.  **Content to Copy and Paste (The Entire Page):**

This code block contains all your contact, location, business rules, and product categories already formatted professionally in simple HTML.

| **File** | **Code to Copy and Paste (It's long, but just paste it all!)** |
| :--- | :--- |
| **`index.html`** | ```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samsung Apple Store Uganda - Official Website</title>

    <style>
        body { font-family: sans-serif; line-height: 1.6; color: #333; background-color: #f4f4f4; margin: 0; padding: 0; }
        .container { width: 90%; max-width: 1200px; margin: 0 auto; padding: 20px 0; }
        header { background: #007bff; color: white; padding: 10px 0; text-align: center; }
        header a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
        h1 { color: #007bff; text-align: center; margin-bottom: 20px; }
        .product-grid { display: flex; flex-wrap: wrap; justify-content: space-around; gap: 20px; }
        .product-card { background: white; padding: 15px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); width: calc(33% - 40px); min-width: 280px; text-align: center; }
        .product-card img { width: 100%; height: 200px; object-fit: contain; margin-bottom: 10px; }
        .price { font-size: 1.5em; color: #dc3545; font-weight: bold; margin: 10px 0; }
        .status-new { background-color: #28a745; color: white; padding: 3px 8px; border-radius: 4px; font-size: 0.9em; margin-right: 5px; }
        .status-used { background-color: #ffc107; color: #333; padding: 3px 8px; border-radius: 4px; font-size: 0.9em; margin-right: 5px; }
        .cta-btn { display: block; background: #28a745; color: white; padding: 10px; text-decoration: none; border-radius: 5px; margin-top: 15px; font-weight: bold; }
        .guarantee { font-size: 0.85em; color: #6c757d; margin-top: 5px; }
        footer { background: #343a40; color: white; text-align: center; padding: 20px 0; margin-top: 40px; }
        footer a { color: #ffc107; text-decoration: none; }
        .whatsapp-float { position: fixed; bottom: 20px; right: 20px; background-color: #25D366; color: white; border-radius: 50%; width: 60px; height: 60px; text-align: center; line-height: 60px; font-size: 2em; box-shadow: 0 4px 8px rgba(0,0,0,0.2); z-index: 1000; }
        .whatsapp-float:hover { background-color: #128C7E; }
    </style>
</head>
<body>
    
    <a href="https://wa.me/256756922058?text=Hello%20Samsung%20Apple%20Store%20Uganda,%20I%20am%20interested%20in%20a%20product%20on%20your%20website." target="_blank" class="whatsapp-float">
        &#x2709; </a>

    <header>
        <div class="container">
            <a href="#">Home</a>
            <a href="#new-devices">New Devices</a>
            <a href="#used-deals">Used Deals</a>
            <a href="https://wa.me/256756922058?text=Hello%20Samsung%20Apple%20Store%20Uganda,%20I%20want%20to%20sell%20my%20device%20and%20get%20a%20quote." target="_blank">SELL / TRADE-IN</a>
        </div>
    </header>

    <div class="container">
        <h1>Welcome to Samsung Apple Store Uganda</h1>
        <p style="text-align: center; font-size: 1.2em; color: #007bff; font-weight: bold;">
            Your Official Source for Genuine iPhones & Galaxy Devices in Kampala.
        </p>

        <div style="background-color: #fff3cd; border: 1px solid #ffeeba; color: #856404; padding: 15px; margin-top: 20px; text-align: center; border-radius: 5px;">
            <h2>FLASH SALE! SAVE UGX 200,000 on Select Used iPhones!</h2>
            <p>Order today before the deals run out! Free delivery within Kampala.</p>
        </div>
        
        <h2 id="new-devices" style="margin-top: 40px; border-bottom: 2px solid #007bff;">BRAND NEW DEVICES</h2>
        <div class="product-grid">
            
            <div class="product-card">
                <img src="https://via.placeholder.com/280x200?text=iPhone+15+Pro+Max" alt="New Apple iPhone 15 Pro Max">
                <h3>Apple iPhone 15 Pro Max (256GB)</h3>
                <p class="price"><span class="status-new">NEW</span> UGX 5,500,000</p>
                <p class="guarantee">Includes 6-Month Warranty & 5-Day Guarantee (Receipt Req.)</p>
                <a href="https://wa.me/256756922058?text=I%20want%20to%20buy%20the%20NEW%20iPhone%2015%20Pro%20Max%20for%20UGX%205,500,000" target="_blank" class="cta-btn">Order on WhatsApp</a>
            </div>

            <div class="product-card">
                <img src="https://via.placeholder.com/280x200?text=Samsung+S24+Ultra" alt="New Samsung Galaxy S24 Ultra">
                <h3>Samsung Galaxy S24 Ultra (512GB)</h3>
                <p class="price"><span class="status-new">NEW</span> UGX 4,800,000</p>
                <p class="guarantee">Includes 6-Month Warranty & 5-Day Guarantee (Receipt Req.)</p>
                <a href="https://wa.me/256756922058?text=I%20want%20to%20buy%20the%20NEW%20Samsung%20S24%20Ultra%20for%20UGX%204,800,000" target="_blank" class="cta-btn">Order on WhatsApp</a>
            </div>
            
        </div>
        
        <h2 id="used-deals" style="margin-top: 40px; border-bottom: 2px solid #dc3545;">PRE-OWNED DEALS</h2>
        <div class="product-grid">
            
            <div class="product-card">
                <img src="https://via.placeholder.com/280x200?text=Used+iPhone+13+Pro" alt="Used Apple iPhone 13 Pro">
                <h3>Apple iPhone 13 Pro (128GB)</h3>
                <p class="price">
                    <span class="status-used">USED (Grade A)</span>
                    <del>UGX 3,500,000</del>
                    <span style="color: #dc3545;">UGX 3,300,000</span>
                </p>
                <p class="guarantee">Includes 6-Month Warranty & 5-Day Guarantee (Receipt Req.)</p>
                <a href="https://wa.me/256756922058?text=I%20want%20to%20buy%20the%20USED%20iPhone%2013%20Pro%20for%20UGX%203,300,000" target="_blank" class="cta-btn">Order on WhatsApp</a>
            </div>

            <div class="product-card">
                <img src="https://via.placeholder.com/280x200?text=Used+Samsung+S22" alt="Used Samsung Galaxy S22">
                <h3>Samsung Galaxy S22 (256GB)</h3>
                <p class="price"><span class="status-used">USED (Grade B)</span> UGX 2,100,000</p>
                <p class="guarantee">Includes 6-Month Warranty & 5-Day Guarantee (Receipt Req.)</p>
                <a href="https://wa.me/256756922058?text=I%20want%20to%20buy%20the%20USED%20Samsung%20S22%20for%20UGX%202,100,000" target="_blank" class="cta-btn">Order on WhatsApp</a>
            </div>
        </div>

    </div>

    <footer>
        <div class="container">
            <h3>Samsung Apple Store Uganda</h3>
            
            <p style="margin-top: 15px;">
                <strong>Location:</strong> Kisakyamaria Building, Shop B11, William Street, Opposite Gazaland, Kampala, Uganda
            </p>
            <p>
                <strong>Call / WhatsApp:</strong> 075-692-2058
            </p>
            <p>
                <strong>Email:</strong> <a href="mailto:wambuga.ivan@gmail.com">wambuga.ivan@gmail.com</a>
            </p>
            
            <p style="margin-top: 20px;">
                All products come with a **6-Month Warranty** and a **5-Day Guarantee**. Original receipt is mandatory for guarantee claims.
            </p>
            <p style="font-size: 0.8em; margin-top: 10px;">
                &copy; 2025 Samsung Apple Store Uganda. Powered by GitHub Pages.
            </p>
        </div>
    </footer>
</body>
</html>
``` |
4.  Click the green **"Commit new file"** button.

### Step 7: Wait and View Your Website

1.  Wait about **2-5 minutes**. GitHub needs this time to build the site.
2.  Go to your GitHub Pages URL (e.g., `https://[your-username].github.io/samsung-apple-store-uganda/`).

Your professional, zero-cost website is now live with all your specific business rules!
