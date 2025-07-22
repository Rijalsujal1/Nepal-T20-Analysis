# Nepal T20I Cricket Analysis

This project provides a comprehensive analysis and visualization of Nepal's performance in Twenty20 International (T20I) cricket matches. Utilizing detailed ball-by-ball data, it aims to uncover insights into various aspects of the team's game, including batting, bowling, fielding, and overall strategic performance.

## Table of Contents
- [Features](#features)
- [Data Source](#data-source)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Key Metrics Analyzed](#key-metrics-analyzed)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

This analysis covers several key areas to provide a holistic view of Nepal's T20I performance:

-   **Overall Team Performance:** General statistics on wins, losses, and team totals.
-   **Advanced Batting Metrics:** In-depth analysis of batsmen's performance, including strike rates, boundaries, and dismissal types.
-   **Advanced Bowling Metrics:** Detailed insights into bowlers' effectiveness, such as economy rates, wickets taken, and bowling variations.
-   **Fielding & Wicketkeeping Metrics:** Evaluation of fielding efficiency, catches, run-outs, and wicketkeeper dismissals.
-   **Game Intelligence Metrics:** Analysis of game situations, powerplay performance, death over strategies, and more.
-   **Visualizations:** Various plots and charts to illustrate trends and patterns in the data.

## Data Source

The dataset used in this analysis is publicly available on Kaggle:

**🔗 [Nepal T20I Ball-by-Ball Dataset (2014–Present)](https://www.kaggle.com/datasets/samarpanrai/nepal-t20i-2014-present-ball-by-ball-data/data)**  
This dataset contains granular ball-by-ball data for Nepal's international T20 matches.

> Local file path (for reference):  
`C:\Users\lsuja\OneDrive\Documents\CricketAnalysis\Nepal_T20I.csv`

## Installation

To set up the project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Rijalsujal1/Nepal-T20-Analysis
    ```
    
2.  **Navigate to the project directory:**
    ```bash
    cd CricketAnalysis
    ```
3.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv .venv
    ```
4.  **Activate the virtual environment:**
    -   **On Windows:**
        ```bash
        .venv\Scripts\activate
        ```
    -   **On macOS/Linux:**
        ```bash
        source .venv/bin/activate
        ```
5.  **Install the required Python packages:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the analysis and view the visualizations:

1.  **Ensure your virtual environment is activated.**
2.  **Start a Jupyter Notebook server:**
    ```bash
    jupyter notebook
    ```
3.  **Open the `nepal_icc.ipynb` notebook** (or any other analysis notebooks you might have) in your browser.
4.  **Run all cells** in the notebook to reproduce the analysis and visualizations.

## Project Structure

```
.
├── Nepal_T20I.csv
├── nepal_icc.ipynb
├── requirements.txt
├── .gitignore
├── README.md
└── ... (other image files or analysis outputs)
```

-   `Nepal_T20I.csv`: The raw dataset containing ball-by-ball T20I data for Nepal.
-   `nepal_icc.ipynb`: Jupyter Notebook containing the main analysis code, data processing, and visualizations.
-   `requirements.txt`: Lists all Python dependencies required to run the project.
-   `.gitignore`: Specifies intentionally untracked files to ignore by Git.
-   `README.md`: This detailed project description.

## Key Metrics Analyzed

The analysis delves into various cricket metrics, providing insights into:

-   **Batting:** Total runs, strike rate, boundaries (fours and sixes), average, dismissal types, and partnerships.
-   **Bowling:** Wickets taken, economy rate, average, strike rate, dot ball percentage, and types of dismissals induced.
-   **Fielding:** Catches taken, run-outs, and overall fielding efficiency.
-   **Team Performance:** Match results, run rates in different phases of the game, and performance against different opponents.

## Contributing

Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeature`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature/YourFeature`).
6.  Open a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Contact

For any questions or feedback, please contact Sujal Rijal at [Lsuja502@gmail.com].
You can also find me on [LinkedIn](https://www.linkedin.com/in/sujalrijal/).
