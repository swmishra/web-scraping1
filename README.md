**Briefly explain what your code does and specify any inputs and outputs required**

The code scrapes the entire Wikipedia page for "Clark University" and keeps only the headings for each section ('.mw-headline') and removes all of the other text on the webpage as well as the HTML tags.


**Any problems you encountered and how you debugged them**

The one problem that was encountered while scraping the Clark University wikipedia page for headings was to find the class element to obtain the headings. It was fixed by referencing the example provided on the assignment page on GitHub to obtain the class element ('.toctext').


**Any interesting insights you gained from the tutorial**

It was interesting to see how while parsing our soup on 'img' tags it resulted in all images on the web page from small icons, empty images included for layout purposes, the Wikipedia logo, etc. To get images within the article and not everywhere on the web page, images were inspected again to hone in on classes or ids of the specific images that were supposed to be obtained.
