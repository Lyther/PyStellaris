# PyStellaris Modding Assistant

Welcome to the PyStellaris Modding Assistant repository. This project is designed to facilitate modding for games developed by Paradox Interactive, specifically focusing on Stellaris. The toolset provided within this repository allows modders to convert game data between the Paradox game format and JSON, enabling easier editing and manipulation of game data.

## Features

- **JSON to Paradox Converter (`json_to_paradox`)**: A Python script that takes JSON files and converts them into a format that can be recognized by Stellaris and other Paradox games.
- **Paradox to JSON Converter (`paradox_to_json`)**: A Python script that performs the reverse operation, converting Paradox game data files into JSON format for convenient editing.

## Getting Started

To use the PyStellaris Modding Assistant, you need to have Python installed on your system. The scripts are standalone Python scripts that do not require additional dependencies.

### Prerequisites

- Python 3.6 or higher

### Usage

1. **JSON to Paradox Conversion**

    Navigate to the `json_to_paradox` directory and run the `j2p_parser.py` script with the path to the JSON file you wish to convert.

    ```bash
    cd json_to_paradox
    python j2p_parser.py <path_to_json_file>
    ```

    The script will output the converted data in the Paradox format.

2. **Paradox to JSON Conversion**

    Navigate to the `paradox_to_json` directory and run the `p2j_parser.py` script with the path to the Paradox file you wish to convert.

    ```bash
    cd paradox_to_json
    python p2j_parser.py <path_to_paradox_file>
    ```

    The script will output the JSON representation of the Paradox file.

## Contributing

Contributions to the PyStellaris Modding Assistant are welcome! If you have suggestions, bug reports, or contributions, please submit them via issues or pull requests on this repository.

## License

This project is open-source and is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- The Paradox Interactive team for creating Stellaris and supporting modding communities.
- Contributors to this project for improving the toolset.

## Disclaimer

This project is not affiliated with Paradox Interactive. Use this tool at your own risk.

---

Enjoy modding with PyStellaris! If you have any questions or need support, please open an issue in the repository.

**Happy Modding!**
