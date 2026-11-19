# Blood Bank Management System

A desktop application written in **Python (Tkinter)** to search and manage blood groups, donors and available blood units. Made as a Data Structures and Algorithms (DSA) project for B.Tech Computer Science, Semester III.

Supports **SDG 3 – Good Health and Well-being**.

## Features

- Password-protected **admin dashboard** (visitors get a view-only mode)
- Dashboard with summary cards and a stock bar chart
- Add, edit, delete, search and sort donors
- Track units of all 8 blood groups with Low / Out-of-stock status
- Blood request queue (first-come-first-served)
- Undo for stock changes
- Change admin password from Settings

## DSA concepts used

| Feature | Data structure / algorithm |
|---|---|
| Donor records | Singly linked list |
| Blood stock | Hash table (dictionary) |
| Blood requests | Queue (`collections.deque`) |
| Undo | Stack |
| Sort donors by name | Bubble sort |
| Search donor by name | Binary search |
| Search donors by blood group | Linear search |

## How to run

1. Install Python 3 (or install [Thonny](https://thonny.org), which includes Python and Tkinter).
2. Download `blood_bank_admin.py`.
3. Open it in Thonny and press the green **Run** button, or run:

   ```
   python blood_bank_admin.py
   ```

No extra libraries are needed.

## Login

| Role | Username | Password |
|---|---|---|
| Admin | `admin` | `admin123` |
| Visitor | – | Click **Continue as Visitor** |

The password can be changed from the **Settings** page after logging in.

## Limitations

- Data is stored in memory and is lost when the program is closed.
- The password is stored as plain text in the program.

## Author

Your Name – B.Tech CSE, Semester III
