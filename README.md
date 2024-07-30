# NoteKeeper

NoteKeeper is a simple note-taking application built using Flutter. It allows users to create, edit, delete, and prioritize notes. The application uses SQLite for local data storage and provides a clean and user-friendly interface.

## Introduction

NoteKeeper is designed to help users keep track of their notes easily. With features such as adding, editing, and deleting notes, as well as setting priority levels, this application is a practical tool for everyday use.

## Features

- **Add Note**: Create a new note with a title, description, and priority level.
- **Edit Note**: Modify the details of an existing note.
- **Delete Note**: Remove a note from the database.
- **Prioritize Note**: Set the priority of a note to either High or Low.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/NoteKeeper.git
    cd NoteKeeper
    ```

2. **Install Flutter**: If you haven't already, install Flutter by following the instructions on the [official Flutter website](https://flutter.dev/docs/get-started/install).

3. **Install dependencies**:
    ```sh
    flutter pub get
    ```

4. **Run the application**:
    ```sh
    flutter run
    ```

## Usage

### Adding a Note

1. Click the floating action button (FAB) on the home screen.
2. Enter the title, description, and select the priority of the note.
3. Click "Save" to add the note to the database.

### Editing a Note

1. Tap on a note from the list to open the detail view.
2. Modify the title, description, or priority.
3. Click "Save" to update the note in the database.

### Deleting a Note

1. Swipe a note from the list to reveal the delete icon.
2. Tap the delete icon to remove the note from the database.


### Main Files

- `main.dart`: Entry point of the application. Sets up the main widget and home screen.
- `note.dart`: Defines the Note data model.
- `database_helper.dart`: Contains the SQLite database helper class.
- `note_list.dart`: Displays the list of notes.
- `note_detail.dart`: Provides the interface to add/edit notes.
- `status_change.dart`: Provides the interface to change the status of a note.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to adjust any section as needed. This README file provides a comprehensive overview of the project, including installation steps, usage instructions, and a brief description of the main files and features.



