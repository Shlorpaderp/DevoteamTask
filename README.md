# Theorhetical WebScraping Software
## Version 1.0

This document will lead you through a simplified, high-level view of the program's architecture and functions, as well a general testing plan going forward.

## Features:

- Webpage scraping geared towards Retail Websites
- Queues a list of webpages to scrape
- Allows for user-defined scraping parameters
- Parallel save files, multiple formats and access to a database

### Architecture:

[Contribution guidelines for this project](diagrams/softwarearc,jpg)



### Software Instructions:

Firstly, you should prepare the link source file:
1. Open your browser and find a retailer webpage which will serve as the target for our software.
2. Once you've identified the webpages, open the text file (webpagelinks.txt)
3. Paste the links in the text file, on line at a time.
4. Save and close the text file.

Now that you have a link source file set up, let's start the program:
1. To start the program, open the executable in the main directory: WebScraper.exe
2. In WebScraper, press the "OPTIONS" button, and setup the parameters for the scraping.
3. By default, the link source file is webpagelinks.txt, you may choose a different file location.
4. _Delimeters and other parameters_
5. Select one or multiple save locations and formats
6. Press "Save Options"
7. Press "Scrape"
8. If successful, a message should appear - "Success" - the scraped data should appear saved as per configuration.


## Testing Flowchart:

[Contribution guidelines for this project](diagrams/testplan.png)


### Unit Testing:
- Whitebox testing
- Verify that all components work on an individual level, use stubs and drivers as necessary to verify functionality.
- Check for possible vulnerabilities in the code

### Integration Testing:

- Whitebox Testing
- Test how each module / component interacts with one another.

### System Test:

- Blackbox Testing
- Run the program as a whole
- Assess the performance and efficiency of the program
- Note the outputs

### User and Tech Acceptance Test:
- Final stage
- Allow a subset of a potential userbase to test the software
- Collect feedback


