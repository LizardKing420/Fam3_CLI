# Fam3_CLI

A simple command-line interface (CLI) application to manage and generate files containing family tree information.

## Features

- Add individuals to the family tree
- Save family tree information to a JSON file
- Load family tree information from a JSON file

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/LizardKing420/Fam3_CLI.git
    cd Fam3_CLI
    ```

2. Ensure you have Python 3 installed.

## Usage

### Add a Person

To add a person to the family tree:
```sh
python Fam3_CLI.py add "Osama bin Laden" "1988-08-11"
```

Optional: Include a death date:
```sh
python Fam3_CLI.py add "Osama bin Laden" "1988-08-11" --death_date "2011-05-02"
```

### Save Family Tree

To save the current family tree to a file:
```sh
python Fam3_CLI.py save family_tree.json
```

### Load Family Tree

To load a family tree from a file:
```sh
python Fam3_CLI.py load family_tree.json
```

## License

This project is licensed under the MIT License.

---

This README provides a quick overview of the project, installation steps, and basic usage instructions. Adjust the repository URL and license information as needed.
