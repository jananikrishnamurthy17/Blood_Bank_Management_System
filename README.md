# Blood_Bank_Management_System

# Overview

The Blood Bank Management System (BBMS) represents an innovative application crafted to streamline the querying and presentation of vital blood bank data. With its intuitive interface, BBMS empowers users to effortlessly execute predetermined SQL queries, efficiently access donor details, oversee blood inventory, and delve into comprehensive data analytics using seamlessly integrated Tableau visualizations.

# Functionalities

Database Connectivity: The Database Connectivity feature of our system offers a secure and efficient means for users to access vital data stored within a MySQL database. Through this secure login process, users can seamlessly connect to the database, facilitating effortless retrieval of data critical to blood bank management.

Interactive UI: The Interactive User Interface (UI) of our system is designed to deliver a superior user experience, characterized by its cleanliness, intuitiveness, and navigability. With a focus on user-centric design principles, we have crafted an interface that minimizes complexity and maximizes usability.

PreConfigured Queries: Our system empowers users with the capability to execute a variety of common SQL queries relevant to blood bank operations, all through a user-friendly and intuitive interface. With a few clicks, users can retrieve essential information such as donor details, inventory levels, and transaction history, facilitating informed decision-making and operational efficiency.

Data Visualization: Through seamless integration with Tableau visualizations, our system offers comprehensive data analytics and reporting capabilities.  By leveraging the powerful visualization tools provided by Tableau, users can explore trends, patterns, and correlations within the blood bank data with ease. From interactive dashboards to dynamic charts and graphs, our system empowers users to communicate findings effectively and drive actionable insights.

Cool Things: Web scraping techniques were implemented to efficiently extract data from various online sources. The extracted data was seamlessly migrated to MongoDB, enabling robust data management and storage. Additionally, AWS RDS was utilized for further data migration, ensuring a scalable and secure cloud-based storage solution. This combination empowers the system to handle large volumes of data efficiently, providing a strong foundation for advanced data analysis and reporting.

# Prerequisite

Ensure that you have the following installed in your system.

1. Python 3.x
2. Tkinter, pillow, tkcalendar library
3. MySQL Connector for Python
4. Access to Tableau Public (for embedded visualizations)

# Running the application

Clone the repository to your local machine using `git clone [https://github.com/jananikrishnamurthy17/Blood-Bank-Management-System.git](https://github.com/jananikrishnamurthy17/Blood_Bank_Management_System.git)'

Navigate to the cloned directory and install the required dependencies by running pip install -r requirements.txt in your terminal.

Run the code cell in MILESTONE3code.ipynb and wait for the app to start.

Make sure you have splash_image.jpg file in your project directory.

If you’re using localhost, create the database using the MILESTONE3DUMP.sql

# Navigate the UI:

1. A login form is shown when the application starts, You can reset the form to put your credentials.
2. Tableau visualisations are shown at the top. You can click on the buttons listed
below which will take you to the corresponding visual in Tableau public.
	1. Count of Blood Bags
	2. Total Donations - Donation Camp
	3. Blood Request Trend
	4. Blood requests - each Hospital
3. You can run 6 six informational SQL queries:
	1. Blood Supply Vs Demand - Hospital
	2. Get Total Number of Donations for a Month/Day
	3. Get top donors list
	4. Total Number of Donors by Blood Group
	5. Search Donor's Information by ID
	6. Blood Group Compatibility Table




