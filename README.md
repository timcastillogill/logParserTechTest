# Challenge

## **What's the Problem You have been set?**

Write a script that:

1. Receives a log as argument (webserver.log is provided) e.g.: ./parser.rb webserver.log
2. Returns the following: <br>
   a) list of webpages with most page views ordered from most pages views to less pageviews e.g.: /home 90 visits /index 80 visits etc...<br>
   b) list of webpages with most unique page views also ordered<br>
   e.g.: /about/2 8 unique views /index 5 unique views etc

### Clarifications:

Lines with end slashes or visits to subpages are counted toward the totals of their parent pages. E.g. /about, /about/ and /about/2 would make 3 visits to /about

### Future Improvements

In the case of a tie for number of visits, lines are sorted alphabetically

### Information

Log [File Formats](https://www.graylog.org/post/log-formats-a-complete-guide#:~:text=What%20Is%20a%20Log%20Format,machine%2Dreadable%20and%20easily%20parsed) The log file supplied as part of this test is a non-standard format, with paths and IP addresses only.

## User Stories

As a
So that I can
I want to

## Installation

To clone the repo

1. Clone the repo
2. cd tech-test
3. bundle

### To run the server

### Rspec Tests

1. cd
2. rspec

## Usage

**Instructions on how to use it. e.g. Where to send POST requests etc.**
