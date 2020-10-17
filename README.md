# aipscraper
Task � RESTful API endpoint
Implement the RESTful endpoint API, which makes concurrent calls to the following websites:

https://www.result.si/projekti/
https://www.result.si/o-nas/
https://www.result.si/kariera/
https://www.result.si/blog/

1. The input data for the endpoint is �integer�, which represents the number of threads/goroutins
to the above web pages (min 1 represents all consecutive calls, max 4 represents all concurrent calls).

2. Extract a short title text from each page and save this text in a common global structure (array, map �).
The program should also count successful calls.

3. Finally, the service should display the number of successful calls,
the number of failed calls and the saved titles from all web pages.