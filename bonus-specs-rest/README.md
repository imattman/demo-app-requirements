# Bonus Functionality for RESTful Projects

Add additional RESTful endpoints that expose usage and statistical data about the service:

Example:

- GET application statistics including (where applicable)
  - Overall size of dataset including length of longest and shortest entries
  - Number of successful/unsuccessful requests processed since application start
  - Top N scoring requests
  - Relevant K<sup>th</sup> percentile slow match times

Include an `X-process-time` HTTP header with the processing execution time in all reponses.

