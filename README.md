# 🐉 Hearthstone Power Creep Analysis 📊

Welcome to the **Hearthstone Power Creep Analysis** project! In this project, we delve into the depths of Hearthstone's expansions to investigate the ever-elusive feeling of power creep among minions. As players strategize and duel in the tavern, many sense that the strength of minions has evolved over time. But is this intuition supported by the stats? 🤔

## 🔍 Project Objective

The primary goal of this project is to analyze whether the perception of power creep in Hearthstone correlates with the increasing stats of minions across various expansions. By examining the data of minions over time, we aim to shed light on the balance (or imbalance) of minion abilities.

## 📈 Data Analysis

Using the Hearthstone API, we gather comprehensive data on collectible minions, including attributes like **cost**, **attack**, **health**, and **rarity**. We plot average attack and health values by year and evaluate the efficiency of minions to understand how mana is being spent.

### Key Functions:
- `plot_this(data, cost=None, rarity=None)`: Visualizes average attack and health of minions filtered by cost and rarity.
- `plot_that(data, cost)`: Compares the average efficiency of minions by rarity over time for a specified cost.
- `find_card(cards, key, value)`: Locates specific cards based on key-value criteria.

## 📊 Visualizations

The project includes various plots to illustrate our findings:
- Line plots showcasing average attack and health values of minions over the years.
- Comparisons of efficiency between different rarity types using violin plots.

## 📑 Presentation

A **PPTX file** is included with the project, containing the presentation of our findings. It includes detailed notes to guide the reader through the analysis process, discussions, and conclusions drawn from our research.

## 📝 Conclusion

After thorough analysis, we concluded that the feeling of power creep cannot be solely attributed to the increasing stats of minions across expansions. Instead, minions have remained balanced over time, maintaining the integrity of the game. ⚖️

## 💻 Getting Started

To run the analysis, ensure you have the following libraries installed:

- `requests`
- `pandas`
- `matplotlib`
- `seaborn`

Clone the repository and execute the scripts to visualize the data. Happy analyzing! 🎮
