<div>
  <img style="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&section=header&reversal=true&text=Event%20Management%20System&fontSize=50&fontColor=FFFFFF&fontAlign=50&fontAlignY=50&stroke=-&descSize=20&descAlign=50&descAlignY=50&textBg=false&color=gradient"  />
</div>

###

<p align="center">The Event Management System is a web-based application developed to simplify the process of event booking and management.<br>It allows customers to browse event services, customize bookings with decorations and optional items, view pricing details, and confirm bookings.<br>Admins can efficiently manage customers, bookings, and decoration pricing.<br><br>This project was developed as part of my college academic project and to enhance practical development skills for job preparation.</p>

###

<h2 align="left">🚀 Features Overview</h2>

###

<p align="left">➺ User-friendly event booking system<br>➺ Dynamic price calculation<br>➺ Separate Customer and Admin modules<br>➺ Secure login and session handling<br>➺ Admin management dashboard</p>

###

<h2 align="left">💻Technologies used:</h2>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="40" alt="php logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="mysql logo"  />
</div>

###

<h4 align="left">Server : XAMPP (Apache + MySQL)</h4>

###

<h2 align="left">🗄️ Database Configuration</h2>

###

<p align="left">db_connect.php<br><br>This file handles the database connection between the application and MySQL.<br>➝ Uses mysqli_connect<br>➝ Centralized DB connection<br>➝ Included in all backend files<br>➝ No UI / page output<br><br>include 'db_connect.php';</p>

###

<h2 align="left">🏠 Home Page</h2>

###

<p align="left">
  The home page is the landing page of the system.
  <br><br>
  ➜ 𝐍𝐚𝐯𝐢𝐠𝐚𝐭𝐢𝐨𝐧 𝐛𝐚𝐫: Home, About Us, Book Event, Contact, Login (dropdown with Customer Login & Admin Login).
  <br><br>
  ➜ Automatic image slider showcasing events.
  <br><br>
  ➜ About Us section describing Suma Events.
  <br><br>
  ➜ Events section displaying all event types:
  <br>
  ↳ Clicking an event redirects to Book Event page if logged in.
  <br>
  ↳ If not logged in, the user is prompted to login first.
  <br><br>
  ➺ Contact section with address, email, and phone number.
</p>

###
<img src="Screenshots/Home1.png" alt="Home Page"/>
<img src="Screenshots/Home2.png" alt="Home Page"/>
<img src="Screenshots/Home3.png" alt="Home Page"/>
<img src="Screenshots/Home4.png" alt="Home Page"/>

###

<h2 align="left">🔐 Login Page</h2>

###

<p align="left">➜ Customers can register or login.<br>➜ Form validation ensures correct input.<br>➜ Secure sessions store user data.<br><br>➜ After login:<br>↳ Redirects to home.php<br>↳ Navbar shows "Hi, [Username]"<br>↳ Dropdown options: Dashboard, My Bookings, Profile, Logout</p>

###

<img src="Screenshots/Login1.png" alt="Sign In Login" width="500"/> <img src="Screenshots/Login2.png" alt="Sign Up Login" width="500"/>
###

<h2 align="left">👤 Customer Dashboard</h2>

###

<p align="left">Redirected here after login.<br><br>➜ Overview: Shows upcoming bookings and past events.<br>➜ Navigation: Home, Book Event, My Bookings, Profile, Logout<br>➜ Quick Actions: Option to book a new event directly from the dashboard.</p>

###
<img src="Screenshots/Customer_dashboard.png" alt="Customer Dashboard" width="700"/>

###

<h2 align="left">📅 Book Event Page</h2>

###

<p align="left">➜ Core booking functionality of the system.<br><br>➜ Event selection: Date, time, and time period<br>↳ Time restriction: 06:00 AM – 10:00 PM<br>↳ Daily booking limit: Maximum 3 bookings per day<br><br>➜ Event type selection: Displays related decorations with prices.<br><br>➜ Decoration selection: Choose decorations based on event type.<br><br>➜ Optional items: Chairs, Shamiyana, Speaker, Lighting<br><br>➜ Dynamic price calculation based on selected items and quantity.<br><br>➜ Address field for event location.<br><br>➜ Total amount displayed before proceeding.</p>

###
<img src="Screenshots/Book_event1.png" alt="Book Eevent" width="800"/>
<img src="Screenshots/Book_event2.png" alt="Book Event" width="800"/>

###

<h2 align="left">📤 Submit Booking</h2>

###

<p align="left">➜ Processes all booking form data.<br>➜ Stores event, decoration, optional items, and price details in the database.<br>➜ Redirects the customer to the Confirm Booking page.</p>

###

<h2 align="left">✅ Confirm Booking</h2>

###

<p align="left">➜ Allows customers to review booking details before final submission.<br><br>➜ Displays:<br>↳ Event details<br>↳ Selected decorations<br>↳ Optional items<br>↳ Total price summary<br><br>➜ On clicking Confirm Booking, a popup message appears:<br>“Your booking is confirmed.”</p>

###

<img src="Screenshots/Confirm_booking.png" alt="Confirm Booking" width="700"/>

###

<h2 align="left">📋 My Bookings</h2>

###

<p align="left">➜ Allow customer to view all booked events with full details.<br>➜ Shows date, time, decorations, optional items, amount, and status.<br>➜ Provides a Cancel Booking option for active bookings.<br>➜ Include a Back button to return to dashboard.</p>

###

<img src="Screenshots/My_bookings.png" alt="My Bookings" width="700"/>

