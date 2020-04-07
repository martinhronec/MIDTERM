# MIDTERM

## Data Processing in Python: MIDTERM EXAM
You have until 20:00 (105 minutes). "Open browser" but NO COMMUNICATION between students.

Using following [Discworld Wikipedia page](http://wiki.lspace.org/mediawiki/List_of_Pratchett_characters):

1. Scrape urls linking to the (individual wikipedia pages of) Major Discworld characters that are related to `Ankh-Morpork` and `The Watch`.

(Hint: `lis = soup.find('span',{'id':'Unseen_University_and_the_Wizards'}).parent.previous.previous.parent.parent.parent.find_all('li')`)

2. Then, get DataFrame linking the particular character with the book he is appearing in. DataFrame should contain two columns: 
    * Name of the book (`book`)
    * Name of the character (`character_name`)
    
(Hint: The list of books of each characters are stored in the table in upper-right corner of the page and its link always contain string Book:)

3. Answer following questions:

    a. How many characters is reported in the book `Men at Arms`?
    
    b. In how many books appear both `Visit-The-Infidel-With-Explanatory-Pamphlets` and `Evadne Cake`?
    
    
### Evaluation criteria
1. Submit as GitHub repository (last commit timestamp at 20:00 will be taken) with Jupyter Notebook with description (2pts)
        send link to jan.sila@fsv.cuni.cz and martin.hronec@fsv.cuni.cz with subject
         f'PythonDataIES Midterm - {your_name}'
2. An independent class for downloader with appropriate functions and attributes (5pts)
    class representing scraped object with appropriate functions and attributes (5pts)
3. Pandas dataframe with results saved as an attribute in the downloader object (5pts)
4. Answers to the asked questions (5pts)
5. Appropriate comments (3pts)

