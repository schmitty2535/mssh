# mssh - Manage SSH Sessions

`mssh` is a command-line tool designed to simplify the management of SSH sessions, allowing users to easily add, delete, and connect to SSH servers. With a user-friendly interface, `mssh` streamlines the process of handling multiple SSH connections by providing a neat, organized list of your servers.

## Features

- **List SSH Sessions:** Display all saved SSH sessions in a tabular format, including details like server name, user@IP, port, and custom comments.
- **Add New Sessions:** Easily add new SSH sessions with details such as server name, user@IP, port, and an optional comment.
- **Delete Sessions:** Remove sessions you no longer need from the list.
- **Edit Sessions:** Modify existing session details.
- **Connect to Sessions:** Initiate an SSH connection to a selected server with a simple menu selection.

## Installation

1. Clone the repository or download the `mssh` script:

    ```bash
    git clone https://github.com/schmitty2535/mssh.git
    ```

2. Move the `mssh` script to a location in your PATH (e.g., `/usr/local/bin` or `~/bin` for macOS and Linux users):

    ```bash
    chmod +x mssh
    mv mssh /usr/local/bin/mssh
    ```

3. Ensure `mssh` is executable:

    ```bash
    chmod +x /usr/local/bin/mssh
    ```

## Usage

To start managing your SSH sessions, simply run:

```bash
mssh
```
Follow the on-screen prompts to add, delete, edit, or connect to your SSH sessions.

## Configuration

The mssh tool stores session data in a text file located at ~/.mssh_sessions. This file is automatically created and updated as you add, delete, or edit your sessions.

## Requirements

Bash 4.0 or higher.
SSH client installed on your system.

## Contributing

Contributions to mssh are welcome! Feel free to open issues for bugs or suggestions and submit pull requests with improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
