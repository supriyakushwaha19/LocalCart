# Local Market Online Store
## Local Online Stores for Small Vendors & Artisans

> **Website Name:** Local Market Online Store  
> **Tagline:** Supporting Small Vendors, Growing Local Businesses!  
> **Color Theme:** Vibrant Forest & Emerald Green with Fresh White Accents  
> **Technologies Used:** Semantic HTML5, CSS3 (Custom Properties & Responsive Layouts), Vanilla JavaScript (ES6+), HTML5 Web Storage API (`localStorage`).

---

## 📖 Project Overview

**Local Market Online Store** is a clean, modern, client-side web application. 

The website provides a digital platform for local neighborhood merchants, farm producers, artisanal bakers, and small shopkeepers to showcase their products, receive orders, and interact with conscious local consumers without corporate middleman fees.

---

## 🎯 Key Project Features

### 1. Preservation of Original Website Identity & 6 Original Products
The website maintains its core identity and preserves the exact six original products with their original vendors and prices:
1. **Fresh Vegetables** — ₹50/kg — *Green Farm*
2. **Fresh Bread** — ₹40/packet — *Local Bakery*
3. **Fresh Milk** — ₹60/litre — *Dairy Corner*
4. **Fresh Fruits** — ₹80/kg — *Fruit Basket*
5. **Homemade Snacks** — ₹100/box — *Tasty Treats*
6. **Water Bottles** — ₹120 each — *Daily Needs Shop*

### 2. Directory of 20 Local Vendors
Includes all 20 unique community merchants with descriptions, owner profiles, ratings, contact info, and dedicated storefronts:
1. **Green Farm** — Vegetables
2. **Local Bakery** — Bakery Products
3. **Dairy Corner** — Dairy Products
4. **Fruit Basket** — Fruits
5. **Tasty Treats** — Snacks and Sweets
6. **Daily Needs Shop** — Household Essentials
7. **Sharma Grocery Store** — Groceries and Pulses
8. **Fresh Mart** — Packaged Food
9. **Sweet Delight** — Sweets and Desserts
10. **Spice Garden** — Spices and Masalas
11. **Organic Harvest** — Organic Products
12. **Farm Fresh Eggs** — Eggs and Poultry Products
13. **Flower Valley** — Flowers and Plants
14. **Style Street** — Clothing
15. **Trendy Footwear** — Shoes and Sandals
16. **Craft Corner** — Handmade Crafts
17. **Home Essentials** — Kitchen and Household Items
18. **Book World** — Books and Stationery
19. **Mobile Accessories Hub** — Mobile Accessories
20. **Gift Gallery** — Gifts and Decorative Items

### 3. Extensive 85+ Product Catalogue
Over **88 products** across 18 categories, including all items specified in the prompt:
- **Vegetables:** Tomatoes, Potatoes, Onions, Carrots, Spinach, Capsicum
- **Fruits:** Apples, Bananas, Mangoes, Oranges, Grapes, Pomegranates
- **Dairy:** Curd, Paneer, Butter, Cheese, Buttermilk
- **Bakery:** Brown Bread, Cookies, Chocolate Cake, Muffins, Biscuits
- **Groceries:** Rice, Wheat Flour, Sugar, Cooking Oil, Lentils, Salt
- **Snacks & Sweets:** Samosa, Sweets Box, Namkeen, Homemade Laddoo, Chips, Roasted Peanuts, Gulab Jamun, Kaju Katli
- **Spices:** Turmeric Powder, Red Chilli Powder, Coriander Powder, Garam Masala, Cumin Seeds, Black Pepper
- **Clothing & Footwear:** Cotton T-Shirt, Casual Shirt, Traditional Kurta, Cotton Scarf, Casual Sandals, Everyday Shoes, Slip-on Loafers
- **Home & Kitchen:** Storage Container, Lunch Box, Coffee Mug, Kitchen Towel, Decorative Lamp, Floor Cleaner
- **Books, Crafts & Gifts:** Notebook, Pen Set, Drawing Book, Handmade Greeting Card, Decorative Plant Pot, Gift Hamper, Terracotta Vase, Scented Candle Set
- **Additional Categories:** Brown Eggs, White Eggs, Kadaknath Desi Eggs, Rose Bouquet, Jasmine Garland, Money Plant, Snake Plant, USB-C Fast Charger Cable, 20W Power Adapter, Tempered Glass, Wild Honey, A2 Cow Ghee, Green Tea, Rolled Oats, Instant Noodles, Tomato Ketchup, Mixed Fruit Jam, Corn Flakes.

