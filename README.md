# b9122_homework2
Computing for Business Research Course 
Author info:
name: Fei Luan
Master Program: Business Analytics at Columbia University
The first file is the course script for web crawling, and the following personal assignment file is based on that course script to extract urls with text 'covid'and'charges' in it. The basic logics and steps are 1. queue of urls to crawl 2. stack of urls seen so far 3. we keep track of seen urls so that we don't revisit them 4.set the maximum number of urls to visit 5. dequeue a URL from urls and try to open and read it 6. IF URL OPENS, CHECK WHICH URLS THE PAGE CONTAINS 7. ADD THE URLS FOUND TO THE QUEUE url and seen 8. Put child URLs into the stack 9. find tags with links 10. extract just the link. In the course script, Professor took columbia business school website as an example. In the assignment, we are asked to find at least 10 url links with 'covid' text in the website https://www.federalreserve.gov/newsevents/pressreleases.htm and top 20 url links with 'charges' text in the website https://www.sec.gov/news/pressreleases. 
