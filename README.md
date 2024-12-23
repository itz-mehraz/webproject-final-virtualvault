# Digital Dhuniya

Welcome to **Digital Dhuniya**, an e-commerce platform designed to sell digital products in Bangladesh. Built using **Laravel**, **PHP**, and **Vite**, this platform aims to provide a seamless, user-friendly experience for both customers and administrators. The site is fully responsive, secure, and integrates localized payment methods to suit the needs of the Bangladeshi market.

---

## **Live Site**

Explore the live version of the site and admin panel:

- **Website:** [Visit Digital Dhuniya](https://khondokar-mehraz.xyz/)
- **Admin Panel:** [Login to Admin Panel](https://khondokar-mehraz.xyz/admin/login)

(*Credentials for the admin panel can be requested for authorized personnel.*)

---

## **Features**

### **Frontend Features**

- **Digital Product Selling**  
  Sell a variety of digital products, including **Netflix**, **Amazon**, **Free Fire**, **Nintendo**, and **iTunes** gift cards, catering exclusively to the **Bangladeshi market**.

- **Responsive Design**  
  Optimized for **mobile**, **tablet**, and **desktop** devices, ensuring smooth navigation and usability across different screen sizes.

- **Localized Payment Methods**  
  Integrated with local **payment gateways** to offer secure, convenient, and region-specific transactions for Bangladeshi users.

- **Plan Selection System**  
  Users can choose from different plans based on:
  - **Duration:** Monthly, yearly, etc.
  - **Type:** Shared, personal, or other categories.

- **Advanced Category System**  
  Efficient product categorization for easier navigation, making it simpler for users to find desired items.

- **Live AJAX Search**  
  A real-time search feature with AJAX that instantly filters products based on categories and other parameters.

- **Custom Checkout Page**  
  A streamlined and user-friendly checkout process designed for Bangladeshi users, offering a hassle-free experience.

- **Mobile-Friendly Menu**  
  A mobile-optimized navigation menu for quick access to important features such as product categories, user accounts, and the shopping cart.

- **User Account System**  
  Secure user accounts with functionalities such as **order tracking**, **purchase history**, and the ability to manage personal information.

- **Review and Landing Pages**  
  Users can leave reviews on products and access promotional landing pages for marketing purposes.

---

### **Backend Features**

- **Product Management**  
  Easy management of digital products, including adding, editing, and categorizing items. Admins can also assign pricing structures (e.g., shared, personal).

- **User Management**  
  Role-based access control:
  - **Admin**: Full access to all features.
  - **Editor**: Limited access for managing specific sections.
  - Option for multi-vendor management.

- **Report Generation**  
  Detailed reports on sales, revenue, user activity, and product performance, providing insights into business operations.

- **Banner and Ad Management**  
  Admins can upload and manage banners and ads across the site for promotions and marketing campaigns.

- **Payment API Integration**  
  Integration with multiple payment APIs for flexible payment options, ensuring smooth transactions.

- **Category Management**  
  Admins can easily add and manage product categories to improve user navigation.

---

## **Technology Stack**

- **Framework:** Laravel  
- **Backend:** PHP  
- **Frontend:** Vite, Blade Templates, Bootstrap, JavaScript  
- **Database:** MySQL  
- **Version Control:** GitHub ([Repository Link](https://github.com/itz-mehraz/webproject-final-digitaldhuniya))  
- **Build Tool:** Vite

---

## **Installation Guide**

Follow the steps below to set up the project on your local machine:

---

### Step 1: Clone the Repository

```bash
git clone https://github.com/itz-mehraz/webproject-final-digitaldhuniya.git
cd webproject-final-digitaldhuniya
```

---

### Step 2: Install Dependencies

Install the required PHP and JavaScript dependencies:

```bash
composer install
npm install
```

---

### Step 3: Configure the Environment

Copy the `.env.example` file and rename it to `.env`:

```bash
cp .env.example .env
```

Next, open the `.env` file and update the following:

- **Database Configuration** (DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME, DB_PASSWORD)
- **Payment API Keys** (as per your setup)

---

### Step 4: Run Database Migrations

Run the migrations to create the necessary database tables:

```bash
php artisan migrate
```

---

### Step 5: Seed the Database (Optional)

Populate the database with sample data:

```bash
php artisan db:seed
```

---

### Step 6: Build Frontend Assets

Compile the frontend assets using Vite:

```bash
npm run dev
```

---

### Step 7: Serve the Application

Start the development server to view the project in your browser:

```bash
php artisan serve
```

Once the server is running, access the application at:

```
http://localhost:8000
```

---

🎉 **Congratulations!** Your application is now running locally.


### Why This Stands Out:
- **Copy-Paste Friendly:** Each code snippet is isolated, making it easy for anyone to copy commands directly.
- **Professional Structure:** Step numbers, headings, and spacing create a clean and clear layout.
- **Clear Instructions:** Minimal text for maximum clarity while guiding users.

This format ensures anyone reading or setting up your project can do so effortlessly. Let me know if this fits your needs better!
After copying, open .env and configure the following:

Database Configuration
Payment API Keys
Any other necessary credentials.
4. Run Database Migrations
Run the migrations to create the necessary database tables:

bash
Copy code
php artisan migrate
5. Seed the Database (Optional)
(Optional) Populate the database with sample data for testing:

bash
Copy code
php artisan db:seed
6. Build Frontend Assets
Compile the frontend assets using Vite:

bash
Copy code
npm run dev
7. Serve the Application
Start the development server to view the application in your browser:

bash
Copy code
php artisan serve
Now, your application should be up and running locally at http://localhost:8000.

You're all set! 🚀
vbnet
Copy code

### Key Improvements:
- **Clear Sections:** Each step is visually separated with lines and headings, making it easy to follow.
- **Highlighted Code Blocks:** Important commands are inside code blocks for easy copying.
- **Simplified Formatting:** The information is concise and directly to the point, helping readers navigate easily.

This format should now be more structured and visually appealing while maintaining clarity. Let me know if you need any other changes!
