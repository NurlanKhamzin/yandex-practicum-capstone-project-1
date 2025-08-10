# 🎬 Capstone Project
## Film Distribution Market Analysis
## 🎓 What Is This Project?
Now it’s time to test your knowledge and solve an analytical case. You’ll work on this project independently.

Once you finish, submit it for review. Within 24 hours, you’ll receive feedback. You’ll need to revise your project based on the comments and resubmit it.

You may need to revise the case multiple times — that’s perfectly normal.

The project is considered complete once all revisions are approved.

## 📌 Project Description
The client for this research is the Ministry of Culture of the Russian Federation.

Your task is to study the Russian film distribution market and identify current trends. Pay special attention to films that received government support. Try to answer the question: How appealing are these films to audiences?

You’ll work with data published on the Ministry of Culture’s open data portal. The dataset includes information on distribution licenses, box office revenue, government support, and ratings from the KinoPoisk website.

## 🛠️ Instructions
Step 1: Open the data files and merge them into a single DataFrame
Merge the data so that all entries from the mkrf_movies dataset are included in the resulting DataFrame.

File paths:

- /datasets/mkrf_movies.csv — data on distribution licenses

- /datasets/mkrf_shows.csv — data on film screenings in Russian cinemas

Step 2: Data Preprocessing
- Check the data types in the DataFrame and convert them where necessary

- Examine missing values. Explain why you chose to fill or not fill them

- Check for duplicates. Describe possible reasons for their appearance

Explore columns with categorical values:

- Identify a common issue across most categorical columns

- Fix problematic values in the type column

Explore columns with numerical values:

- Check for suspicious data entries. Decide how best to handle them

Add new columns:

- Extract the release year from the film’s premiere date

- Create two columns: one for the first director’s name and one for the primary genre (first value in each list)

- Calculate the share of government support in the film’s total budget

Step 3: Exploratory Data Analysis
- Count how many films were released each year

- Note that box office data is not available for all films. Calculate the share of films with box office data and analyze how this share changed over the years

- Determine which period is most fully represented in the data

Analyze box office trends over time:

- In which year was the total box office revenue the lowest? The highest?

- Use a pivot table to calculate the average and median box office revenue per year. Compare and interpret the results

Investigate whether age restrictions ("6+", "12+", "16+", "18+", etc.) affect box office revenue between 2015 and 2019:

- Which age category generated the most revenue?

- Does this trend change by year? If so, suggest possible reasons

Step 4: Explore Films with Government Support
This step has no strict instructions — look for interesting patterns in the data.

- Examine how much funding is allocated to supported films

- Check how well these films perform financially

- Analyze their ratings

Step 5: Write a General Conclusion
🧾 Formatting Guidelines
Complete the assignment in Jupyter Notebook:

- Use code cells for programming

- Use markdown cells for explanations

- Apply formatting and headings for clarity

## 📋 Data Description
The mkrf_movies table contains information from the distribution license registry. A single film may have multiple licenses.

Columns:

- title — film title

- puNumber — distribution license number

- show_start_date — film premiere date

- type — film type

- film_studio — production studio

- production_country — country of production

- director — director

- producer — producer

- age_restriction — age rating

- refundable_support — amount of refundable government support

- nonrefundable_support — amount of non-refundable government support

- financing_source — source of government funding

- budget — total film budget

- ratings — KinoPoisk rating

- genres — film genre(s)

Note: The budget column already includes the full amount of government support. Data in this column is only available for films that received support.

The mkrf_shows table contains data on film screenings in Russian cinemas:

- puNumber — distribution license number

- box_office — box office revenue in rubles

## ✅ How Will My Project Be Evaluated?
💡 If your project is sent back for revision, do not delete reviewer comments in the Jupyter Notebook. This helps the reviewer check your changes more easily.

Your project will be evaluated based on specific criteria. Review them carefully before starting.

Reviewers will assess:

- How you describe problems found in the data

- Which methods you use for type conversion, handling missing values, and duplicates — and how you justify your choices

- Whether you automate repetitive tasks

- Whether you summarize final data in pivot tables

- Which graphing methods you use

- Whether your project is well-structured and your code is clean

- What conclusions you draw

- Whether you leave comments explaining your steps

Everything you need to complete the project is covered in the course materials.

Good luck! 🍀
