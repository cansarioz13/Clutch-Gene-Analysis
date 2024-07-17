# Clutch Shooting Analysis

This project contains the code and data analysis used to write the honors thesis titled "The ‘Clutch Gene’ Myth: An Analysis of Late-Game Shooting Performance in the NBA" by Can Sarioz. The thesis investigates the concept of 'clutch' performance in basketball, specifically analyzing late-game shooting performance in the NBA across the 2008-09 and 2018-19 regular seasons.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Data](#data)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)
- [References](#references)
- [Acknowledgements](#acknowledgements)

## Introduction

The concept of a 'clutch' player, one who performs exceptionally well under pressure, is widely discussed in sports media and among fans. This project aims to analyze whether such a 'clutch gene' exists by comparing players' shooting percentages in clutch moments to their overall performance.

## Features

- **Data Collection**: Utilizes play-by-play data from NBA games.
- **Statistical Analysis**: Includes t-tests and binomial tests to compare clutch and non-clutch performance.
- **Visualization**: Provides visual insights into shooting performance during clutch and non-clutch periods.

## Data

The analysis uses NBA play-by-play data spanning from the 2008-09 to the 2018-19 regular seasons. Data files can be found compressed in the repository. Key performance metrics include:
- Field Goal Percentage (FG%)
- Free Throw Percentage (FT%)
- Three-Point Percentage (3PT%)

## Usage

To run the analysis, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/clutch-shooting-analysis.git
    cd clutch-shooting-analysis
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook Clutch_Shooting_Analysis.ipynb
    ```

The notebook contains step-by-step instructions and code to reproduce the analysis.

## Results

The analysis shows that while clutch performances as singular events do occur, there is no consistent evidence to support the existence of a clutch ability among NBA players. Key findings include:
- Overall, players tend to perform worse in clutch situations.
- Significant drops in field goal and free throw percentages during clutch moments.
- No significant change in three-point shooting percentages.

## Conclusion

The findings align with existing literature, suggesting that the belief in a clutch gene may be more a product of cognitive biases and media portrayal rather than a measurable ability. Further research could explore the psychological aspects of clutch performance and the reasons behind its persistent belief among fans.

## References

- Berri, D. J., & Eschker, E. (2005). Performance When It Counts? The Myth of the Prime Time Performer in Professional Basketball. Journal of Economic Issues, 39(3), 798–807.
- Solomonov, Y., Avugos, S., & Bar-Eli, M. (2015). Do clutch players win the game? Testing the validity of the clutch player’s reputation in basketball. Psychology of Sport and Exercise, 16, 130–138.
- Swann, C., Crust, L., Jackman, P., Vella, S. A., Allen, M. S., & Keegan, R. (2017). Performing under pressure: Exploring the psychological state underlying clutch performance in sport. Journal of Sports Sciences, 35(23), 2272–2280.

## Acknowledgements

I would like to thank Professor Ben Handel for his invaluable guidance and support throughout the research process.

---

You can copy and paste this into the "Add a README file" page on GitHub.
