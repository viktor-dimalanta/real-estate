## Real Estate Management System (REMS)
REMS is a Laravel Project that helps you to manage small or medium Real Estate business.

### Frameworks
1. Laravel
2. Materialize
3. Admin BSB Material Design

### Modules

Property Listings: Allows users to create and manage property listings with details such as location, features, and images.

Tenant Management: Tracks tenant information, lease agreements, and communication with tenants.

Lease Management: Manages lease agreements, tracks lease terms, and automates rent calculations.

Financial Management: Handles financial transactions, rent collection, expenses, and generates financial reports.

Maintenance Tracking: Monitors property maintenance schedules, requests, and work orders.

Document Management: Stores and organizes important documents related to properties, leases, and transactions.

Reporting and Analytics: Provides insights through reports on property performance, occupancy rates, and financial metrics.

Communication Tools: Facilitates communication between property managers, tenants, and other stakeholders.

Integration: Allows integration with other systems such as accounting software or CRM for seamless workflow.

User Access Control: Manages access levels for different users based on their roles and responsibilities.

### Admin Features
1. Tags
2. Categories
3. Posts
4. Features
5. Properties
6. Sliders
7. Testimonials
8. Galleries
9. Settings
    1. Profile
    2. Message
    3. Change Password
    4. General Setting

### Agent Features
1. Properties (CRUD)
2. Settings
    1. Profile
    2. Message
    3. Change Password

### User Features
1. Comments
2. Property Rating
3. Settings
    1. Profile
    2. Message to Agent
    3. Change Password


### Install
01. `git clone https://github.com/parvez-git/real-estate.git`
02. `cd real-estate`
03. `composer install`
04. `cp .env.example .env`
05. `php artisan key:generate`
06. `php artisan migrate`
07. `php artisan db:seed`
08. `php artisan storage:link`
09. `php artisan serve`

#### Cridentials
01. 
    Email: `admin@admin.com` 
    Password: `123456`
02. 
    Email: `agent@agent.com` 
    Password: `123456`
03. 
    Email: `user@user.com` 
    Password: `123456`


### Screenshot

<img src="https://github.com/parvez-git/real-estate/blob/master/public/demo/home.jpg">
