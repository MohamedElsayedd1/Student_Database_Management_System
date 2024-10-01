# Student Database Management System

A simple **Student Database Management System** built in C, which allows you to perform basic operations like **CRUD (Create, Read, Update, Delete)** along with additional functionalities such as sorting, reversing, and swapping student records.

## Features

- **Add a student** to the beginning or end of the list.
- **Delete a student** by their ID.
- **Search** for a student by ID.
- **Sort** students by their IDs.
- **Reverse** the student list.
- **Swap** two students' records by their IDs.
- **Retrieve** the Nth student from either the beginning or the end of the list.

## Project Structure

- `StudentDataBase.c`: Contains all the core functions for student data management.
- `StudentDataBase.h`: Header file declaring the functions and data structures used in the project.
- `main.c`: The driver program that executes the various functionalities of the system.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/StudentDatabaseSystem.git
   ```

2. Compile the code:

   ```bash
   gcc main.c StudentDataBase.c -o student_database
   ```

3. Run the executable:

   ```bash
   ./student_database
   ```

## Usage

1. You can choose to add students to the database.
2. Sort the list of students by their IDs.
3. Perform operations such as reversing, searching, and swapping records.
4. View the entire student list or individual students by ID.

## Example

```bash
Enter 1 to add student
Enter 2 to delete student by ID
Enter 3 to search student by ID
Enter 4 to sort students by ID
Enter 5 to reverse student list
Enter 6 to display all students
Enter 0 to exit
```

## Future Enhancements

- Add file persistence for saving and loading student data.
- Implement additional sorting and filtering features.

## Contributions

Feel free to fork the repository, make your contributions, and create pull requests. All contributions are welcome!

## License

This project is open-source and available under the MIT License.

