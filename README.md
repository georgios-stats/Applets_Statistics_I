

------------------------------------------------------------------------

# About:

This repository contains part of the teaching material for the module MATH1541 Statistics (now obsolete).


***Computer practicals classes***

-   '[Computer_Practicals](https://github.com/georgios-stats/Statistics_I/tree/master/Computer_Practicals)' folder contains the material for your computer practicals


***Web-applets***

-   '[Web_applets](https://github.com/georgios-stats/Statistics_I/tree/master/Web_applets)' folder contains the source code of some of the web applets used in the lectures.




------------------------------------------------------------------------

# How to download:


### To download the whole repository

Ways:

1. You can click [[HERE](https://github.com/georgios-stats/Statistics_I/archive/master.zip)].

2. You can click the green button 'Clone or download' and download it as a zip file

3. You can use the program 'git' (<https://git-scm.com/>):
    
    -   in windows/linux: 
    
        download and install git from https://git-scm.com/
    
    -   in Debian linux run in the terminal: 
    
        sudo apt-get install git
    
    -   in Red Hat linux run in the terminal: 
    
        sudo yum install git
    
    ... then run:

    -   git clone https://github.com/georgios-stats/Statistics_I.git

4. You can use rstudio:

    1.  Go to File &gt; New Project &gt; Version Control &gt; Git
    
    2.  In the section *Repository URL* write
        
        -   <https://github.com/georgios-stats/Statistics_I.git>
        
        -   … and complete the rest as you wish
    
    3.  Hit *Create a Project*

### To download a specific folder only

Ways:

1. You can use the GitZip add-on for Firefox available [HERE](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&cad=rja&uact=8&ved=2ahUKEwias52xjd3nAhXPUs0KHeXHCEUQFjACegQIAhAB&url=https%3A%2F%2Faddons.mozilla.org%2Fen-US%2Ffirefox%2Faddon%2Fgitzip%2F&usg=AOvVaw37servrJ29tuNcx9dIQDqy) or the Chrome add-on GitZip available [HERE](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=2&cad=rja&uact=8&ved=2ahUKEwias52xjd3nAhXPUs0KHeXHCEUQFjABegQIARAB&url=https%3A%2F%2Fchrome.google.com%2Fwebstore%2Fdetail%2Fgitzip-for-github%2Fffabmkklhbepgcgfonabamgnfafbdlkn%3Fhl%3Den&usg=AOvVaw1Pn3VXuXz1Fphl7dsPEhDS)

    1. In install [Firefox GitZip add-on](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&cad=rja&uact=8&ved=2ahUKEwias52xjd3nAhXPUs0KHeXHCEUQFjACegQIAhAB&url=https%3A%2F%2Faddons.mozilla.org%2Fen-US%2Ffirefox%2Faddon%2Fgitzip%2F&usg=AOvVaw37servrJ29tuNcx9dIQDqy) or the [Chrome GitZip add-on](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=2&cad=rja&uact=8&ved=2ahUKEwias52xjd3nAhXPUs0KHeXHCEUQFjABegQIARAB&url=https%3A%2F%2Fchrome.google.com%2Fwebstore%2Fdetail%2Fgitzip-for-github%2Fffabmkklhbepgcgfonabamgnfafbdlkn%3Fhl%3Den&usg=AOvVaw1Pn3VXuXz1Fphl7dsPEhDS)  

    2. Double click on the items you need.  
    
    3. Click download button at bottom-right.  
    
    4. See the progress dashboard and wait for browser trigger download.  
    
    5. Get the ZIP file.  

2. You can use 'git' (<https://git-scm.com/>). 

    E.g., assume you wish to download the sub-folder 'Computer_Practicals':

    -   run in the terminal the following:
        
        *mkdir Statistics_I  
        cd Statistics_I  
        git init  
        git remote add -f origin https://github.com/georgios-stats/Statistics_I.git  
        git config core.sparseCheckout true  
        echo "Computer_Practicals/*" >> .git/info/sparse-checkout  
        git pull origin master*

### To download a specific file

1. You can just navigate to the file from the browser and download it.

2. You can use the GitZip add-on for Firefox available [HERE](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&cad=rja&uact=8&ved=2ahUKEwias52xjd3nAhXPUs0KHeXHCEUQFjACegQIAhAB&url=https%3A%2F%2Faddons.mozilla.org%2Fen-US%2Ffirefox%2Faddon%2Fgitzip%2F&usg=AOvVaw37servrJ29tuNcx9dIQDqy) or the Chrome add-on GitZip available [HERE](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=2&cad=rja&uact=8&ved=2ahUKEwias52xjd3nAhXPUs0KHeXHCEUQFjABegQIARAB&url=https%3A%2F%2Fchrome.google.com%2Fwebstore%2Fdetail%2Fgitzip-for-github%2Fffabmkklhbepgcgfonabamgnfafbdlkn%3Fhl%3Den&usg=AOvVaw1Pn3VXuXz1Fphl7dsPEhDS)


------------------------------------------------------------------------

