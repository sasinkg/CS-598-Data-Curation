# Assignment 1 Information

## Assignment 1: Data curation using the relational model
- Data curation is concerned with all aspects of data management required to efficiently and reliably support analysis and reuse. This includes everything from initial acquisition to organization, integration, access and preservation. Data often originate from a variety of sources and in different formats. Often curation requires the selection of a basic model for storage and organization and may require an in-depth understanding of the data and objectives for its use. The fundamental model we select and our design and implementation may support or impede our other objectives.
- In this exercise, we explore the application of the widely-used relational model in the context of data curation. This is not about learning the relational model or entity-relationship diagramming techniques---we assume you already have a basic understanding of these. Instead, this exercise is intended for you to consider the strengths and weaknesses of the relational model with respect to curatorial objectives and activities.  If you need a refresher on logical schema design or entity-relationship diagramming, see the Additional Resources section below.

The assignment is divided into two parts:
1. Data analysis and relational schema design
2. Data integration and entity-relationship diagramming

## Learning objectives
- Become familiar with data abstraction, indirection, and strategies for data representation using the relational model.
- Gain experience analyzing the characteristics of a dataset.
- Gain experience with documenting rationale for data representation selection, emphasizing relevance to data curation.
- Become familiar with ER diagrams and strategies for data integration.
- Gain experience analyzing the characteristics of data and integrating data sources.

## Part 1: Relational Schema Design
### Scenario:
The setting is a small auto dealer with three separate departments: Inventory, Sales, and Customer Relations. Today the departments manage information separately, but they hope to integrate it into a shared database  in order to be able to answer questions like, "What engine is in Customer Smith’s car?" While the Sales group has information about which car a customer bought; the Inventory group tracks which engines are in which cars; and the Customer Relations maintains separate (and slightly redundant) information about each customer.

You have been tasked with defining an approach that is effective and efficient for all departments and supports combining data from the different sources.

You are given data from each department:

A. File A (Inventory): Document relating models to styles, power trains, quantities, and individual cars, etc.

B. File B (Sales): Document relating people to cars, prices, trade-ins, etc.

C. File C (Customer relations): Document relating people to personal information, information about services, warranties, etc.

### Instructions:
1. [20 points] Write a short narrative description of each file we have given you (about 150~300 words). Be sure to remark on the overall quality of the data (are there errors, missing values, etc.), the contents of each data file, and any data which overlaps between files.

2. [10 points] Use your narrative to design a database schema that will accommodate the information in the files. Your schema should include:
    - Tables
    - Attributes (column heading) in each table
    - Datatypes for each attribute (develop your own)
    - Primary and foreign keys

3. [15 points] Create an example of each table, populated with data from the files.

4. [30 points] Write an account of your process for creating the database schema and tables. Describe any decisions you had to make as you developed a relational schema.
    - How did you decide to represent the data in the way that you did?
    - Did you leave out any information? If so, why?
    - Why did you choose certain things as attributes? As keys?
    - What were the hardest decisions you had to make in this design process?
    - How does your schema design support data independence?
    - How may your schema design support the overarching goals of data curation (revisit objectives and activities of Week 1)?
    - What are the pros and cons of your schema design?
    - Which curation activities could enhance or sustain the database for future discovery and use for new purposes? What additional activities would you recommend?

5. For Part 1, your submission should include two parts:
    - A workbook including schema and tables from steps 2-3
    - A document containing your narratives from steps (1) and (4), above

