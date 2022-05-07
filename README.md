# :unicorn: Maven-Unicorn-Challenge

A unicorn company is a private company with a valuation of more than $1 billion, and today there are over 1,000 unicorn companies around the world!

- This dataset contains a csv table with 1,074 records, one for each company
- Each record contains details on the company's current valuation, total funding, country of origin, industry, select investors, and the years they were founded and became unicorns

More information about Maven Unicorn Challenge [here](https://www.mavenanalytics.io/blog/maven-unicorn-challenge)


# :bookmark: Key findings
- Fintech, E-commerce and Internet Software industries have the highest number of Unicorn companies, valuation and funding.
- Top five most valued unicorns are Bytedance, SHEIN, SpaceX, Stripe and Klarna. Of the five, four Unicorn companies belong to United States and China.
- United States has the highest number of Unicorns and the highest number of Unicorns are headquartered in San Franscisco.
- Internet Software, E-commerce and Fintech Unicorns are the highest in North America, Asia and Europe regions respecively.
- 2021 was the year of Unicorns, 54% of them attained the Unicorn status in 2021. AI, E-commerce, Ed-tech, Fintech and Health industries boomed in 2021 inspite of the pandemic.
- Sequoia Capital China, Tiger Global management and Tencent Holdings are the most popular investors.
- On average, it takes 7 years to become a unicorn. Some companies have become unicorns within a year of founding!


# :memo: Data wrangling
- Analysed the rows with missing city value and dropped them.
Performed data cleaning and wrangling on the dataset.
- Cleaned **Valuation** and **Funding** columns and cast it to float type
- Corrected the spelling mistake for "Artificial Intelligence" in **Industry** column
- Duplicate entries of **Bolt** company were identified. They were made unique by appending the country the company was founded in.
- Exploded the **Select Investors** column into individual rows
- Derived the year in which the company reached $1 billion in valuation
- Derived the **ROI** metric-> Valuation-to-funding ratio
- Derived the time taken to reach $1 billion in valuation

# :bar_chart: Visualization
Produced a 1-pager dashboard using Tableau.

Tableau: [Unicorn Companies 2022](https://public.tableau.com/app/profile/manaswi.kamila/viz/UnicornCompanies2022/UnicornsDashboard)

![Unicorns Dashboard](https://user-images.githubusercontent.com/77529445/167242933-7521d12e-187f-4b8b-b1e1-ee0cdb2e5ac4.png)
