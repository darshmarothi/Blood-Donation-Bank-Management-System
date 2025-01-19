# Blood-Donation-Bank-Management-System
The Blood Donation Bank Management System is a Python-based project designed to manage blood donation records effectively. My team and I developed it for the AISSCE 2022 examination, it provides an easy-to-use interface for donors and patients to register, update details, and check blood availability.
The project integrates MySQL for data storage and employs libraries such as mysql.connector, Pillow, qrcode, and more for functionality and user experience.
Features:

    Donor & Patient Management: Register and update donor and patient details, including unique ID generation.
    Blood Availability Check: Check available blood types and their quantities.
    QR Code Generation: Create registration cards with scannable QR codes for easy retrieval of donor/patient details.
    User-Friendly Interface: Simple navigation through menu-based interaction.
    MySQL Integration: Seamless database connectivity for efficient data storage and retrieval.

    You can find the code and project details attached to the file "CS Report" above.

Technologies Used:

    Python: Core programming language.
    MySQL: Relational database management system.
    Pillow: For creating ID cards.
    qrcode: For generating QR codes.

Prerequisites:

    Python 3.8 or above
    MySQL Server
    Required Python libraries (install via pip install -r requirements.txt)

Getting Started:

    Clone the repository:

git clone https://github.com/your-username/blood-donation-bank.git

Navigate to the project directory:

cd blood-donation-bank

Install dependencies:

pip install -r requirements.txt

Set up the MySQL database as per the provided schema.
Run the application:

    python main.py

