# JupyterLab

 - Even if you don't use Jupyter, you can still take this survey. Just indicate this fact in the first question 
   and carry on as best as you can.
 - Thank you. Your participation guides Jupyter's roadmap toward your real-life use cases by quantifiably 
   helping us prioritize the functionality that is important to our userbase. 
 - So that you know what to expect, it's comprised of 20 questions spread across the sections below. 
   As a fair heads up, Question 7  is the biggest one, but it provides critical information.
    - Usage patterns.
    - Data
    - Visualization.
    - Scale.
    - Collaboration.
 - The aggregate survey data itself will be openly shared with the Jupyter community when polling closes in mid-December.
   If you opt to provide your email address for a user interview, it not be used for Jupyter's promotional purposes and 
   it will not be shared with a 3rd party.


### Usage Patterns

1. How frequently do you use Jupyter?
    - Daily - heavy usage; 3+ hours per day.
    - Daily - moderate usage; less than 3 hours per day.
    - Weekly.
    - Monthly.
    - I no longer use Jupyter.
    - I have never used Jupyter.

2. How long have you been using Jupyter?
    - 2+ years.
    - 1-2 years.
    - 6-12 months.
    - Less than 6 months (welcome =]).
    - I don't use Jupyter.

3. What languages do you use in Jupyter? (pick up to 4)
    - C (and derivatives)
    - Go
    - Groovy
    - Java
    - JavaScript
    - Julia
    - NodeJS
    - Perl
    - PHP
    - Python
    - R
    - Ruby
    - Rust
    - Scala
    - Spark SQL
    - SQL
    - TypeScript
    - ❗I wrap/ use bindings for other languages.
    - ❗My preferred language is not supported in Jupyter.
    - Other (please specify)

4. What are your primary job roles when you are using Jupyter? (pick up to 2)
    - Backend engineer.
    - Business analyst.
    - Data engineer.
    - Data scientist.
    - Database Admin (DBA).
    - DevOps.
    - Financial modeler/ analyst.
    - Front end/ web development.
    - Infrastructure engineer/ cloud architect.
    - Scientist/ researcher.
    - Student.
    - Sysadmin.
    - Teacher/ lecturer.
    - Tutor/ teaching assistant.
    - Other (please specify)

5. What are your go-to tools for performing data science, scientific computing, 
and machine learning on your laptop/ desktop (non-cloud) for data science? (pick up to 3)
    - Atom.
    - Emacs.
    - iPython.
    - Jupyter Notebook - Classic.
    - JupyterLab.
    - nteract.
    - PyCharm.
    - RStudio.
    - Spyder.
    - Sublime Text.
    - Vim.
    - VS Code.
    - Zeppelin.
    - Other (please specify).

6. How do you run and/ or access Jupyter? (pick up to 4)
    - BinderHub / MyBinder.
    - Cloud server (e.g. AWS EC2).
    - Cloud service - AWS (e.g. EMR, SageMaker).
    - Cloud service - Azure (e.g. Notebooks, ML Studio).
    - Cloud service - Databricks.
    - Cloud service - Google (e.g. AI Platform, Dataproc).
    - Cloud service - IBM (e.g. Watson).
    - CoCalc.
    - Google Colab.
    - HPC or on-premise server.
    - JupyterHub.
    - Mobile device (e.g. phone, tablet). Comments welcome.
    - Through a Python virtual environment (e.g. conda, virtualenv).
    - Through Docker.
    - ❓Don’t know how, I just go to a URL.
    - 🖥️ Run directly on local machine (e.g. laptop, desktop).
    - Other (please specify).

