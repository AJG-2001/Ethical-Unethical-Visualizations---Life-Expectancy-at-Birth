**Ethical/Unethical Visualizations - Life Expectancy at Birth**

📌 Project Overview

This project explores the ethical and unethical use of data visualization through a red team / blue team exercise. Using World Bank data (1960–2022) on global life expectancy at birth for males and females, the team created two visualizations:

Blue Team (Ethical): A clear, transparent, and unbiased chart designed to inform.

Red Team (Unethical): A misleading visualization that distorts truth through biased design choices.

The objective was to critically assess how design decisions can shape perception, either enhancing clarity or misleading an audience
.

🔎 Data Source

World Bank – Life Expectancy at Birth (Male & Female)

Female Life Expectancy Dataset

Male Life Expectancy Dataset

🛠️ Methodology
Data Cleaning

Imputed missing values with medians.

Dropped irrelevant rows/columns (non-country data).

Standardized country names using the countrycode package.

Grouped countries into four regions: Africa, Americas, Asia, Europe.

Created yearly averages for each gender by region
.

Visualization Approach

Tools: R, ggplot2, R Markdown.

Techniques: Faceted line charts, contrasting color palettes, minimal themes.

Ethical vs. Unethical Perspectives: Applied the CRAP framework (Contrast, Repetition, Alignment, Proximity) differently to highlight clarity vs. deception.

📊 Visualizations
Blue Team (Ethical Visualization)

Design: Faceted line charts of male (steel blue) vs female (red) life expectancy by continent, 1960–2022.

Key Features:

Uniform y-axis (40–80 years) for fair comparisons.

Dashed gray gridlines and clean serif fonts for readability.

Transparent labeling and credible sourcing (World Bank).

Story: Demonstrates steady global improvement in life expectancy, with persistent gender and regional differences
.

Red Team (Unethical Visualization)

Design: Misleading line graph of African life expectancy, framed around U.S. HIV intervention.

Tactics Used to Mislead:

Background shading (“Before intervention” vs. “After intervention”) implied causality without evidence.

Skewed axis scaling (starting at 50 instead of 0) exaggerated differences.

Selective labeling minimized other factors (e.g., war, famine, poverty).

Story: Misrepresented U.S. HIV intervention as the main driver of life expectancy trends, ignoring broader causes
.

📚 References

World Bank. Life Expectancy at Birth – Male & Female (1960–2022). https://data.worldbank.org

Black History Month. (2016, October 18). The history of AIDS in Africa. https://www.blackhistorymonth.org.uk/article/section/real-stories/the-history-of-aids-in-africa/
 

🚀 Key Takeaways

Visualization is not neutral: design decisions can clarify or mislead.

The Blue Team emphasized transparency, fairness, and readability.

The Red Team demonstrated how biased framing, color, and scaling distort perception.

This project sharpened critical data literacy skills by contrasting ethical vs. unethical storytelling through visualizations.
