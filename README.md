# Shell_Don

This project provides two Python scripts to encode and decode shell commands in various formats. The first script includes a graphical user interface (GUI) for easy use, while the second is a command-line interface (CLI) script.

## Features

- Encode shell commands to:
  - Hexadecimal
  - Base64
  - URL encoding
  - HTML encoding
  - JSON encoding
  - Markdown encoding
  - Binary encoding
  - Substitution cipher
- Generate decoding commands for each encoded format
- Preview decoding commands without executing them
- Custom decoding commands

## Installation

Ensure you have Python installed. Then, install the required packages with:

```bash
pip install -r requirements.txt
```

It should contain tk and another that you may need to install using python install instead of pip depending.

### Usage

There are two ways to use this with a GUI which has nmore features ot the CLI for quick on the go access:

### GUI Script

To launch the GUI:

```bash
Copy code
python gui_script.py --gui
```

### CLI Script

To use the CLI script:

```bash
Copy code
python cli_script.py <command> <substitution_key> [--preview] [--custom-decoding <command>]
```

### Arguments:

<command>: The shell command to encode.
<substitution_key>: The substitution cipher key (0-61).

### Options:

--preview: Preview the decoding commands without executing them.
--custom-decoding <command>: Custom decoding command. Overrides default decoding commands.

## Examples:

### Encode a command with the GUI:
Run the script with the --gui flag.
Enter your shell command and substitution key.
Click "Generate" to see the encoded formats and decoding payloads.

### Encode a command with the CLI:

```bash
Copy code
python cli_script.py "ls -la" 3 --preview
```


This will encode the command ls -la with a substitution key of 3 and display the decoding commands.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements:
Built by DeadmanXXXII.

Copy code

### Note
- Save the first script as `gui_script.py`.
- Save the second script as `cli_script.py`.

You can now use these scripts for encoding and decoding shell commands with both a graphical interface and command-line interface.

![Usage](https://raw.githubusercontent.com/DeadmanXXXII/Shell_Don/blob/main/Nethunter-use_OP_Top.png)

![Usage](https://raw.githubusercontent.com/DeadmanXXXII/Shell_Don/blob/main/Nethunter-use_OP_bottom.png)




