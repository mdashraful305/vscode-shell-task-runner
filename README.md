# VSCode Task for Compiling and Running a Bash Script

This project contains a VSCode `tasks.json` configuration that enables you to easily compile and run a shell script with an input file and save the output to an output file. This setup is useful for automating tasks where an input file is required, and results are stored in a designated output file.

## Prerequisites

- VSCode installed
- Shell access on your system
- `input.txt` file created in your workspace

## How It Works

The task in `tasks.json`:
1. Grants execute permissions to the selected file.
2. Executes the file with input redirection from `input.txt` and output redirection to `output.txt`.

### Steps to Use

1. Clone this repository to your local environment.
2. Open the project in VSCode.
3. Ensure you have an `input.txt` file in the root of your workspace.
4. Press `Ctrl+Shift+B` to trigger the "Compile and run" task.

The task will silently compile and run the current file, using `input.txt` as input and saving the results in `output.txt`.

### Notes

- Modify `input.txt` to change the input parameters.
- View `output.txt` after running the task to check the results.
- Customize the task by editing the `tasks.json` file.

## File Structure
```plaintext
├── dir1
│   ├── file11.sh
│   └── file12.sh
├── dir2
│   ├── file21.sh
│   ├── file22.sh
│   └── file23.sh
├── dir3
├── input.txt
└── output.txt
```
## License

This project is licensed under the MIT License - see the LICENSE file for details.

