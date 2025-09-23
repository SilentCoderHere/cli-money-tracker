# CLI Money Tracker

A command-line tool to track income, expenses, and balance using SQLite.

## Features

- Add income and expense transactions
- View current balance
- List transaction history
- Simple CLI interface
- Persistent storage via SQLite database

## Installation

No installation required!  
This project does **not** use any third-party libraries.  
Just clone the repository and run the script.

```sh
git clone https://github.com/itzpremsingh/cli-money-tracker.git
cd cli-money-tracker
```

## Usage

Run the tool from the command line:
```sh
python tracker.py
```

### Example Commands

- **Add income:**
  ```sh
  python main.py add-income --amount 1000 --note "Salary"
  ```
- **Add expense:**
  ```sh
  python main.py add-expense --amount 200 --note "Groceries"
  ```
- **View balance:**
  ```sh
  python main.py balance
  ```
- **List transactions:**
  ```sh
  python main.py history
  ```

## Technologies Used

- Python (Standard Library only)
- SQLite (via Python's built-in module)

## License

This project is licensed under the MIT License.
