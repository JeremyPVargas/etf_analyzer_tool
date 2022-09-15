# ETF Analyzer Tool

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#purpose">Purpose</a>
      <ul>
        <li><a href="#inputs">Inputs</a></li>
        <li><a href="#outputs">Outputs</a></li>
      </ul>
    </li>
    <li>
      <a href="#technologies">Technologies</a>
      <ul>
        <li><a href="#sql">SQL</a></li>
        <li><a href="#voila">Voila</a></li>
        <li><a href="#pandas">Pandas</a></li>
        <li><a href="#matplotlib">Matplotlib</a></li>
      </ul>
    </li>
    <li><a href="#version-release">Version Release</a></li>
    <li><a href="#how-to-run">How to run</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#license">License</a></li>
        <ul>
        <li><a href="#permissions">Permissions</a></li>
        <li><a href="#disclaimer">Disclaimer</a></li>
        </ul>
    </li>
    <li><a href="#aknowledgements">Aknowledgements</a></li>
</details>

---

<!--Purpose -->
## Purpose
This tool models a financial database and a web application using SQL, Python, and the Voila library to analyze a hypothetical fintech Exchange Traded Fund (ETF).
The application runs on Jupyter notebook and it can be experienced as a single page web based dashboard. 


### Inputs
The application reads financial performance data from one file. Data is used to conduct futher analysis of the funds in comparision to the S&P 500, which is also included in the original Data Frame.

    etf.db


  
### Outputs
    Visualizations:
    - ETF select stock Daily Returns
    - Selected stock cumulative returns 
    - ETF analysis including cumulative portfolio returns
    Reports: 
    - SQL based reports summarized as daily returns.
    Web-Based Dashboard:
    - Single page web based dashboard of the entire application
    
---
<!--Technologies -->
## Technologies
### Python:

    Phyton Version: **3.7.13**

## Libraries and Dependencies

### SQL
[SQL](https://realpython.com/python-requests/)

### Voila
[Voila](https://docs.python.org/3/library/os.html)

### Pandas
[Pandas](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html) 

### Matplotlib
[Matplotlib](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.plot.html)


---
<!--How to run -->
## How to run
1. Clone the repository on a folder that will easy to open
2. File was developed with Jypiter Notebook and Lab
3. Open the file with Jupiter using the Anaconda Navigator
4. Navigate open the folder where the files were cloned to
5. Open the file on JupyterLab


![jupyterlab](./images/anaconda_nav.png)



---
<!--Version Release -->
## Version Release

### Version 1.0


---
<!--Usage -->
## Usage

### Viaualization PYPL Daily Returns:

![pypl_daily](./images/pypl_daily.png)


### Visualization ETF Portfolio - Avg Daily Returns:

![etf_porfolio](./images/etf_portfolio.png)


### Visualization of ETF Cumulative Portfolio Returns:

![etf_cumu](./images/etf_cumu.png)



### ETF Analyzer Web Based Dashboard Video DEMO using the VOILA extension
[![Watch the video](https://i9.ytimg.com/vi/bX0N4Oxk5Uc/mqdefault.jpg?v=6322d473&sqp=CPyvi5kG&rs=AOn4CLCMqAR6Dr6grgWsUaro43k7tdwInA)](https://youtu.be/bX0N4Oxk5Uc)



---
<!--Contributors -->
## Contributors

Jeremy Vargas

    Managing Director
    Resonant Solutions LLC
    email:    jeremyvargas@resonantsolutions.org
    linkedin: https://www.linkedin.com/in/jeremyvargas/

UW FinTech Bootcamp
- Startup code provided by institution

---
<!--License -->
## License
Portfolio Risk Analysis tool is available under an MIT License.

Copyright (c) 2022 - Resonant Solutions, LLC

### Permissions
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
### Disclaimer
The Software is provided “as is”, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the Software.

---
<!--Aknowledgements -->
## Aknowledgements
* [Markdown Guide](https://www.markdownguide.org/basic-syntax/#reference-style-links)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->