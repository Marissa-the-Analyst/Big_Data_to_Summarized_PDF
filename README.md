# Big_Data_to_Summarized_PDF
I went through thousands of rows to count population and number of census tracts for each county. Automating the data this way, I was able to translate a large complex task into a short script and output it into a useable format for stakeholders!

# Business Questions
- Can you generate a report that shows me states with a total population of 5 mil or more and the breakdown by county?
- Also I need that as a PDF... include a summary chart of the 10 most populated states too while youre at it?

# Finished Product
To read my full project check out my full Kaggle Notebook [here](https://www.kaggle.com/code/marissan/from-large-dataset-to-pdf-report)

**Deliverables**
<br>

- A PDF of all states with a total population of 5mil or more
- A break down of each state's tracts and county populations
- A summary chart at the beginning of the PDF

# Programs 
- Python
- Gemini used as a learning aid and syntax helper

# Data Source
I used *How to Automate the Boring Stuff* by Al Sweigart's Chapter 14's Excel Spreadsheets sample census data. 

# Opportunities
I would have liked to have drawn more conclusions and create a more usable report! The scope of this project was pretty narrow, tailoring the focus on just automating a large task, but taking the census data and outputting a throughouly formatted PDF could help stakeholders make more use of the data itself.

# Reflection
It was really enjoyable seeing how the weasyprint package allowed HTML to be incorporated into Python code as well as how you can use Openpyxl over pandas to have more native workbook support. I'd definitely like to go down that rabbit hole more to explore what areas of Openpyxl (perhaps conditional formatting?) could open up over the more general, but quicker, pandas. Additionally working more with the OS package to manipulate and create new files instead of just digging into already existing ones. This type of work is more closely aligned with what could be expected in a real world environment and I look forward to uncovering more insights and reports that can help people see the *point* of data faster! 
