# Fam3_CLI

A simple command-line interface (CLI) application to manage and generate files containing family tree information.

## Features

- Add individuals to the family tree
- Save family tree information to a JSON file
- Load family tree information from a JSON file

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/family-tree-cli.git
    cd family-tree-cli
    ```

2. Ensure you have Python 3 installed.

## Usage

### Add a Person

To add a person to the family tree:
```sh
python family_tree.py add "John Doe" "1980-01-01"
```

Optional: Include a death date:
```sh
python family_tree.py add "John Doe" "1980-01-01" --death_date "2050-01-01"
```

### Save Family Tree

To save the current family tree to a file:
```sh
python family_tree.py save family_tree.json
```

### Load Family Tree

To load a family tree from a file:
```sh
python family_tree.py load family_tree.json
```

## License

This project is licensed under the MIT License.

---

This README provides a quick overview of the project, installation steps, and basic usage instructions. Adjust the repository URL and license information as needed.
