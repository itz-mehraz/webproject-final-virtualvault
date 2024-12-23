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

Follow these steps to set up the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/itz-mehraz/webproject-final-digitaldhuniya.git
cd webproject-final-digitaldhuniya
2. Install Dependencies
Install the required PHP and JavaScript dependencies:

bash
Copy code
composer install
npm install
3. Configure the Environment
Copy the example environment file and update it with the correct database credentials and payment API keys:

bash
Copy code
cp .env.example .env
4. Run Database Migrations
Migrate the database:

bash
Copy code
php artisan migrate
5. Seed the Database (Optional)
Populate the database with sample data:

bash
Copy code
php artisan db:seed
6. Build Frontend Assets
Compile the frontend assets using Vite:

bash
Copy code
npm run dev
7. Serve the Application
Start the development server:

bash
Copy code
php artisan serve
Your application should now be running locally.

yaml
Copy code

---

This version is clean, concise, and well-structured with clearly separated steps. Let me know if you need further tweaks!
