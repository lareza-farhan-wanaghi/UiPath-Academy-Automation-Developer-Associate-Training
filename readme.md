# UiPath Academy Automation Developer Associate Training

This repository contains my solutions for various exercises from the UiPath Academy’s Automation Developer Associate Training course. Each folder represents a chapter, with subfolders corresponding to individual exercises. Screenshots of the solutions are also included for reference. Below is a summary of the exercises:

## A. Data Manipulation with Strings in Studio

1. **Extract Email Address Using String Methods**  
   A workflow that extracts and displays the email address from a string using string methods.

    ![alt text](images/image.png)

2. **Extract Email Address Using Regex**  
   A workflow that extracts all email addresses from a provided template file using regular expressions.

    ![alt text](images/image-1.png)

3. **String Manipulation Using String Activities**  
   A workflow that extracts an employee's first and last name from a text file, and uses this information to complete a message:
   _"Hello Mr/Ms/Mrs `<first_name> <last_name>`, we would like to invite you to our product launch event next week. Please confirm by the end of the week."_

    ![alt text](images/image-2.png)

## B. Data Manipulation with Lists and Dictionaries in Studio

1. **Using Lists**  
   Given a list of countries, this workflow sorts them alphabetically and prints the first three countries in descending order.  
   _Input_: `{"Germany", "Spain", "Japan", "Brazil", "India", "China"}`  
   _Output_: `Spain, Japan, India`

    ![alt text](images/image-3.png)

2. **Using Dictionaries and Integers**  
   This exercise calculates the number of Tour de France victories for each winner using a dictionary.  
   _Input_: A dictionary of winners from 2006–2018.  
   _Output_: Displays each winner and their number of victories.

    ![alt text](images/image-4.png)

## C. UI Automation Synchronization with Studio

1. **Check App State and Verify Execution**  
   A workflow that checks if a user is logged into the ACME page, and if so, navigates to the "Add New Vendor" section. If not, it logs an error message.  
   _Vendor details_:  
   - Vendor ID: 10001  
   - Vendor Name: Ironman Inc  
   - Address: 1 MG Road, Bengaluru, India

    ![alt text](images/image-5.png)
    ![alt text](images/image-6.png)

## D. UI Automation Descriptors in Studio

1. **Fix My Workflow**  
   A troubleshooting task where the workflow is corrected to search for the movie "Ice Age" on IMDb, retrieve the rating, and display it.

    ![alt text](images/image-7.png)
    ![alt text](images/image-8.png)

2. **Fine-tuning the Descriptor**  
   Enhances the previous workflow by allowing user input for the movie title, searches IMDb, retrieves the rating, and displays it.

    ![alt text](images/image-9.png)
    ![alt text](images/image-10.png)

## E. Selectors in Studio Deep Dive

1. **Highlight WFT Type Items on ACME**  
   This exercise highlights specific workflow types (WI1–WI5) on the ACME Work Items page, based on user input.

    ![alt text](images/image-11.png)
    ![alt text](images/image-12.png)

## F. Debugging in Studio

1. **Fix My Workflow**  
   Debug a workflow that inputs data into the RPA Challenge website after reading it from an Excel file, correcting execution errors.

    ![alt text](images/image-13.png)
    ![alt text](images/image-14.png)

## G. Error and Exception Handling in Studio

1. **Try Catch**  
   A workflow that calculates the difference between "Cash In" and "Cash Out" values from an Excel file, using Try-Catch blocks to handle conversion errors.

    ![alt text](images/image-15.png)
    ![alt text](images/image-16.png)

2. **Retry Scope**  
   Automates a process where the workflow retries opening a Notepad application based on a random variable, handling failure scenarios effectively.

    ![alt text](images/image-17.png)
    ![alt text](images/image-18.png)

## H. Working with Local Files and Folders in Studio

1. **File and Folder Automation**  
   A workflow that extracts, renames, and sorts contract and invoice files into corresponding folders based on company names.

    ![alt text](images/image-19.png)
    ![alt text](images/image-20.png)

## I. Email Automation with Studio

1. **Email Filtering and Sending**  
   Automates retrieving unread emails from the last 30 days with "Invoice" in the subject, and generates a report with email details, sending it as an attachment.

    ![alt text](images/image-21.png)
    ![alt text](images/image-22.png)

## J. PDF Automation with Studio

1. **Extract Data from PDFs**  
   A workflow that extracts the date and total from scanned PDFs and writes the information into an Excel file.

    ![alt text](images/image-23.png)
    ![alt text](images/image-24.png)

2. **Extract Data from Multiple PDFs**  
   A similar workflow to extract invoice details (number, date, and total) from multiple native PDF files.

    ![alt text](images/image-25.png)
    ![alt text](images/image-26.png)

## K. Data Manipulation with Data Tables in Studio

1. **Calculating Sums**  
   A workflow that adds the values from two columns and writes the result into a third column.

    ![alt text](images/image-27.png)
    ![alt text](images/image-28.png)

2. **Calculating Expense Percentages**  
   A workflow that consolidates expenses from various payment methods and calculates each category's percentage of the total expenses.

    ![alt text](images/image-29.png)
    ![alt text](images/image-30.png)

## L. Working with Orchestrator Resources

1. **Using Orchestrator Resources**  
   Updates an automation project to retrieve the ACME URL from the Orchestrator.

    ![alt text](images/image-31.png)
    ![alt text](images/image-32.png)

2. **Using Queues**  
   Automates the insertion of account details from an Excel file into ACME Bank, using a dispatcher-performer model with Orchestrator queues.

    ![alt text](images/image-33.png)
    ![alt text](images/image-34.png)
    ![alt text](images/image-35.png)
    ![alt text](images/image-36.png)

## M. UiPath Integration Service Overview

1. **Integration with Google Drive and Gmail**  
   An automation that triggers when a file is uploaded to Google Drive, sending email notifications using Gmail with data derived from an Excel file.

    ![alt text](images/image-37.png)
    ![alt text](images/image-38.png)
    ![alt text](images/image-39.png)

## N. Workflow Analyzer in Studio

1. **Project Analysis**  
   A task to identify and solve errors and warnings in a workflow using the Workflow Analyzer.

    ![alt text](images/image-40.png)

## O. RPA Testing with Studio

1. **Automating and Testing Hashing**  
   A data-driven RPA test case that verifies hash codes for the keyword "UiPath" using different hash methods like MD5, CRC32, etc.

    ![alt text](images/image-41.png)

