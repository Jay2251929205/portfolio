# New Visualization on Blockchain Decentralization: 2D Histogram Contour Plots
## Project information
- **Author**: Jiayi Wang, Applied Mathematics, Class of 2024, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 (Machine Learning for Explanation Section) for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**:  I am deeply indebted to my professor Luyao Zhang for her invaluable patience and inspiring instructions on these machine learning methods. I could not started my journey without her feedback and help. Additionally, this endeavor would not have been possible without Prof. Luyao Zhang, Xinshi Ma, and Yulin Liu's initial research and data source of [Blockchain Decentralization](https://arxiv.org/abs/2205.04256). I am also grateful to my classmates, especially for Haoyang's sharing in class. Lastly, I would be remiss in not mentioning my family, especially my parents.
- **Project Summary**: Based on Luyao Zhang, Xinshi Ma, and Yulin Liu's research on [Blockchain Decentralization](https://arxiv.org/abs/2205.04256), the project is aimed at generating a new visualization for the decentralization index of three tokens, which are "AAVE", "COMP", and "LUSD". Here, one kind of the new visualizations is shown and more other amazing visualizations can be generated. [Python Plotly](https://plotly.com/python/) is used to generate a Violin Plot for the dencity of three tokens' decentralization index under 30-day simple moving averj

## Table of Contents
- [data](https://github.com/Jay2251929205/portfolio/tree/main/data)
- [code](https://github.com/Jay2251929205/portfolio/tree/main/code)
- [spotlight](https://github.com/Jay2251929205/portfolio/tree/main/spotlight)

## Data
- Data Source: https://github.com/SciEcon/SoK_Blockchain_Decentralization/tree/main/Data_TokenIndex
- [Queried Data](https://github.com/Jay2251929205/portfolio/tree/main/data/Queried_Data)
- [Processed Data](https://github.com/Jay2251929205/portfolio/tree/main/data/Processed_Data)

## Code
- [Query Data](https://github.com/Jay2251929205/portfolio/blob/main/code/Query_Data.ipynb)
- [Process Data](https://github.com/Jay2251929205/portfolio/blob/main/code/Process_Data_updated.ipynb)
- [Analyze Data](https://github.com/Jay2251929205/portfolio/blob/main/code/Analyze_Data_updated_updated.ipynb)

## Spotlight

![Figure No.1 ](https://github.com/Jay2251929205/portfolio/blob/main/spotlight/image/figure1.png)

**Figure No.1. Source: [SoK: Blockchain Decentralization](https://github.com/SciEcon/SoK_Blockchain_Decentralization/), created by [Plotly](https://plotly.com/python/)**

Figure No.1 represents the dencity of AAVE, COMP, and LUSD's decentralizaton index under 30-day simple moving average. The y-axis shows the 30-day moving average of the decentralization index of these three tokens. The legend shows that the fatter the violin is, the more centralized the data will be. In the boxplot inside the violin, the imaginary line shows the mean value and the full line stands for the median value. We can learn from the figure that under SMA30, AAVE obviously has a higher decentralization index and a larger range than the other two tokens, while the index of LUSD seems to be the most centralized and lower that the other two tokens.


## References

### Data Source
[SoK_Blockchain_Decentralization/Data_TokenIndex](https://github.com/SciEcon/SoK_Blockchain_Decentralization/tree/main/Data_TokenIndex)
### Code Source
[SoK_Blockchain_Decentralization/code/Top_DeFi_Decentralization_Visualizations.ipynb](https://github.com/SciEcon/SoK_Blockchain_Decentralization/blob/main/code/Top_DeFi_Decentralization_Visualizations.ipynb)
### Articles
[SoK: Blockchain Decentralization](https://arxiv.org/abs/2205.04256)
### Literature
Zhang, Luyao, Xinshi Ma, and Yulin Liu. 2022. “SoK: Blockchain Decentralization.” ArXiv:2205.04256 [Cs, Econ, Q-Fin], May. https://arxiv.org/abs/2205.04256.
