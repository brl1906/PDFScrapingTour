# PDFScraping
This notebook is part exploration part tutorial resource for public employees or those working with civic data who need to access, organize, analyze information or metadata trapped in PDF documents.

"This one's for you..."
If you need to digitize records, extract information from scanned forms, this is for you.  If you have ever had to manually enter an Excel spreadsheet or had to ask an intern to do it to get at information in a document or report. this is for you. If you do not have a paid service for Optical Character Recognition on scanned documents, this is for you.  If you are working with information you or your department is not comfortable exposing to one of the many free but limited online services that require you to upload your documents into some data-ether for conversion and limit the number of documents you can convert, this is for you.

## Potential Problem Statements or Use Cases
Your department, division or organization:

* is trying to make data publicly available on a certain government service that is only released by that organization as a PDF document

* needs to answer a statistical question about a frequency, standard deviation or some distribution about the occurrence of something that captured in standard formatted PDFs--like what is the average dollar amount of a change order submitted by some department

* pays rental fees for space that is occupied by boxes of paper that could be more efficiently stored if scanned, digitized and stored in a database based on some feature of the document data or structure.

* participates in investigations of events or incidents and often needs to process a significant amount of retrieved scanned PDF documents to prioritize them based on some element of the document metadata or existence of a particular element or string in a scanned document.

* somehow.....got their hands on like 2,156 resumes (scanned & paper) and wants to email each of these people to inform them about the launch of a new government fellowship program opportunity to potentially increase the competitiveness of the applicant pool.


**Fact**: Manual entry sucks and should be abolished!

## Getting Started
```
go get the repo, clone it & explore it
```

### Installing
The requirements.txt file contains the dependencies necessary to run this program from your machine. It also includes the installation of packages required to convert the jupyter notebook code into a slideshow  though this is not necessary or related to any of the PDF stuff.  You can create a virtual environment and run in your terminal the command:
'''pip install -r requirements'''

This assumes that you have created a project folder, changed into that directory, have created a virtual environment there, activated the virtual environment for your project, and are running the above command in that location.
* for example:
  * $ mkdir yourprojectfoldername
  * $ virtualenv yourvenvname
  * $ source yourvenvname/bin/activate
  * $ pip install -r requirements

## Presentation Slides
[Google Slides](https://docs.google.com/presentation/d/1cFwCPy7sZOJU9m-N1tqqfJ3vQWAU1iKO--nA8EfilNE/edit?usp=sharing) for Python Meet Up | Center of Excellence Talk 

## TODO:
* - [x] create initial project readme with problem statement
* - [X] update additional presentation


## Authors
Babila Lima [Business Process Improvement Office](https://generalservices.baltimorecity.gov/business-process-improvement-office)

## Acknowledgements
Nothing happens in a vacum--except carpet cleaning, and even that is debatable. A special thank you goes to the folks that were banging their heads on this problem and lifted them long enough to ask the magic question, is there a way to automate the boring stuff.  

Special shoutout to Evan Cook for asking the original question that sparked this mini-project: 'How do I get the data from page 4 of this 72 page document?'
