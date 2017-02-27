# STA141b-Project: Recent Job Market Analysis
2017-02-03

### Group members: 
Da Xue, Jiewei Chen

### Data source: 
<li> Aggie Job Link </li>
<li> www.indeed.com/ </li>
<li> linkedin </li>
<p> (restricted to CA, one-day) </p>

### What to explore: 
<li> Job posts across majors </li>
<li> Salary levels across majors </li>
<li> Skill requirements </li>
<li> Degree requirements </li>
<li> Internship vs full-time position demands </li>
<li> Company locations that have active job posts </li>


### Log: 02/03/2017
First attemp by using Beautiful Soup

### Log: 02/06/2017
Edit project recipe for future discussion with instructors

### Log: 02/08/2017
Together: understand api of indeed

<br> Jiewei: write function to obtain data from api of indeed
<br> Da: parse city names of california using beautifulsoup

### Log: 02/21/2017 - 02/22/2017
Jiewei: web scraping 5000 job post for "Data Analyst", "CA", "Internship"

### Log: 02/26/2017
Jiewei: get **Key words** for further extracting qualification key words

### Log: 02/26/2017
#### Discussion:
<li> `post_summary` group by company to find companies with most job posts </li>
<li>  Find a way to denote unsuccessful data parsed </li>
<li>  Tokenize - bi-gram </li>

#### Question:
Not able to extract job description for some posts. <a href = "https://www.indeed.com/viewjob?jk=2597a304d86609fc&qd=N2J-naHqk5bSExrJs-uSyH9HAx4PLUCTZQfXawpJOgkOVqMCVMkmCS8enUuplbB-4rYdC8l5t_9_l80gUVoC8ASNtTMq3B26cxHbEL5qrrg1Vu4aS9dH_tvzuwb-B6Jr&atk=1b9hm0f13af35cn0&utm_source=publisher&utm_medium=organic_listings&utm_campaign=affiliate"> One example </a>. The BeautifulSoup object does not contain the `ul` tags.

How to summarize skills?

#### Ultimate goals ( on paper )

