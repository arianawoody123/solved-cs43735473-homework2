Download Link: https://assignmentchef.com/product/solved-cs4373_5473-homework2
<br>
Notice: <em>Given the nature of on-line course, we will require you to practice using Words, Markdown, or HTML to write and format your homework solutions (no scanned smeared image please). It will prepare you for taking the on-line exams, where only a Words style editor (with HTML support) is available.</em>

<ol>

 <li> (Smoothing) Write functions that use the cut() and qcut() functions provided by DataFrame to smooth data in a given column using the following methods. Apply these function on column F.

  <ul>

   <li>Equal-depth binning with bin means for depth <em>k</em>, for example <em>k </em>=100.</li>

   <li>Equal-depth binning with bin boundaries for depth <em>k</em>, for example <em>k </em>=100.</li>

   <li>Equal-width binning with bin median for 10</li>

  </ul></li>

 <li>(Data Reduction) Write a function that takes a DataFrame, a set of column names (of numeric columns), and an integer <em>p </em>(less than the total number of columns in the table), and use PCA method in Scikit-Learn (specifically, sklearn.decomposition.PCA) to reduce the set of columns into <em>p </em>new columns. Apply this function to reduce the columns {C, D, E, F} into two columns p1, and p2.</li>

 <li> (Correlation) For this question, you will need to use packages scipy.stats

  <ul>

   <li>Compute the covariance and the correlation coefficient for each pair of the numericcolumns.</li>

   <li>Use the crosstab() function to construct the contingency table for columns A and B,similar to the following sample, where the distinct values in attribute A are {<em>a</em><sub>1</sub><em>,a</em><sub>2</sub>} and in attribute B are {<em>b</em><sub>1</sub><em>,b</em><sub>2</sub><em>,b</em><sub>3</sub>} (this is just a sample and may not be the same as Computer Science 4373/5473 <em>Assignment 2  </em>August 10, 2020</li>

  </ul></li>

</ol>

the data in your data file). Write a sequence of Python code to perform the Pearson’s chi-square (<em>χ</em><sup>2</sup>) test of independence with a confidence level of 0<em>.</em>001 to determine if the two attributes are correlated. You should use stats.chi2() to get the <em>χ</em><sup>2 </sup>distribution. Print sufficient information to report the result of the test.

<table width="154">

 <tbody>

  <tr>

   <td width="27"> </td>

   <td width="32"> </td>

   <td width="31"> </td>

   <td width="31">A</td>

   <td width="32"> </td>

  </tr>

  <tr>

   <td width="27"> </td>

   <td width="32"> </td>

   <td width="31"><em>a</em><sub>1</sub></td>

   <td width="31"><em>a</em><sub>2</sub></td>

   <td width="32">all</td>

  </tr>

  <tr>

   <td rowspan="4" width="27">B</td>

   <td width="32"><em>b</em><sub>1</sub></td>

   <td width="31">??</td>

   <td width="31">??</td>

   <td width="32">??</td>

  </tr>

  <tr>

   <td width="32"><em>b</em><sub>2</sub></td>

   <td width="31">??</td>

   <td width="31">??</td>

   <td width="32">??</td>

  </tr>

  <tr>

   <td width="32"><em>b</em><sub>3</sub></td>

   <td width="31">??</td>

   <td width="31">??</td>

   <td width="32">??</td>

  </tr>

  <tr>

   <td width="32">all</td>

   <td width="31">??</td>

   <td width="31">??</td>

   <td width="32">??</td>

  </tr>

 </tbody>

</table>