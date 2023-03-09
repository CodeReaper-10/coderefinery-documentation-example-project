<a name="readme-top"></a>
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<div align="center">
<h1>Temperature Data Logger</h1>

This is a project that takes temperature data as input from an excel sheet and displays the results accordingly.

<details>
  <summary>Table of Contents</summary>
  <ul>
    <li><a href="#motivation">Motivation</a></li>
    <li><a href="#requirements">Requirements</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#acknowledgment">Acknowledgment</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</details>
</div>


## Motivation

Temperature data is an important aspect in a wide range of industries such as agriculture, transportation, and manufacturing. As such, there is a need for an efficient and reliable system to manage and display temperature data. This project aims to provide a solution for this need by allowing users to easily store, view and analyze temperature data from an Excel sheet. By using this project, users can make informed decisions based on the temperature data, leading to better management and control of temperature-sensitive operations. Furthermore, this project can be customized and adapted to fit specific use cases, making it a versatile solution for various industries.


## Requirements

This project requires [![Python][Python.org]][python-url] to be installed on your machine. It depends on ``pandas`` library as well.


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


## Acknowledgment

[GitHub Repository](https://github.com/esciencecenter-digital-skills/coderefinery-documentation-example-project)
<p align="right">(<a href="#readme-top">back to top</a>)</p>


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

LinkedIn: [Adipta Santra](https://www.linkedin.com/in/adipta-santra-5978a0219/)

Email: adipta1010@gmail.com


[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/CodeReaper-10/coderefinery-documentation-example-project/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/CodeReaper-10/coderefinery-documentation-example-project/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/CodeReaper-10/coderefinery-documentation-example-project/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/CodeReaper-10/coderefinery-documentation-example-project/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/CodeReaper-10/coderefinery-documentation-example-project/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/adipta-santra-5978a0219/
[Python.org]: https://img.shields.io/badge/Python-3.5-blue
[Python-url]: https://www.python.org/
