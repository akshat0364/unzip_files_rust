# Rust Unzip Tool

This Rust-based tool extracts files from a zip archive. It utilizes the `zip` crate for working with zip files.

## Code Details

The tool is implemented in Rust and uses the following key components:

- **`zip` Crate**: The `zip` crate is used for working with zip files.

- **Unzipping Algorithm**: The tool iterates through the contents of the zip archive and extracts files to the specified location.

- **Command-Line Interface (CLI)**: The tool accepts the path to the zip file as a command-line argument.

- **File Permissions**: The tool sets permissions for the extracted files based on the original zip file (Unix only).

- **Error Handling**: Proper error handling is implemented, and the tool provides informative error messages in case of issues.

- **Efficient Memory Usage**: The tool efficiently handles memory to accommodate large zip files.

## Technical Notes

- The `zip` crate provides a reliable and efficient way to work with zip archives in Rust.

- The extraction process is optimized for performance while ensuring data integrity.

- The tool gracefully handles different scenarios, such as files and directories within the zip archive.

## Usage

To use the tool, follow these general steps:

1. Clone the repository to your local machine.

2. Navigate to the project directory.

3. Build the tool using `cargo`.

4. Run the tool with the path to the zip file.


