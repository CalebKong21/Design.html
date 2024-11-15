# Design.html
CSCI 490 Proj
Project
Goal
The goal of the project is for you to develop an interactive, Web-based visualization for a real-world dataset. You will need to understand the data (its types and semantics), the questions your visualization will answer, the tasks it will support, and make justifiable visualization design choices.

Instructions
You should produce an interactive, Web-based visualization that could be published to the Web. You may work individually or with a partner on the project. If you choose to work with a partner, I will expect significantly more work than I will on an individual project. The project should utilize visualization libraries and provide custom visualizations (i.e. not the charts that applications like Excel would produce).

If you are currently working on research and would like to have a visualization project that fits with your research, please contact me so we can design a good project.

Steps
0. Dataset Selection, October 25, 2024
1. Proposal, October 30, 2024
2. Designs, November 15, 2024
3. Presentation, 2024-12-02 and 2024-12-04
4. Report, TBA


Dataset
Here are a few dataset ideas:
-US Food Safety Data
-Illinois Hospital Report Card (API, GitHub)
-National Football League Datasets (older years also available)
-US Register of Introduced and Invasive Species

If you have a particular interest in another dataset, please talk with me about it.

Note that you do not need to use all of the data. If you need any help extracting or transforming the part of the dataset you wish to use, please contact me. While it’s great to put data manipulation skills to use, the focus of the project is on the visualizations.

Proposal
Submit, via Blackboard, a proposal that includes

The name and URL of the dataset(s) you will be working with and a description of the types and semantics of your dataset. This means defining the attributes and what the attribute types (categorical, ordered, quantitative) are. This should include necessary background information about the domain being studied. Explain any ideas and terms being examined.

A detailed list of the tasks you envision in your project. For example, if you are examining a dataset of taxi data, you might ask “Are there any trends between the day of the week and number of rides?” or “Which locations see the highest density of ridership?”. These should be questions that cannot be answered via a simple statistical calculation; examples of bad questions include “What day had the maximum number of rides?” or “How many days are in the dataset?”. That is not to say that these questions are not important but rather that a visualization is not required to answer them.

A sketch that shows some initial ideas about how your visualization and its interactions work. I recommend drawing by hand and scanning (or use a camera phone), but you may also use a computer drawing program.

A collection of ideas and requirements for your visualization and its interactions. Many projects will have multiple views and/or customized techniques. If you use multiple views, focus on how the views are linked together (e.g. linked highlighting). In addition, consider what interactive elements you would like to have (e.g. zooming, dropdown menus, transitions from one data subset to another).


Designs

Submit, via Blackboard, your current sketches and code for the project and include at least three different design iterations for your visualization: two good designs and one bad design. If you have updated any of the details based on feedback on the proposal, please indicate the updates and include them as well. At least one of the designs should be prototyped, and the others should either be prototypes or detailed sketches (as with Five Sheets Design). For prototypes, it will be easier if you use version control and create versions often. Consider using GitHub and tagging iterations of the design or creating branches for different ideas. Your submission must include a table of contents that clearly identifies at least three designs you have produced. You may put all the different iterations on one web page with a table of contents section at the beginning (preferred) or on separate web pages with a separate table of contents page. Any sketches should be scanned/photographed and included in the web page. The main page should be titled designs.html. Make sure to include all JavaScript and CSS files as well as the HTML files.

Presentation

You will present your final visualization during the last week of classes. Before then, please submit, via Blackboard, an index.html file that contains or links to all of your project material. If you create your project using Observable, you may just put the link to that notebook in the file. Otherwise, include any other files (JavaScript, data, etc.) you need to run for your presentation in the submitted file as well. Your presentation should describe the dataset and the questions it answers in addition to showing your visualization and describing its features and your design choices. We will plan to run all presentations via my laptop in Chrome to ensure we get through all of the presentations.

Report
Your submission should contain:

Code:

All the code you developed for the project.
Include data if it is not linked directly in your visualization, or include a README with instructions on how to obtain it if it is too large (>5MB) to include. Please do not turn in files >20MB to Blackboard.
You may submit a link (e.g. to an Observable notebook) as long as it will be live until at least the end of the semester, but I recommend also downloading the tgz file and turning that into Blackboard just in case.
Report (3-4 pages of text, more if screenshots are included):

Describe the dataset.
Describe the questions your visualization is designed to answer.
Describe the visualization you created and how its design evolved. What marks and channels are used? What techniques do you build on?
Describe how the visualization can be used to answer the questions.
Your report may be integrated with an Observable notebook, but could be a separate PDF or Word document. If you turn in a notebook link, I strongly recommend printing the notebook to a PDF and turning that in as well just in case.