###

<h2 align="left">👤 Customer Profile</h2>

###

<p align="left">Allows customers to view their personal profile details.</p>

###

<img src="Screenshots/Customer_profile.png" alt="Customer Profile" width="500"/>


###

<h2 align="left">🔐 Admin Login</h2>

###

<p align="left">➜ Provides a secure login for admin users.<br>➜ Accessible from the Login dropdown on the Home page.<br>➜ Uses username and password authentication.<br>➜ After successful login, the admin is redirected to the Admin Dashboard.</p>

###

<img src="Screenshots/Admin_login.png" alt="Admin Login" width="500"/>

###

<h2 align="left">📊 Admin Dashboard</h2>

###

<p align="left">➜ Main control panel for the admin.<br><br>➜ Top navigation bar includes:<br>↳ Manage Bookings<br>↳ Manage Decorations<br>↳ Customers<br>↳ Logout<br><br>➜ Dashboard overview section displays:<br>↳ Total bookings<br>↳ Upcoming events<br>↳ Registered customers<br><br>➜ Provides quick action buttons to:<br>↳ View all bookings<br>↳ Manage decorations<br>↳ View customer list</p>

###

<img src="Screenshots/Admin_dashboard.png" alt="Admin Dashboard" width="700"/>

###

<h2 align="left">📦 Manage Bookings</h2>

###

<p align="left">➜ Allows the admin to view and manage all customer bookings.<br>➜ Navigation buttons:<br>↳ Back to Dashboard <br>↳ Logout<br><br>➜ 𝐁𝐨𝐨𝐤𝐢𝐧𝐠 𝐨𝐯𝐞𝐫𝐯𝐢𝐞𝐰: Categorized by Today’s bookings, Upcoming bookings, and Expired bookings.<br><br>➜ Each booking displays:<br>↳ Customer name and details<br>↳ Event date & time<br>↳ Event type and extra decorations<br>↳ Total price and event address<br>↳ Action button to delete or modify bookings.</p>

###
<img src="Screenshots/Manage_bookings.png" alt="Manage Bookings" width="700"/>

###

<h2 align="left">🎨 Manage Decorations</h2>

###

<p align="left">➜ Allows admin to Add, Update, or Delete decorations.<br><br>➜ Add new decoration:<br>↳ Select Event Type from dropdown<br>↳ Upload Decoration image<br>↳ Enter Price and click Add Decoration<br><br>➜ Manage existing decorations:<br>↳ View all decorations with images and prices<br>↳ Buttons to Update or Delete each decoration</p>

###


<img src="Screenshots/Manage_decorations.png" alt="Manage Decoration" width="700"/>

###

<h2 align="left">👥 Customer Details</h2>

###

<p align="left">➜ Allows admin to view all registered customers.<br>➜ Displays customer information:<br>  ↳ Name<br>  ↳ Email<br>  ↳ Phone number<br>➜ Admin can also access each customer’s booking history.</p>

###


<img src="Screenshots/Customer_details.png" alt="Customer Details" width="700"/>

###

<h2 align="left">🚪 Logout</h2>

###

<p align="left">➜ Destroys the active session.<br>➜ Logs out both Customer and Admin users.<br>➜ Redirects to the Home page.</p>

###

<h2 align="left">🗄️ Database Setup</h2>

###

<p align="left">The Event Management System uses MySQL as its database.</p>

###

<p align="left">𝐃𝐚𝐭𝐚𝐛𝐚𝐬𝐞 𝐅𝐢𝐥𝐞</p>

[Database File](Database/Event_Management.sql)

###

<p align="left">𝐓𝐚𝐛𝐥𝐞𝐬 𝐎𝐯𝐞𝐫𝐯𝐢𝐞𝐰:<br>1. customer → Stores customer information like name, email, password, and contact details.<br>2. decoration → Stores decoration types, optional items, and their prices.<br>3. bookings → Stores all booking details including customer, event, selected decorations, optional items, date, time, and total price.<br><br>How to Setup<br><br>1. Open 𝐩𝐡𝐩𝐌𝐲𝐀𝐝𝐦𝐢𝐧.<br>2. Create a new database (e.g., event_management).<br>3. Import the event_management.sql file.<br>4. Ensure the db_connect.php file contains the correct database name, username, and password.</p>

###

<h3 align="left">ER Diagram</h3>

###

<p align="left">It is recommended to include an ER diagram to visualize relationships:<br><br>★ customer → bookings (One-to-Many)<br>★ decoration → bookings (Many-to-Many via booking details)</p>

###

<img src="Screenshots/ER_diagram.png" alt="ER Diagram" width="400"/>

###

<h2 align="left">▶️ How to Run the Project</h2>

###

<p align="left">1. Install 𝐗𝐀𝐌𝐏𝐏 on your system.<br>2. Start 𝐀𝐩𝐚𝐜𝐡𝐞 and 𝐌𝐲𝐒𝐐𝐋 from the XAMPP control panel.<br>3. Copy the project folder to:<br><br>   C:\xampp\htdocs\<br>   <br>4. Import the database using phpMyAdmin<br>(event_management.sql file).<br>5. Open a browser and go to:<br><br>   http://localhost/Event Management/</p>

###

<h2 align="left">📌 Conclusion</h2>

###

<p align="left">This Event Management System demonstrates real-world usage of PHP, MySQL, and session management, providing separate dashboards for customers and administrators.<br>It helped me strengthen my backend development skills and understand complete project flow from UI to database.</p>

###
