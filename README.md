# Votelytics

Votelytics is a database-driven project to manage and analyze elections. It includes:

- Schema creation for elections, candidates, voters, and participation
- Sample data insertion
- Analytical SQL queries to determine results and insights

## 📁 Project Structure

Votelytics/
├── DDL.sql               # SQL schema definitions
├── DataInsertion.sql     # Inserts sample data into tables
├── DRL.sql               # SELECT queries for analysis
├── ERD.jpg               # Entity-Relationship Diagram (image)
└── RelationalDiagram.pdf # Detailed relational model (PDF)


## 🛠️ Requirements
- MySQL or compatible SQL database
- SQL client (MySQL Workbench recommended)
- Image/PDF viewer for diagrams (optional)

## 🚀 Setup Instructions
1. **Clone the repository**
    ```bash
    git clone https://github.com/Manthan-Kansagara/Votelytics.git
    cd Votelytics
    ```

2. **Open MySQL Workbench**
    - Connect to your MySQL server
    - Create a new SQL tab

3. **Execute SQL files in this order:**
    - Open `DDL.sql`, copy all content, and run it  
      📌 This will create the database schema (tables, constraints, keys)
    - Open `DataInsertion.sql`, copy all content, and run it  
      📌 This will insert sample data into the tables
    - Open `DRL.sql`, copy all content, and run it  
      📌 This will run the analysis queries and show results

## 📊 Diagrams
- **ERD.jpg** – Entity-Relationship Diagram
- **RelationalDiagram.pdf** – Full relational schema with keys and relations  
  *(Open with any image or PDF viewer)*

## 🧩 Customize It
- Adjust data types if using PostgreSQL or another DBMS
- Add more entries in `DataInsertion.sql` for larger datasets
- Modify `DRL.sql` to include more queries (e.g., party analysis, turnout trends, etc.)

---

### Made with 💡 by **Manthan Kansagara**