7. What tasks do you need to perform and what tools do you use to accomplish them?
    - Cleaning and preparing data.
    - Run pipelines, workflows, or ETL (extract, transform, load) jobs.
    - Building a machine learning or statistical model.
    - Creating content (e.g. blogs, books, education materials).
    - Developing extensions/ plugins to solve my problems.
    - Writing and running tests for software.
    - Visualize data in charts, plots, or dashboards.
    - Writing software documentation.
    - Finding extensions/ plugins to solve my problems.
    - Writing a software package.
    - Documenting research (reports, scientific papers)
    - Other major use cases (please specify).

    For each of the items above, provide additional information related to:
    - How frequently do you perform this task?
        - Never.
        - Every few months.
        - Monthly.
        - Weekly.
        - Daily.
    - To what degree does Jupyter meet your expectations for this?
        - Does not apply.
        - Never meets.
        - Rarely meets.
        - Sometimes meets.
        - Often exceeds.
        - Always exceeds.
    - To what degree do alternative tools meet your expectations for this?
        - Does not apply.
        - Never meets.
        - Rarely meets.
        - Sometimes meets.
        - Often exceeds.
        - Always exceeds.

### Data

8. What data sources are you primarily working with in your role? (pick up to 3)
    - My local file system (e.g. files and folder on local machine).
    - File system (e.g. HPC, EBS/EFS, JupyterHub volumes).
    - Cloud object storage (e.g. buckets, S3, Blob, GS).
    - SQL (e.g. PostgreSQL, MySQL)
    - SQL - embedded (e.g. SQLite)
    - NoSQL - columnar store (e.g. Parquet, Arrow, HDFS, BigQuery).
    - NoSQL - document store (e.g. MongoDB, Elasticsearch, CouchDB).
    - Graph database (Neo4j, TigerGraph).
    - Time Series (e.g. InfluxDB).
    - Pub sub (e.g. Kafka, Druid).
    - Key value (e.g. Redis, MemcacheDB).
    - Google Sheets.
    - ❗Industry or field specific APIs.
    - Streaming.
    - Other (please specify)

9. What data formats are you mostly working with? (pick up to 3)
    - Tabular (csv, spreadsheet, database tables, parquet).
    - Images.
    - Tensors (deep learning).
    - Nested (JSON, NoSQL).
    - Hierarchical Data Format (HDF5).
    - Time series.
    - Text.
    - Audio.
    - Video.
    - 3D/ CAD.
    - Graph (nodes, edges).
    - Spatial/ geographic (coordinates, GIS).
    - Game/ reinforcement simulation.
    - ❗Industry-specific file formats.
    - Other (please specify)

10. Do you experience these problems with data in Jupyter? (rate from scale of 0-4)
    - Data is too big to fit into memory on my machine/ server.
    - Can’t see a list of my current variables.
    - Poor MVC/ ORM integrations (Django, Flask).
    - Managing database/ source connections and secrets.
    - No grid view for manipulating/ filtering dataframes and arrays.
    - Lost data during failure or restart of kernel/ server.
    - Other (please specify)
    
    For each of the items above, specify:
    - Not a problem for me.	
    - Trivial.	
    - Minor.	
    - Major.	
    - Critical.	
    - N/A - skip, don't know.

11. What type of analysis are you running? (up to 4)
    - ❗I am not performing ML/statistical tasks.
    - Regression (predict a numeric output).
    - Classification (predict a categorical output).
    - Generative/ auto-encode (create new data based on existing data).
    - Reinforcement learning (actions that maximize a reward)
    - Dimensionality reduction (PCA, K-Nearest Neighbors)
    - Feature engineering (importance, extraction, selection, permutation).
    - Natural language processing.
    - Graph data science.
    - Outlier detection.
    - Other (please specify)
    
    
### Visualization

12. What tools does your team use to create dashboards tools? (pick up to 3)
    - ❗My team doesn’t create dashboard tools.
    - Write our own in HTML & JS.
    - R Shiny.
    - Kibana.
    - Dash-Plotly.
    - Voila.
    - Tableau.
    - Looker.
    - Klipfolio.
    - Google Data Studio.
    - Spotfire.
    - Grafana
    - Other (please specify)

13. Do you experience these problems with visualization in Jupyter?
    - No built-in UI for creating charts.
    - Can't publish my charts as web-based dashboards.
    - Poor/ buggy support for my plotting tool.
    - Displaying highly dimensional data (array of array of arrays, too many rows/ columns to fit on screen).
    - Lacking templating support (Jinja2)

    For each of the items above, specify:
    - Not a problem for me.	
    - Trivial.	
    - Minor.	
    - Major.	
    - Critical.	
    - N/A - skip, don't know.

