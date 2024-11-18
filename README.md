# User Management System

## Installation

### Steps

1. **Install dependencies:**

   ```bash
   composer install
   ```

2. **Set up the database:** 2. **Set up the database:** - Create a new MySQL database. - Update the database configuration in `config/db.php`.

   3. **Run migrations:**

      ```bash
      php yii migrate
      ```

   4. **Run Role-Based Access Control (RBAC) migrations:**
      ```bash
      php yii migrate --migrationPath=@yii/rbac/migrations/
      ```

3. **Start the application:**

   ```bash
   php yii serve
   ```

4. **Access the application:**
   Open your browser and navigate to `http://localhost:8080`.

## Default Credentials

- **Admin User:**
  - Username: `admin`
  - Password: `admin123`
