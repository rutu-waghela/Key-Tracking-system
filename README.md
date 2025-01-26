# Key-Tracking-system

# Key Tracker Database System 🔑

A comprehensive database management system designed for **The Rescue Mission** in Syracuse, NY, to efficiently track, record, and manage over 700 keys for facilities, housing, stores, and donation centers. This project replaces the outdated Alpha Four database system, ensuring improved accuracy, accessibility, and data security for key tracking.

---

## 📋 Problem Statement

The Rescue Mission faced challenges with its outdated key tracking system, including:
- **Complexity**: Over 700 distinct keys for 11 housing units, 27 stores, and an administration building.
- **Data Loss**: Frequent loss of transaction records, leading to increased expenses.
- **Inefficiency**: Difficulty in tracking key assignments, returns, and inventory.

---

## 🚀 Proposed Solution

The new Key Tracker system offers:
1. **Efficient Recording**: Tracks key transactions such as creation, assignment, return, and loss.
2. **Inventory Management**: Monitors key inventory with streamlined processes.
3. **Improved Accessibility**: Provides quick access to key statuses, reducing data loss and improving user satisfaction.

---

## 💻 Features and Functions

### 1. **Key Transactions**
   - Tracks the lifecycle of each key (creation, assignment, return, loss).
   - Assigns keys to assets (doors, cabinets, vehicles, etc.).

### 2. **Documentation**
   - Records the relationship between keys and locks.
   - Tracks key blanks, codes, and bittings for accurate replication.

### 3. **Inventory Management**
   - Monitors the availability of keys and tracks lost or replaced items.

### 4. **Key and Asset Management**
   - **Function 1**: View keys assigned to an employee.
   - **Function 2**: View employees assigned to a key.
   - **Function 3**: Track detailed key specifications (stamp, blank type, hook, etc.).
   - **Function 4**: Track assets and buildings associated with keys.

---

## 📊 Data Model

The system is built on a relational database with the following entities:
- **Key**: Includes specifications such as key stamp, status, and registration details.
- **Key Holder**: Tracks employee assignments and their respective keys.
- **Building and Asset**: Manages information about buildings and associated assets.
- **Relationships**:
  - Key ↔ Asset (1:M)
  - Key ↔ Key Holder (0:M)
  - Building ↔ Asset (1:M)

---

## 🛠️ Technologies Used

- **Database**: SQL Server
- **Programming Languages**: SQL
- **Tools**: PowerApps for application interface
- **Key Features**:
  - Stored procedures and triggers for updating records.
  - Window functions for advanced queries.
  - Pivot functions for historical tracking.

---

## 🖥️ Application Screenshots

### 1. **Main Page**
- Access the list of functions: Assigned Keys, Employees, Key Specifications, and Assets & Buildings.

### 2. **Function 1: Assigned Keys**
- Input employee details to view their assigned keys.

### 3. **Function 2: Employees**
- Display all employees currently assigned keys.

### 4. **Function 3: Key Tracking**
- View detailed key data, including stamp, blank, bitting, and hook information.

### 5. **Function 4: Asset & Building Tracking**
- Search assets by ID to find related keys and their specifications.

---

## 🔍 Key Benefits

1. **Data Integrity**: Structured data model with additional and connection tables to minimize complexity.
2. **User Efficiency**: Simplified processes for recording and accessing data.
3. **Enhanced Security**: Access controls ensure only authorized personnel manage key records.