### 4. Complete 9-Page Architecture
1. `index.html` — Homepage with Hero, Category Grid, Featured Products, Popular Vendors, Recent Arrivals, Special Offers, and Why Shop Local.
2. `products.html` — Searchable and multi-filterable catalog with Category, Vendor, Min/Max Price, and Sort options (Price Low/High, Alphabetical, Rating).
3. `product-details.html` — Individual product specification view, quantity picker, add-to-cart, and related items.
4. `vendors.html` — 20-vendor searchable and category-filtered directory with live product counts.
5. `vendor-details.html` — Individual vendor profile, owner details, address, ratings, and exclusive vendor catalog.
6. `cart.html` — Persistent shopping cart with item removal, quantity updates, subtotal, delivery tiers (Free above ₹500), student discount promo code (`LOCAL10`), and grand totals.
7. `about.html` — Project background, vendor support context, architecture, and mission.
8. `contact.html` — Client-side validated contact form, support channels, and interactive FAQ accordion.
9. `checkout.html` — Demo checkout with full name, 10-digit Indian mobile number validation, 6-digit PIN code check, order summary, simulated payment options, and animated order confirmation modal with generated Order ID.

---

## 📁 Project File Structure

```
local-market-online-store/
│
├── index.html                # Homepage
├── products.html             # All Products & Advanced Filtering
├── product-details.html      # Individual Product Page
├── vendors.html              # 20 Local Vendors Directory
├── vendor-details.html       # Individual Vendor Profile & Catalog
├── cart.html                 # Shopping Cart & Calculations
├── checkout.html             # Demo Checkout & Confirmation
├── about.html                # About Project & Mission
├── contact.html              # Contact Form & FAQ Accordion
├── README.md                 # Project Setup & Documentation
│
├── css/
│   └── style.css             # Comprehensive Responsive Stylesheet
│
└── js/
    ├── data.js               # Central Data Store (20 Vendors, 88 Products, Categories)
    ├── common.js             # Cart LocalStorage Engine, Toasts, Navbar, Fallbacks
    ├── products.js           # Multi-Filter & Search Engine
    ├── product-details.js    # Product View & Quantity Selector
    ├── vendors.js            # Vendors Directory Engine
    ├── vendor-details.js     # Vendor Profile & Exclusive Items
    ├── cart.js               # Cart View, Calculations & Coupons
    ├── contact.js            # Form Validation & FAQ Accordion
    └── checkout.js           # Checkout Validation & Order Modal
```

---

## 🚀 How to Run the Website Locally

Since the project uses pure standard **HTML5, CSS3, and Vanilla JavaScript**, it requires **no Node.js installation, no npm packages, and no backend server!**

### Option 1: Direct File Launch (Easiest)
1. Navigate to the project directory on your computer.
2. Double-click on `index.html` to open it directly in any modern web browser (Google Chrome, Microsoft Edge, Firefox, Safari).

### Option 2: Using Python's Built-in Local Static Server
If you prefer running via `localhost`:
1. Open PowerShell or Command Prompt in the project folder.
2. Run:
   ```bash
   python -m http.server 8000
   ```
3. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

### Option 3: In VS Code (Two Simple Ways)
* **Way A (One-click F5):** Press `F5` on your keyboard (or click the Run & Debug icon on the sidebar and click the Green Play button). VS Code will automatically launch `index.html` in your browser via `.vscode/launch.json`.
* **Way B (Live Server extension):** Right-click `index.html` in the file explorer and select **"Open with Live Server"** (or click "Go Live" at the bottom-right status bar). It will open `http://127.0.0.1:5500/index.html`.

---

## 🧪 Testing Checklist

- [x] **Original 6 Products:** Verified intact with original vendors and prices (Vegetables ₹50/kg, Bread ₹40/pkt, Milk ₹60/ltr, Fruits ₹80/kg, Snacks ₹100/box, Water Bottles ₹120 each).
- [x] **20 Vendors:** All 20 vendors present in `vendors.html` with accurate categories, descriptions, and direct links.
- [x] **85+ Products:** 88 products categorized, linked to correct vendors, and searchable.
- [x] **Navigation:** Navbar active states, sticky header, mobile drawer menu, and footer links all operational.
- [x] **Multi-filtering:** In `products.html`, search + category + vendor + price range + sorting operate seamlessly simultaneously.
- [x] **Shopping Cart:** Add from any page, increment/decrement quantity, remove items, clear cart, persistent in `localStorage`.
- [x] **Promo Code:** Coupon `LOCAL10` gives 10% discount on order subtotal.
- [x] **Demo Checkout:** Validates 10-digit mobile number, 6-digit PIN code, required fields, generates simulated Order ID (`LMO-2026-XXXXXX`).
- [x] **Contact Form:** Validates name, email, message length, and displays success toast.

---

## 🌿 Project Standards

This project emphasizes clean code structure, semantic HTML5 accessibility, mobile responsiveness, and client-side web application principles.
