# Practice Quiz: Automatically generate a PDF and send it by email
**Total points:** 10
**Score:** 100%

## Question 1
What is the overall purpose of the emails.py script in the lab? Select all that apply. 

- **To send an email message to an SMTP server.**
- To check for incoming email messages.
- **To define the structure of an email message.**
- To set the priority of an email message to high.

## Question 2
What step must you complete before you can run the example.py script?

- ./scripts/example.py
- cat ~/scripts/example.py
- **sudo chmod o+wx ~/scripts/example.py**
- ls ~/scripts

## Question 3
What do you use the Linux cat command for? 

- **To display the contents of a file on the screen.**
- To run a Python script.
- To output to a specific file.
- To edit a file.

## Question 4
In the lab, you must modify the script cars.py to calculate which car model had the most sales. What command can you use to simply view the contents of the cars.py script? 

- grep ~/scripts/cars.py
- sudo ~/scripts/cars.py
- chmod ~/scripts/cars.py
- **cat ~/scripts/cars.py**

## Question 5
You’ve edited the cars.py script to generate the cars.pdf but find that all the information in the PDF is on a single line. What should you do to fix the report?

- Edit the cars_dict_to_table function to include <br/> between the lines.
- Edit the reports.generate function to include <br/> between the lines.
- Edit the format_car method to include <br/> between the lines.
- **Edit the process_data function to include <br/> between the lines.**

## Question 6
In the example.py script, what is the purpose of the three import commands? 

- To retrieve the data needed for the PDF. 
- To retrieve another script and execute it before the example.py script runs.
- **To enable a script to use commands from an imported module.**
- To convert the data into the correct format for the PDF.

## Question 7
What is the purpose of the reportlab library? 

- **To format the report.**
- To format the body of email messages.
- To define the filename of the report.
- To attach a report to an email.

## Question 8
What is the purpose of the following commands from the reports.py script? Select all that apply. 

```python
import reportlab
from reportlab.platypus import SimpleDocTemplate
```

- **To import the reportlab library.**
- To create the PDF.
- To specify the format of the PDF.
- To specify the format of the email message.

## Question 9
In the cars.py script, what is the purpose of the format_car function? 

- **To display the car make, car model, and car year.**
- To display the car make and price.
- To display the car ID, car make, car model, and car year information.
- To display the car model and car year.

## Question 10
Which commands must be included in your script if you want to send an email? Select all that apply. 

- **emails.send**
- **import emails**
- reports.generate
- **emails.generate**