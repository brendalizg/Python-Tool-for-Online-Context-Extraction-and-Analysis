# Python-Tool-for-Online-Context-Extraction-and-Analysis
Hello! Welcome to the Tool for Online Extraction and Content Analysis with Python!
The code is divided into four main parts which are indicated by comments.
  1. Data Extraction
  2. Data Cleaning
  3. Word Frequency
  4. Word Cloud Creation
     
When you run the code you will have to provide two inputs. 
1. The first input is the URL specifically from Doctor.com. (Example: https://www.doctor.com/Ezra-Trachtenberg?utm_source=doctor)
2. The second input is the path where your files and code will be located. It should be copied in this format: C:\Users\brend\Documents\MSIE_Brendaliz\Spring 2023
   
**After you have introduced these two inputs the code will extract and process the data automatically!**

_Possible changes to the code:_
  # Data from another website
    Want to extract data from another website? Focus on lines 20 and 25.
    When extracting data from a website you need to inspect it. 
    Right click on the website and select inspect. 
    You will be able to hover over the html file and see exactly what part of the webiste you want to extract.
    Once you have identified which part, identify which is the div class. Insert the class in line 20.
    Then you will have to travel down that div to the specific text that you want to extract, the path for that text will be inserted in line 25.
    Example: div.p.next_sibling.next_sibling.string
    
 # Want to analyze a text file?
  You will need line 7 an example and line 31.
  To analyze your text file convert everything from line 4 to 28 to a comment.
  Identify the path of your text file in your computer and add it on line 31 on the first argument of open() in the format seen in line 7.
  You will have to add the name of your text file at the end of the path.
  Example: r'C:\Users\brend\Documents\MSIE_Brendaliz\Spring2022\ININ6999\Python\Dr-Smith.txt'
  Run the code and it will analyze your text data.
  
  # Want to obtain only word frequency outputs and not wordcloud?
  Hide lines 97 and further
  
  # Want to obtain only word cloud outputs and not word frequency?
  Hide lines 62 to 94.

  **Enjoy! If you have any further question please do contact me.
  Brendaliz Gonzalez Morell
  brendaliz.gonzalez3@upr.edu**
