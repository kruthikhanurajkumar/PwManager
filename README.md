
## Password Manager for MergeFest Event

A CLI-based password manager built in Python.

### Setup Instructions

1. **Fork the repository** and clone it:
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```
2. **Set up SSH** for GitHub to commit changes.
3. **Ensure Python 3 is installed**:
    ```bash
    python3 --version
    ```
4. **Install dependencies**:
    ```bash
    pip install cryptography
    ```
5. **Run the application**:
    ```bash
    python3 main.py
    ```

### Features
- Encrypt and store passwords
- Generate and load encryption keys
- File-based password storage

### Requirements
- Python 3.x
- `cryptography` library

### How to Use

1. **Start the program**:
    ```bash
    python3 main.py
    ```

2. **Menu options**:
    - `1`: Create a new key
    - `2`: Load an existing key
    - `3`: Create a new password file
    - `4`: Load an existing password file
    - `5`: Add a new password
    - `6`: Retrieve a password
    - `q`: Quit

### Example Usage

- **Create a new key**:
    ```
    Enter choice: 1
    Enter key file path: keyfile.key
    ```

- **Add a password**:
    ```
    Enter choice: 5
    Enter site: gmail
    Enter password: mypassword
    ```

- **Get a password**:
    ```
    Enter choice: 6
    Enter site: gmail
    Password for gmail is mypassword
    ```

### Security Note
- Keep your encryption key safe. Without it, passwords cannot be decrypted.