### Scale

14. How do you scale and schedule your workloads? (up to 4)
    - They run just fine on my local machine 😃.
    - ❓I need to scale, but don't know how.
    - On-premise HPC/ data center.
    - Cloud server (e.g. EC2)
    - Cloud service for ML/ AI (e.g. AWS SageMaker)
    - Spark cluster (e.g. similar Hadoop, Dask).
    - K8s cluster (e.g. Mesos, Swarm, Slurm).
    - Jupyter Enterprise Gateway.
    - Jupyter BinderHub.
    - Quantum (e.g. D-Wave).
    - Horovod.
    - Kubeflow.
    - Elyra.
    - Workflow - Snakemake.
    - Workflow - Papermill
    - Workflow - Nextflow, WDL, CWL.
    - Workflow - Airflow.
    - Workflow - cloud service (e.g. AWS Batch)
    - Cloud query service (AWS Presto or Athena)
    - Other (please specify)

15. Do you experience these problems with scale in Jupyter?
    - Figuring out how to schedule batch execution of notebook-based jobs.
    - Don’t have the budget for more scalable environment/ cloud services.
    - Haven’t divided longer notebooks into multiple, modular notebooks.
    - Not persisting the outputs of a notebook.
    - ML training jobs take too long.
    - Can't call code/ modules from other notebooks.
    - Managing Spark dependencies (Java) and connections.

    For each of the items above, specify:
    - Not a problem for me.	
    - Trivial.	
    - Minor.	
    - Major.	
    - Critical.	
    - N/A - skip, don't know.

### Collaboration

16. With how many other people are you collaborating?
    - 0
    - 10
    - 20
    - 30
    - 40
    - 50+

17. What is your reason for sharing a notebook with someone else? (up to 3)
    - ❗I am not working with other people.
    - Share knowledge.
    - Feedback about my writing.
    - Feedback about my code.
    - Formal code review.
    - Integrate my code/ data with their downstream or upstream processes.
    - Edit/ contribute some of their own code.
    - Edit/ contribute some of their own writing.
    - Teach/ tutor them.
    - Peer programming.
    - Deploy my code/ model/ pipeline/ dashboard.
    - Other (please specify)

18. What is the nature of your collaboration?
    - Describe the collaboration:
        - How long have you been working together?
            - I am not collaborating.
            - 2+ years.
            - 1-2 years.
            - 6-12 months.
            - Less then 6 months.
        - How frequently do you work together?
            - I am not collaborating.
            - 2+ times per week.
            - Weekly.
            - A few times a month.
            - Monthly.
            - Less then monthly.
        - How do you divide the work?
            - I am not collaborating.
            - We work on different projects.
            - We work on the same project, but different parts.
            - We work on the same part of the same project together.
    - Comments about collaboration:

19. Do you have challenges with collaboration in Jupyter?
    - Don't know what dependencies (versions of language, packages, extensions) a notebook uses.
    - Don't know/ have the data a notebook is supposed to use.
    - Poor support for our version control (git) system.
    - Publishing my notebook to a shared location.
    - Not being able to comment on notebooks.
    - More robust non-git version history of a notebook.

    For each of the items above, specify:
    - Not a problem for me.	
    - Trivial.	
    - Minor.	
    - Major.	
    - Critical.	
    - N/A - skip, don't know.

20. Do you have challenges with the notebook UI?
    - Poor autocompletion [LSP, show methods/ attributes].
    - No modes for editing other Jupyter documents (MyST, Jupyter Book).
    - Can't see hidden (.) files in file browser.
    - Can't collapse sections of a notebook hierarchically.
    - No progress bar for running long notebooks.
    - Don't know which cell failed in long notebook.
    - No Extension marketplace (5 star ratings, categories).
    - No global search.
    
    For each of the items above, specify:
    - Not a problem for me.	
    - Trivial.	
    - Minor.	
    - Major.	
    - Critical.	
    - N/A - skip, don't know.

### You did it - thank you!

21. Open feedback for problems/ pain points you didn't get to share.


22. Email Address for Recontact - Do we have your permission to recontact you for a user interview? (If not, leave this question blank.)