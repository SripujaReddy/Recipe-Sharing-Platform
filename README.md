# Recipe Sharing Platform
## 📌 Overview
The **Recipe Sharing Platform** is a web-based application that allows users to discover, upload, and share recipes online. It fosters a community of cooking enthusiasts who can contribute their own recipes, interact with others through likes and comments, and manage personal profiles.

## 💻 Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL

## 🌟 Features
### 1. **Home Page**
- Showcases featured recipes and latest uploads.
- Navigation bar to different sections of the site.

### 2. **Recipe Listing**
- Displays all available recipes in a user-friendly layout.
- Includes recipe name, short description, and image preview.

### 3. **Recipe Details**
- Full recipe information including ingredients, steps, cook time, and an image.
- Users can like and comment on recipes.

### 4. **Add Recipe**
- Logged-in users can add new recipes with:
  - Title
  - Description
  - Ingredients
  - Preparation steps
  - Cook time
  - Image upload

### 5. **User Registration & Login**
- New users can register.
- Existing users can log in to access personalized features.

### 6. **User Profile**
- Shows the user's uploaded recipes and activity.
- Allows updating of profile details.

### 7. **Search & Filter**
- Users can search recipes by name or ingredients.
- Filter recipes by categories or preparation time.

### 8. **Admin Dashboard**
- Admins can manage users and content.
- View, edit, or delete recipes and user profiles.

## 🔐 Roles
- **User:** Register, log in, upload recipes, like, and comment.
- **Admin:** Manage site content, user accounts, and handle moderation.

## ⚙️ Installation & Setup
1. Clone the repository.
2. Set up your MySQL database and import the SQL dump (if provided).
3. Configure database connection in the `config.php` file.
4. Deploy the project on a local server using XAMPP, WAMP, or any PHP-supported server.

## 📁 Project Structure
/recipe-sharing-platform ├── index.html ├── login.php ├── register.php ├── add_recipe.php ├── recipe_details.php ├── profile.php ├── admin/ │ ├── dashboard.php │ └── manage_users.php ├── assets/ │ ├── css/ │ └── js/ └── db/ └── config.php
