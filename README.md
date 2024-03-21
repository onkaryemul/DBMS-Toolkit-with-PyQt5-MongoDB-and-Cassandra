Manage and interact with your local and cloud-based databases effortlessly using this Python-based graphical user interface (GUI), supporting MongoDB Atlas, DataStax AstraDB, and local instances of MongoDB and Cassandra.


# DBMS Toolkit with PyQt5, MongoDB and Cassandra

A collection of GUI applications for managing student records using different database systems. Each application connects to a different database instance, including MongoDB Atlas, AstraDB Cassandra, local MongoDB, and local Cassandra.

Simplify database administration tasks with this versatile PyQt5 GUI application, designed to seamlessly connect to MongoDB Atlas, DataStax AstraDB, and local MongoDB/Cassandra databases, providing an intuitive interface for managing student records, data streams, and more.


## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)


## Features

- Add, delete, view, and update student records.
- Input validation for email format and phone number format.
- Error handling for database interactions.
- Connection to various database systems including MongoDB Atlas, AstraDB Cassandra, local MongoDB, and local Cassandra.


## Technologies Used

- Python
- PyQt5
- MongoDB
- Cassandra
- MongoDB Atlas
- AstraDB Cassandra


## Installation

1. **Clone the repository:**

   ```bash
      git clone https://github.com/onkaryemul/DBMS-Toolkit-with-PyQt5-MongoDB-and-Cassandra.git
   ```

2. **Navigate to the project directory:**

   ```bash
     cd DBMS-Toolkit-with-PyQt5-MongoDB-and-Cassandra
   ```
   
3. **Install dependencies:**

   ```bash
      pip install PyQt5 pymongo cassandra-driver python-dotenv
   ```


## Usage

1. **.env Configuration:**
   Create a .env file in the project root folder and set the following variables:
    
   ```env
      MONGODB_ATLAS_URI=your-mongodb-atlas-uri
      ASTRA_DB_SECURE_BUNDLE_PATH=/path/to/secure-connect-cassandradb.zip
      ASTRA_DB_APPLICATION_TOKEN=/path/to/CassandraDB-token.json
   ```   

   - Replace `your-mongodb-atlas-uri` with your actual mongodb atlas connection URL. Make sure to replace placeholders like `yourusername` and `yourpassword` in the MongoDB URI with your actual MongoDB credentials.

   - Replace `/path/to/secure-connect-cassandradb.zip` with the path to your AstraDB secure bundle and `/path/to/CassandraDB-token.json` with the path to your AstraDB application token JSON file.
      
3. **Run the desired application file:**
   
  - **For MongoDB Atlas:**
    
    ```bash
       python mongodb_atlas_gui.py
    ```
    
  - **For AstraDB Cassandra:**
    
    ```bash
       python cassandradb_cloud_gui.py
    ```
  
  - **For local MongoDB:**
    
    ```bash
       python mongodb_gui.py
    ```
    
  - **For local Cassandra:** 

    ```bash
       python cassandra_gui.py
    ```
  
4. **Use the GUI to perform CRUD operations on student records.**


## Contributing

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request. Please follow best practices and maintain code clarity.

If you would like to contribute to the project, follow these steps:

1. Fork the repository.

2. Create a new branch:

   ```bash
     git checkout -b feature/your-feature-name
   ```
   
3. Make your changes and commit:

   ```bash
     git commit -m "Add your feature"
   ```

4. Push to your branch:

   ```bash
     git push origin feature/your-feature-name
   ```
   
5. Create a pull request on GitHub.

