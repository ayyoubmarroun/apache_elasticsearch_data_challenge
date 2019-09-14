# Data Challenge

## Challenge Description
The second challenge is a very well known use case. As in the previous challenge, you arefree to use the language you are most familiar with. What we want from you is that youdevelop a tool that generates a few reports, which will be specified in the following lines,about an unstructured dataset which consists of an Apache2 web server log file. You candownload the dataset from the following URL:

[Raw data](https://raw.githubusercontent.com/elastic/examples/master/Common%20Data%20Formats/apache_logs/apache_logs)

### Restrictions
You cannot import more than 3 third party libraries (without of course countingdependencies).  It is not allowed to use a Database (DBMS), such as MySQL or MongoDB.Please, write a README file explaining how to use your tool, what dependencies it has andany assumptions you have made.

### Mandatory
- Top 10 requested pages and number of made requests for each one
- Percentage of successful requests (anything in the 200s and 300s range)
- Percentage of unsuccessful requests (anything that is not in the 200s or 300s range)
- Top 10 unsuccessful page requests
- The top 10 IPs making the largest number of requests. Please, display the IP address andthe number of made requests
- Your solution must take a parameter which specifies which of the previous reports must bebuilt. A single report must be built per execution of your program (e.g. only the top 10 urls,only the percentage of successful requests and so on). You can call the possible values ofthe parameter as you like, such as TOP_10, TOP_OK, TOP_KO...

### Extra
- Unit tests for your code
- Total number of made requests every minute in the entire time period covered by the provided file
- For each of the top 10 IPs, show the top 5 pages requested and the number of requests for each one

## Challenge output

The challenge has been written using ***python*** and it's compatible with version *3.6.X* or higher. Also you'll need to install all libraries under [requirements.txt](requirements.txt)
