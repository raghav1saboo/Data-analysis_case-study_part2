# Data-analysis_case-study_part2
Did real_world analysis on the basis of case study analysis done in part 1

---
jupyter:
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
  language_info:
    codemirror_mode:
      name: ipython
      version: 3
    file_extension: .py
    mimetype: text/x-python
    name: python
    nbconvert_exporter: python
    pygments_lexer: ipython3
    version: 3.11.4
  nbformat: 4
  nbformat_minor: 2
  orig_nbformat: 4
---

::: {.cell .markdown}
In this section, you need to try to find out answer to the given
questions using the solutions you have done in Case Study (part 1) or
you might need to write code to find the answers.
:::

::: {.cell .markdown}
## Case Study : Questions {#case-study--questions}

1.  Your Friend has developed the Product and he wants to establish the
    product startup and he is searching for a perfect location where
    getting the investment has a high chance. But due to its financial
    restriction, he can choose only between three locations - Bangalore,
    Mumbai, and NCR. As a friend, you want to help your friend deciding
    the location. NCR include Gurgaon, Noida and New Delhi. Find the
    location where the most number of funding is done. That means, find
    the location where startups has received funding maximum number of
    times. Plot the bar graph between location and number of funding.
    Take city name \"Delhi\" as \"New Delhi\". Check the
    case-sensitiveness of cities also. That means, at some place instead
    of \"Bangalore\", \"bangalore\" is given. Take city name as
    \"Bangalore\". For few startups multiple locations are given, one
    Indian and one Foreign. Consider the startup if any one of the city
    lies in given locations.
2.  Even after trying for so many times, your friend's startup could not
    find the investment. So you decided to take this matter in your hand
    and try to find the list of investors who probably can invest in
    your friend's startup. Your list will increase the chance of your
    friend startup getting some initial investment by contacting these
    investors. Find the top 5 investors who have invested maximum number
    of times (consider repeat investments in one company also). In a
    startup, multiple investors might have invested. So consider each
    investor for that startup. Ignore undisclosed investors.
3.  After re-analysing the dataset you found out that some investors
    have invested in the same startup at different number of funding
    rounds. So before finalising the previous list, you want to
    improvise it by finding the top 5 investors who have invested in
    different number of startups. This list will be more helpful than
    your previous list in finding the investment for your friend
    startup. Find the top 5 investors who have invested maximum number
    of times in different companies. That means, if one investor has
    invested multiple times in one startup, count one for that company.
    There are many errors in startup names. Ignore correcting all, just
    handle the important ones - Ola, Flipkart, Oyo and Paytm.
4.  Even after putting so much effort in finding the probable investors,
    it didn\'t turn out to be helpful for your friend. So you went to
    your investor friend to understand the situation better and your
    investor friend explained to you about the different Investment
    Types and their features. This new information will be helpful in
    finding the right investor. Since your friend startup is at an early
    stage startup, the best-suited investment type would be - Seed
    Funding and Crowdfunding. Find the top 5 investors who have invested
    in a different number of startups and their investment type is
    Crowdfunding or Seed Funding. Correct spelling of investment types
    are - \"Private Equity\", \"Seed Funding\", \"Debt Funding\", and
    \"Crowd Funding\". Keep an eye for any spelling mistake. You can
    find this by printing unique values from this column. There are many
    errors in startup names. Ignore correcting all, just handle the
    important ones - Ola, Flipkart, Oyo and Paytm.
5.  Due to your immense help, your friend startup successfully got seed
    funding and it is on the operational mode. Now your friend wants to
    expand his startup and he is looking for new investors for his
    startup. Now you again come as a saviour to help your friend and
    want to create a list of probable new new investors. Before moving
    forward you remember your investor friend advice that finding the
    investors by analysing the investment type. Since your friend
    startup is not in early phase it is in growth stage so the
    best-suited investment type is Private Equity. Find the top 5
    investors who have invested in a different number of startups and
    their investment type is Private Equity. Correct spelling of
    investment types are - \"Private Equity\", \"Seed Funding\", \"Debt
    Funding\", and \"Crowd Funding\". Keep an eye for any spelling
    mistake. You can find this by printing unique values from this
    column. There are many errors in startup names. Ignore correcting
    all, just handle the important ones - Ola, Flipkart, Oyo and Paytm.
:::

## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
Welcome to the "Data Analysis Case Study Part 2" repository. This project is a continuation of Part 1 and involves further data analysis and exploration of the dataset from a real-world scenario. The goal is to build upon the insights gained in Part 1 and perform more advanced analysis to derive meaningful conclusions.

## Objective
The primary objectives of this project include:
- Extending the analysis from Part 1 by incorporating additional data and metrics.
- Applying advanced data manipulation and statistical techniques to gain deeper insights.
- Creating visualizations and reports to effectively communicate the findings.

## Technologies Used
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn

*(Feel free to add or modify the list of technologies based on the tools and libraries used in your project)*

## Installation
To run the code in this repository locally, follow these steps:

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/raghav1saboo/Data-analysis_case-study_part2.git
   ```

2. Navigate to the project directory:
   ```
   cd Data-analysis_case-study_part2
   ```

3. Install the required dependencies using the following command:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Open Jupyter Notebook to access the analysis files:
   ```
   jupyter notebook
   ```

2. In the Jupyter Notebook interface, navigate to the `analysis.ipynb` file, and open it.

3. Run the code cells in the notebook to perform the extended data analysis and visualization.

*(If there are specific usage instructions for your project, provide them here)*

## Data
Describe the dataset used in this project. Mention its source, format, and any data preprocessing steps taken. You can also provide a link to the original dataset or mention how to obtain it.

## Contributing
Contributions to this project are welcome. If you find any issues or have improvements to suggest, please feel free to open an issue or create a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
If you have any questions or need further assistance, you can reach me via email at [raghav1713@gmail.com]


---
.
