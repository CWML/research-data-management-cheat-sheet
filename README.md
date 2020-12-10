# Research Data Management Cheat Sheet

## Research Data Management Lifecycle 
The research data management lifecycle is an illustration of the research process as it relates to data management. In this system, data is meant to be organized, annotated and stored in ways that will facilitate data sharing and reuse and/or research validation.  

<img src="https://github.com/CWML/research-data-management-cheat-sheet/blob/main/images/research-data-lifecycle.png" alt="data lifecycle" width="600">

#### Project Planning
At the start of any research project, you should think ahead about what data you will need to use (if any) during your research processes. You may need to pay to access, compute against, or store data, so knowing about these costs upfront can inform grant budgets.  

#### Data Creation / Collection
Data might be collected from vendors, databases, or other researchers. If the data you are searching for does not exisit, you may need to collect it yourself from multiple sources, or you may need to create the data. 

Support at Yale:
* Reusing data from data repositories - [strategies for finding appropriate data repositories](https://library.medicine.yale.edu/research-data/find-datasets/data-repositories)
* Reusing data associated with publications [strategies for finding research data for reuse](https://library.medicine.yale.edu/research-data/find-datasets/) 
* Collecting data from EHRs (Electronic Health Records) - [YNHH Epic EHR data pull requests at Yale are places through JDAT (the Joint Data Analytics Team](https://medicine.yale.edu/ycci/researchservices/systems/epic/datarequests/)

#### Data Processing
After data is collected or created, most likely you will need to process or clean the data in some way. Data processing and cleaning can involve, merging multiple datasets, selecting or filtering out specific portions of a dataset, standardizing categories found within a dataset, reorganizing how spreadsheets containing data are organized, and more. When you create data groups that result in aggregation, data processing can start to bleed into data analysis. 

Support at Yale:
* Data Support @ the Medical Library - email medicaldata@yale.edu 

#### Data Analysis
Data analysis = generating findings from your data. 

An important part of data analysis includes data visualization (i.e., graphs).

Support at Yale
* Statistical help - [StatLab](https://marx.library.yale.edu/data-gis-statlab/statlab)
* Bioinformatics help - [Bioinformatics Hub](https://library.medicine.yale.edu/bioinformatics)
* High Performance Computing & Parellel Computing - [YCRC (Yale Center for Research Computing](https://research.computing.yale.edu/) 
* Research & Analytics Clinics - [YCAS (Yale Center for Analytical Sciences)](https://publichealth.yale.edu/ycas/working/) 
* Help designing and creating data visualizations - email medicaldata@yale.edu 

#### Data Sharing / Retention 
*Generally, research data and materials that are commonly accepted in the scientific community as necessary to validate research findings must be retained by Yale researchers for three (3) years after publication of the findings or all required final reports (e.g., progress and financial) for the project have been submitted to the sponsor.* [Yale Policy 6001 Research Data & Materials Policy](https://your.yale.edu/policies-procedures/policies/6001-research-data-materials-policy#:~:text=Generally%2C%20research%20data%20and%20materials,for%20the%20project%20have%20been) 

Data sharing refers to the process of making data public, typically via a data repository. Data retention refers to storing data so it remains usable, though not nessissarily available to the public. 

## Research Data Management Lifecycle + Constant Themes
In addition to the (sometimes iterative) stages you will progress through during the Research Data, there are also themes that you will need to consider during multiple, if not all, of these phases. 

<img src="https://github.com/CWML/research-data-management-cheat-sheet/blob/main/images/research-data-lifecycle-themes.png" alt="data lifecycle" width="600">

#### Version Control
Version control allows you to see the change history of a file, and to restore a file to a previous iteration. You can apply a manual version control by adding dates or v1/v2/vfinal notations to a file name, or by writing a change log within a READme file. Cloud data storage systems like Box and Google Drive have version control capabilitites (Note: whenever you are exploring a data, or content management system, make a note to check if the system supports version control and how versions are retained).

The most robust and independent way to maintain control over your file versioning is to apply a Version Control System like [Git](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F). 

Support at Yale:
* If you have questions about Git, or would like help getting started with Git or GitHub, email medicaldata@yale.edu.  

#### Documentation
Documentation can include any notes and annotations related to your research data that make your data understandable to others (as well as your future self). Maintaining accurate and useful documentation can make the difference between your data being reusable in future research senarios or not.

Support at Yale:
* Take a look at this additional information about [Codebooks, Data Dictionaries & ReadMe Files](https://github.com/sauuyer/Med-Lib-Data-Classes/blob/master/data-documentation/research_data_documentation.pdf) and email medicaldata@yale.edu with any questions. 

#### Data Storage
When choosing a data storage solution, you should think about how often you will be using this data, if others will need to access this data too, how much a data storage solution will cost, the level of risk associated with your data, the size of your data, and more. 

Support at Yale:
* [This interactive storage finder tool](https://storage-finder.yale.edu/) can help you navigate the various options available to you through Yale. 

#### Data Security 
How can you know which software are cleared for moderate or high risk data? (And what are the classifications of moderate or high risk data?) [Check with Yale Information Security](https://cybersecurity.yale.edu/approved-services)


## Reserach Data Management Lifecycle + Technology
When you start to think about *how* you would actually engage with any of these steps, different technology aspects come into play, along with themes including version control, documentation, and operational data storage. 

<img src="https://github.com/CWML/research-data-management-cheat-sheet/blob/main/images/research-data-lifecycle-2.png" alt="data lifecycle + technology" width = "600">

#### Project Planning Tools
* DMPTool - access and store templated data management plans. [Quick start guide](https://dmptool.org/help) 

#### Data Creation Tools
* Core Research Facilities - Yale’s Core Research Facilities provide Yale researchers access to state of the art scientific instrumentation with the intent to keep Yale’s scientific research at the cutting edge.  Each Core employs highly trained staff that may provide training and assistance with use of instrumentation as well as aid in experimental design. 

#### Data Collection Tools 
* APIs (Application Programming Interfaces)
* Qualtrics - create and deploy 
* Microsoft Excel
* Databases - databases are more robust for storing and organizing interrelated data structures than spreadsheets or tables. Email medicaldata@yale.edu with questions about relational database design and set-up. 

#### Data Processing Tools
* Microsoft Excel - [Excel funtions](https://www.excel-easy.com/data-analysis.html) | [Data processing/analysis in Excel](https://www.excel-easy.com/data-analysis.html)
* Python - email medicaldata@yale.edu for a workshop or tutorial based on your research needs
* R - email medicaldata@yale.edu for a workshop or tutorial based on your research needs
* OpenRefine - [A powerful tool for working with messy data, cleaning it, and transforming it from one format or structure to another](https://openrefine.org/)

#### Data Analysis Tools
* There are many proprietary analysis tools; this document will focus on what you have access to free and/or through Yale
* Find software through the [Yale Software IT Library](https://your.yale.edu/yale-link/software-library) 
* Microsoft Excel - [Excel funtions](https://www.excel-easy.com/data-analysis.html) | [Data processing/analysis in Excel](https://www.excel-easy.com/data-analysis.html)
* Python - email medicaldata@yale.edu for a workshop or tutorial based on your research needs
* R - email medicaldata@yale.edu for a workshop or tutorial based on your research needs
* Learn about different types and categories of graphs via the [Data Viz Catalogue](https://datavizcatalogue.com/)
* Jump start your ability to create data visualizatins in R with [The R Graph Gallery](https://www.r-graph-gallery.com/) 

#### Data Sharing / Retention Tools
* [Interactive storage finder tool](https://storage-finder.yale.edu/)
* Dryad - deposit research data for free through Yale. [More about Dryad](https://datadryad.org/stash#:~:text=Dryad%20is%20a%20nonprofit%20membership,Charges%20help%20ensure%20our%20sustainability.)
* Zenodo - deposit research code and data. [More about Zenodo](https://about.zenodo.org/)


## FAQs
* [Where can I find additional training opportunities?](https://github.com/CWML/research-data-management-cheat-sheet/blob/main/find-training.md) 
* [What are file and folder naming best practises?](https://github.com/CWML/research-data-management-cheat-sheet/blob/main/best-practices/file-and-folder-naming.md)
* [What if I want to make bulk changes to how my files are currently named?](https://github.com/CWML/research-data-management-cheat-sheet/blob/main/best-practices/bulk-renaming-files.md)
* [What are best practises related to file organization?](https://github.com/CWML/research-data-management-cheat-sheet/blob/main/best-practices/file-organization.md) 
* [Where can I connect with peers engaging in biomedical data science research?](https://medicine.yale.edu/cbds/)
* [What about specific topics (training, software, hardware, and collaborative opportunities) in bioinformatics research?](https://library.medicine.yale.edu/bioinformatics)
* [How can you know which software are cleared for moderate or high risk data? (And what are the classifications of moderate or high risk data?) -> Check with Yale Information Security](https://cybersecurity.yale.edu/approved-services) 

Have other questions? Email medicaldata@yale.edu 

