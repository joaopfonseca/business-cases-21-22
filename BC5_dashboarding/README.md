
# BC5: Cryptocurrency Data Visualization

**Problem type:** Dashboarding

**Submission date:** 30-05-2022 | 11.59pm

## General Context

Data Visualization is a technique that uses graphs/charts to answer questions.
A large portion of a data scientist's work involves data visualization, and
while some skills may have obvious applications, data visualization is not a
one size fits all skill. Each data visualization task is dependent on the type
of information being explored, how the visualization will be used, the
intended audience, and how the data will be obtained and processed. 

Dashboarding, in particular, is a broader application of data visualization
techniques. Dashboards come in many different shapes and sizes. They can be
simple (e.g. a weekly sales report) or more complex (e.g. a dashboard tracking
production, sales, predictions etc.). For each task, there are some data
visualization techniques that work better than others. Some techniques allow
visualization of a range of data while others need access to detailed
information about a specific user or set of users.

An example of a data visualization problem could be, "My website is performing
exceptionally well, yet I know that the data contains user information such as
gender, age, location, and number of subscribers. How do I visualize the
entire data set?" Using a variety of techniques, an experienced data scientist
can illustrate this particular problem and provide useful insights.

## Business Situation

Warner Buffer and Gil Bates, partners of Investments4Some, after looking into
the work you did during your last project, decided to hire you once again.
They are asking you to develop a dashboard for their financial analysts.
However, they expect a flexible dashboard, that fetches daily updated data
about any arbitrary financial asset. They expect to use this dashboard to
inform the investment decisions of their internal financial team and external
stakeholders.

Your client expects you to create a dashboard that will be available for as
many assets as possible. They prefer to have a generalistic dashboard to
analyse and compare any type of asset. However, if the latter is not possible,
they would like to get (as a fallback) a dashboard primarily focused on the
cryptocurrencies used in the last project.

## Metadata

No data was provided a priori.

## Expected outcomes

1. A dashboard using any Python-based tool.
    - You may **NOT** use drag/drop dashboarding tools like Tableau, Power BI,
        Qlik Sense etc. Some suggestions:
        * [Plotly/Dash](https://dash.plotly.com/)
        * [Streamlit](https://streamlit.io/)
        * [Bokeh](https://bokeh.org/)
        * ...

    - Data must be updated either real-time or whenever the dashboard is
        initialized to display the most recent data. Suggested library:
        * [yfinance](https://pypi.org/project/yfinance/)
        * **Note**: you can use any method to achieve this. There are many other
              libraries and ways to do this.

    - The dashboard must include prediction outputs based on the work
        you developed during the last business case (feel free to modify your
        previous solution or choose other classifiers or preprocessing methods
        to do so).

    - Include analyses/visualizations of the most relevant financial indicators you found.
 
2. Other features (not required but highly appreciated):
    - Easily filter financial assets by index (name actual name not required)
    - Inclusion of relevant external data into the analysis
    - Make your work available (and documented) on Github. Include a
        description of the project, intructions to run the dashboard, and
        screenshots of the final result in the README. 
    - Deploy your dashboard for public access (there are many ways to do
        this). Some examples include:
        * [Streamlit Share](https://share.streamlit.io/) (only works for streamlit apps) - Easy
            difficulty, limited learning experience
        * [Heroku](https://www.heroku.com/) - Medium difficulty, good learning experience
        * Any cloud service provider (AWS, Google Cloud, MS Azure etc. contain some
            limited free resources) - Complex, excellent learning experience
