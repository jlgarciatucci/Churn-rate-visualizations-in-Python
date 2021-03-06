<h1 align="center">Churn-rate-visualizations-in-Python</h1>
<p align="center">
<img src="BANNER2.png" alt="Figure 1" style="width: 600px;"/>
</p>
<br>Combining my passion for coding and data, I wanted to recreate a data visualization in Tableau that I saw while reading and working on a SQL data analysis training course. This relates to having a view of a company's churn rate in relation to its subscribers.</br>

<br>You can visit the article: "The Churn Dashboard Explained" at www.datarevelations.com where the author Steve Wexler explains how he created the Churn Dashboard visualization in Tableau.Churn rate visualizations in Python</br>

<p align="center">
<img src="10_Original.png" alt="Figure 1"/></br>
<em>Figure 1. Original visualization proposed in Steve Wexler's article</em>
</p>

<br>In this article, I will share with you the code and the result for the proposed waterfall/line chart visualization so as not to make the article too long.</br> 
<br>At the end of the article, you can check both codes on my GitHub page and also the nbviewer links for the Jupyter notebooks.</br>
<br>Keep in mind that the code can certainly be improved, but I would like to share it in case someone like me wants to plot similar charts and could use this as a starting point, as I did not find too many examples online when I searched for this topic.</br>
<br>Let us take the same data from the reference to create the visualization for the churn rates from the reference. This is fictitious data on subscriber gain and loss over the course of a year, assuming that the company starts acquiring subscribers in January.</br>

<p align="center">
<img src="table.png" alt="Table 1"/></br>
<em>Table 1. Fictitious data on subscriber gain and loss</em>
</p>

<br>I used a couple of Numpy arrays to input the data. Due to the amount of data for the example, it is not necessary to read from .csv or other files.</br>

<p align="center">
<img src="code.png" alt="Figure 2" style="width: 800px;"/></br>
<em>Figure 2. Code</em>
</p>
<br>From the code we will get the author's preferred visualization of the running totals.</br>

<p align="center">
<img src="hat_chart1.png" alt="Figure 3" style="width: 1200px;"/></br>
<em>Figure 3. Code output</em>
</p>

<br>I only added a few extras like the legend and some axis information, but I tried to replicate Steve's visualization in Tableau with a few lines in Python.</br>

<br>The power of Python in creating data visualizations is well known and here we can see it. I hope you enjoy this brief explanation of my code and find it useful. If you would like to see both examples, here are the GitHub links and the nbviewer links to the notebooks.</br>

<br>As a second option, I also checked the possibility of displaying a line chart for running totals, as shown below:</br>

<p align="center">
<img src="hat_chart2.png" alt="Figure 4" style="width: 1200px;"/></br>
<em>Figure 4. Second option for visualization</em>
</p>

<br>Please let me know in the comments if you enjoyed the article or found it interesting in any way..</br>




