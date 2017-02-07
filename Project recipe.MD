# STA141b-Project: Recent Job Market Analysis

### Some comments:
<ul> Static data and off-line analysis </ul>
<ul> Data source: <href> https://www.indeed.com/ </href>

<ol start = "1">
  <h2> <li> Data collection </li> </h2> 
    <ol>
        <h3> <li> DataFrame initialization </li> </h3>
          Create a data frame to store data. 
          <table style="width:100%">
          <tr>
            <th>Company</th>
            <th>Job title</th> 
            <th>Major</th>
            <th>Job type</th>
            <th>Salary</th>
            <th>Degree requirement</th>
            <th>Company location</th>
            <th>Skills</th>
          </tr>
          <tr>
            <td> Indeed  </td>
            <td> Data Scientist </td> 
            <td> Computer Science, Operations Research, Statistics, Econometrics or Mathematics </td>
            <td> Full time</td>
            <td></td> 
            <td> Ph.D. or M.S. </td>
            <td> San Francisco, CA 94102 </td>
            <td> R, Python, Julia, Octave, Hadoop, Pig, Scala, Spark</td> 
          </tr>
        </table>
        
        <h3> <li> Web scraping</li> </h3> 
            <br> Step 1: Restrict to "What = Data scientist", "Where = CA" ("Major" ignored for now) </br>
            <br> Step 2: Read html from url </br> 
            <br> Step 3: Parse "Job title", "Company", "Company location", "Job type", url for each post </br>
            <br> Step 4: For each post, read html from url  --> Parse "Salary", "Degree requirement", "Skills" </br>
            
        <h3> <li> Data cleaning </li> </h3>
            <table style="width:100%">
              <tr>
                <th>Company</th> <th> Doesn't really matter. May be used for counting post frequencies. </th>
              </tr>
              <tr>
                <th>Job title</th> <th> Doesn't really matter. Key words may matter. </th>
              </tr>
              <tr>
                <th>Major</th> <th> Would be used for comparisons using pie or bar charts. <br> Q: most posts have more than one majors. </br></th>
              </tr>
              <tr>
                <th>Job type</th> <th> Full time, Internship, co-op, etc.. </br></th>
              </tr>
              <tr>
                <th>Salary</th> <th> No need for cleaning. Pay attention to NaN. </th>
              </tr>
              <tr>
                <th>Degree requirement</th> <th> </th>
              </tr>
              <tr>
                <th>Company location</th> <th> </th>
              </tr>
              <tr>
                <th>Skills</th> <th> Natuaral language processing? </th>
              </tr>
            </table>
                
    </ol>

  <h2> <li> Data analysis and visuallization </li> </h2>
</ol>
