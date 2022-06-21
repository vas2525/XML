# XML
 1. Create an external repository called XML.
>GitHub -> Create New Repository XML
 2. Clone the XML repository to the local machine.
>git clone https://github.com/vas2525/XML.git
 3. Inside the local XML, create a “new.xml” file.
>cd XML && touch new.xml
 4. Add file under git.
>git add new.xml
 5. Commit the file.
>git commit -m "add new.xml"
 6. Push the file to an external GitHub repository.
>git push
 7. Edit the content of the “new.xml” file - write information about yourself (name, age, number of pets, future desired salary). Everything is written in XML format.

> vim new.xml
```
 <?xml version="1.0"?>
     <INFO>
        <NAME>VASILII</NAME>
        <AGE>29</AGE>
        <PETS>0</PETS>
        <SALARY>2500</SALARY>
    </INFO>
```
 8. Push changes to an external repository.
>git commit -am "change xml" && git push
 9. Create preferences.xml file
>touch preferences.xml
 10. In the preferences.xml file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in XML format.

> vim preferences.xml
```
<?xml version="1.0"?>
    <INFO>
        <FILM>WHO I am?</FILM>
        <SERIES>Fear Factor</SERIES>
        <FOOD>Cheeseburger</FOOD>
        <SEASON>Summer</SEASON>
        <COUNTRY>USA</COUNTRY>
    </INFO>
```
 11. Create a skills.xml file, add information about the skills that will be studied in the course in XML format
>touch skills.xml

> vim skills.xml
```
 ?xml version="1.0"?>
    <INFO>
        <SKILLS>The best skills</SKILLS>
    </INFO>
```
 12. Make a commit in one line.
> git add . && git commit -m "preferences and skill" 
 13. Send 2 files at once to an external repository.
> git push
 14. Create a bug_report.xml file on the web interface.
> GitHub -> add file -> create new file -> bug_report.xml
 15. Make Commit changes (save) changes on the web interface.
> GitHub -> Commit changes
 16. Modify the bug_report.xml file on the web interface, add a bug report in XML format.
> GitHub -> bug_report.xml -> edit this file
```
 <?xml version="1.0"?>
 <INFO>
    <ID>1</ID>
    <Title>CART - Unable to add new item to a cart</Title>
    <Environment>MacBook Air 2018, MacOS Big Sur, Yandex Browser</Environment>
    <Steps_to_reproduce>
        <Step>Go to product page</Step>
        <Step>Press to 'Add to cart button'</Step>
        <Step>Go to cart</Step>
    </Steps_to_reproduce>
    <Priority>High</Priority>
    <Severity>Critical</Severity>
    <Expected_Result>The cart containes 1 item</Expected_Result>
    <Actual_Result>The cart containes 0 items</Actual_Result>
</INFO>
```
 17. Make Commit changes (save) changes on the web interface.
> GitHub -> commit changes
 18. Synchronize external and local XML repository
> git pull
