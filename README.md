# Books-Market-Intelligence-SQL-Analysis
SQL-driven analysis of books, authors, publishers, ratings, and reviews to generate market intelligence and support data-dr

## Overview
This project analyses a relational database from an online book service to extract insights about books, authors, publishers, and user engagement. The goal is to support the creation of a data-driven value proposition for a new product in the digital reading market.

The analysis is performed **entirely in SQL**, with results surfaced in a notebook and visualised through an interactive Tableau dashboard.

---

## Business Objective
- Understand publishing activity and trends after 2000
- Measure user engagement through ratings and written reviews
- Identify high-performing publishers and authors
- Analyse reviewer behaviour to inform product strategy

---

## Live Dashboard (Tableau Public)
An interactive dashboard was created to present the key findings in a visual and accessible format:

🔗 **Tableau Dashboard — Books SQL Project**  
https://public.tableau.com/views/Proyecto-Books-SQL/Dashboard?:language=en-GB&:display_count=n&:origin=viz_share_link

The dashboard highlights:
- Publishing trends
- Rating and review patterns
- Top publishers and authors
- User engagement indicators

---

## Data Model
The database consists of five related tables:

- **books** — book metadata (pages, publication date, publisher)
- **authors** — author information
- **publishers** — publishing houses
- **ratings** — user ratings per book
- **reviews** — written user reviews per book

The schema supports joins across books, authors, publishers, ratings, and reviews.

---

## Analytical Workflow

### Data Exploration
- Inspect table structures and sample records
- Validate relationships between entities

### SQL Analysis
Queries were written to answer the following:
- Number of books published after January 1, 2000
- Number of user reviews and average rating per book
- Publisher with the most books over 50 pages
- Highest-rated author (books with ≥50 ratings only)
- Average number of written reviews by highly active reviewers (users rating >50 books)

### Result Interpretation
- Each query result is documented with a concise business interpretation
- Findings are contextualised for product and market strategy

---

## Key Outputs
- SQL queries answering all business questions
- Query results displayed via pandas for clarity
- Interactive Tableau dashboard for stakeholder consumption
- Clear insights into publishing performance and user behaviour

---

## Tools
- SQL (primary analysis)
- Python (pandas for query output display)
- Jupyter Notebook
- Tableau Public

---

## Conclusion
This project demonstrates strong capability in **SQL-driven analysis**, relational data modelling, and translating database queries into actionable market insights. The results support strategic decisions related to content focus, publisher partnerships, and user engagement features.

---

## Author
**Erika González**  
MBA | Marketing & Data Analytics  
Focus areas: SQL Analytics, Market Intelligence, Data-Driven Product Strategy
