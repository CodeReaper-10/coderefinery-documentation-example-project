# Temperature Data Logger

This is a project that takes temperature data as input from an excel sheet and displays the results accordingly.

## Motivation

Temperature data is an important aspect in a wide range of industries such as agriculture, transportation, and manufacturing. As such, there is a need for an efficient and reliable system to manage and display temperature data. This project aims to provide a solution for this need by allowing users to easily store, view and analyze temperature data from an Excel sheet. By using this project, users can make informed decisions based on the temperature data, leading to better management and control of temperature-sensitive operations. Furthermore, this project can be customized and adapted to fit specific use cases, making it a versatile solution for various industries.

## Requirements

This project requires ``python3.5`` to be installed on your machine. It depends on ``pandas`` library as well.

## Installation

1. Clone the repository using the following command:

    ```bash
    git clone https://github.com/CodeReaper-10/coderefinery-documentation-example-project.git
    ```


2. Install the required Python packages using the following command:

    ```bash
    pip install -r requirements.txt
    ```


## Usage

1. Place the temperature data in an Excel sheet with the following format:

| Date       | Temperature (°C) |
|------------|------------------|
| 2022-01-01 | 20               |
| 2022-01-02 | 22               |
| 2022-01-03 | 19               |
| ...        | ...              |

**Note:** The first row of the sheet must contain the column names as shown.

2. Run the script using the following command:

    ```bash
    python analyse_spreadsheet.py
    ```

3. Follow the on-screen instructions to view the temperature data.

## Contributing

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature/your-feature-name`
3. Make the necessary changes and commit them: `git commit -m "Add your commit message"`
4. Push the changes to your fork: `git push origin feature/your-feature-name`
5. Create a pull request on the original repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
