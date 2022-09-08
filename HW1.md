<body>

<h1 id="hw-1-cs-625-fall-2022">HW 1, CS 625, Fall 2022</h1>
<p>Jarrold Fowler Sep 08, 2022 6:40pm</p>
<h2 id="git-github">Git, GitHub</h2>
<ol style="list-style-type: decimal">
<li><p>*What is your GitHub username? Jarrold-Fowler</p></li>
<li><p>*What is the URL of your remote GitHub repo (created through
Mr.&nbsp;Kennedy’s exercises)? Jarrold-Fowler/620-ODU</p></li>
</ol>
<h2 id="r">R</h2>
<p>The command below will load the tidyverse package. If you have
installed R, RStudio, and the tidyverse package, it should display a
list of loaded packages and their versions.</p>
<div class="sourceCode" id="cb1"><pre class="sourceCode r"><code class="sourceCode r"><span id="cb1-1"><a href="file:///C:/Users/jarro/AppData/Local/Temp/RtmpCEjZwt/preview-39085c0824e9.html#cb1-1" aria-hidden="true" tabindex="-1"></a><span class="fu">library</span>(tidyverse)</span></code></pre></div>
<pre><code>## ── Attaching packages ─────────────────────────────────────── tidyverse 1.3.2 ──
## ✔ ggplot2 3.3.6      ✔ purrr   0.3.4 
## ✔ tibble  3.1.8      ✔ dplyr   1.0.10
## ✔ tidyr   1.2.0      ✔ stringr 1.4.1 
## ✔ readr   2.1.2      ✔ forcats 0.5.2 
## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
## ✖ dplyr::filter() masks stats::filter()
## ✖ dplyr::lag()    masks stats::lag()</code></pre>
<h2 id="r-markdown">R Markdown</h2>
<ol style="list-style-type: decimal">
<li><em>Create a bulleted list with at least 3 items</em>
<ul>
<li>Masters of Data Science</li>
<li>Masters of Business Administrations</li>
<li>Bachelor’s of Arts Business Administration</li>
</ul></li>
<li><em>Write a single paragraph that demonstrates the use of italics,
bold, bold italics, code, and includes a link. The paragraph does not
have to make sense.</em></li>
</ol>
<p>Hi! My name is <em><strong>Jarrold Fowler</strong></em> and I am
working on my <strong>Master’s of Data Science</strong> degree here at
<em>ODU</em>. This will be my <code>degrees = 1 +2 print degrees</code>
as I work towards my PH.D eventually! You can check out <a href="https://github.com/Jarrold-Fowler/620-ODU">My repo for CS 620</a>
here!</p>
<ol start="3" style="list-style-type: decimal">
<li><em>Create a level 3 heading</em> ### This creates a Level 3
Heading</li>
</ol>
<h2 id="r-1">R</h2>
<h4 id="data-visualization-exercises">Data Visualization Exercises</h4>
<ol style="list-style-type: decimal">
<li>(Q2) <em>How many rows are in mpg? How many columns?</em> There are
234 rows and 11 columns 234x11</li>
<li>(Q4) <em>Make a scatterplot of hwy vs cyl.</em> <img src="data:image/png;base64,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" alt="image"></li>
</ol>
<h4 id="workflow-basics-exercises">Workflow: basics Exercises</h4>
<ol style="list-style-type: decimal">
<li>(Q2) <em>Tweak each of the following R commands so that they run
correctly (<code>library(tidyverse)</code> is correct):</em></li>
</ol>
<div class="sourceCode" id="cb3"><pre class="sourceCode r"><code class="sourceCode r"><span id="cb3-1"><a href="file:///C:/Users/jarro/AppData/Local/Temp/RtmpCEjZwt/preview-39085c0824e9.html#cb3-1" aria-hidden="true" tabindex="-1"></a><span class="fu">library</span>(tidyverse)</span>
<span id="cb3-2"><a href="file:///C:/Users/jarro/AppData/Local/Temp/RtmpCEjZwt/preview-39085c0824e9.html#cb3-2" aria-hidden="true" tabindex="-1"></a><span class="fu">ggplot</span>(<span class="at">data =</span> mpg) <span class="sc">+</span> </span>
<span id="cb3-3"><a href="file:///C:/Users/jarro/AppData/Local/Temp/RtmpCEjZwt/preview-39085c0824e9.html#cb3-3" aria-hidden="true" tabindex="-1"></a>  <span class="fu">geom_point</span>(<span class="at">mapping =</span> <span class="fu">aes</span>(<span class="at">x =</span> displ, <span class="at">y =</span> hwy)) <span class="co"># data was spelled incorrectly</span></span>
<span id="cb3-4"><a href="file:///C:/Users/jarro/AppData/Local/Temp/RtmpCEjZwt/preview-39085c0824e9.html#cb3-4" aria-hidden="true" tabindex="-1"></a></span>
<span id="cb3-5"><a href="file:///C:/Users/jarro/AppData/Local/Temp/RtmpCEjZwt/preview-39085c0824e9.html#cb3-5" aria-hidden="true" tabindex="-1"></a><span class="fu">filter</span>(mpg, <span class="at">cyl =</span> <span class="dv">8</span>) <span class="co"># Filter was spelled incorrectly</span></span>
<span id="cb3-6"><a href="file:///C:/Users/jarro/AppData/Local/Temp/RtmpCEjZwt/preview-39085c0824e9.html#cb3-6" aria-hidden="true" tabindex="-1"></a></span>
<span id="cb3-7"><a href="file:///C:/Users/jarro/AppData/Local/Temp/RtmpCEjZwt/preview-39085c0824e9.html#cb3-7" aria-hidden="true" tabindex="-1"></a><span class="fu">filter</span>(diamonds, carat <span class="sc">&gt;</span> <span class="dv">3</span>) <span class="co"># diamond was missing an (s)</span></span></code></pre></div>
<h2 id="google-colab">Google Colab</h2>
<ol style="list-style-type: decimal">
<li><em>What are the URLs of your Google Colab notebooks (both Python
and R)?</em> My <a href="https://colab.research.google.com/drive/1Xr_090vnP9U2JZz5EJOgsO6pEIvXHa0i?usp=sharing">R
Notebook</a> My <a href="https://colab.research.google.com/drive/1p-F8JBi9rBJnSwenCDktDM_cdoTMyq9w?usp=sharing">Jypter
Notebook</a></li>
</ol>
<h2 id="tableau">Tableau</h2>
<p><a href="https://github.com/Jarrold-Fowler/620-ODU/blob/main/south%20and%20west%20-%20tableau.png">Chart
Screenshot</a></p>
<ol style="list-style-type: decimal">
<li><em>What conclusions can you draw from the chart?</em> Office
supplies sales were low in Fiscal Year 2020, probably due to Covid.</li>
</ol>
<h2 id="observable-and-vega-lite">Observable and Vega-Lite</h2>
<h3 id="a-taste-of-observable">A Taste of Observable</h3>
<ol style="list-style-type: decimal">
<li><p><em>In the “New York City weather forecast” section, try
replacing <code>Forecast: detailedForecast</code> with
<code>Forecast: shortForecast</code>. Then press the blue play button or
use Shift-Return to run your change. What happens?</em> The short
description of weather for the day is given</p></li>
<li><p><em>Under the scatterplot of temperature vs.&nbsp;name, try replacing
<code>markCircle()</code> with <code>markSquare()</code>. Then press the
blue play button or use Shift-Return to run your change. What happens?
How about <code>markPoint()</code>?</em> The plot turns into a square
from a circle</p></li>
<li><p><em>Under “Pick a location, see the weather forecast”, pick a
location on the map. Where was the point you picked near?</em> I picked
Hampton roads, and it stated it was near Southhampton Meadow,
Virginia.</p></li>
<li><p>*The last visualization on this page is a “fancy” weather chart
embedded from another notebook. Click on the 3 dots next to that chart
and choose ‘Download PNG’. <a href="https://github.com/Jarrold-Fowler/620-ODU/blob/main/untitled.png">Fancy
Weather Chart</a></p></li>
</ol>
<h3 id="charting-with-vega-lite">Charting with Vega-Lite</h3>
<p><code>markCircle()</code></p>
<ol style="list-style-type: decimal">
<li><em>Pass an option of <code>{ size: 200 }</code> to
<code>markCircle()</code>.</em></li>
<li><em>Try <code>markSquare</code> instead of
<code>markCircle</code>.</em></li>
<li><em>Try <code>markPoint({ shape: 'diamond' })</code>.</em></li>
</ol>
<p><code>vl.x().fieldQ("Horsepower")</code>, …</p>
<ol style="list-style-type: decimal">
<li><em>Change <code>Horsepower</code> to
<code>Acceleration</code></em></li>
<li><em>Swap what fields are displayed on the x- and y-axis</em></li>
</ol>
<p><code>vl.tooltip().fieldN("Name")</code></p>
<ol style="list-style-type: decimal">
<li><em>Change <code>Name</code> to <code>Origin</code>.</em></li>
</ol>
<p>Another example, <code>count()</code></p>
<ol style="list-style-type: decimal">
<li><em>Remove the <code>vl.y().fieldN("Origin")</code> line.</em></li>
<li><em>Replace <code>count()</code> with
<code>average("Miles_per_Gallon")</code>.</em></li>
</ol>
<h2 id="references">References</h2>
<p><em>Every report must list the references that you consulted while
completing the assignment. If you consulted a webpage, you must include
the URL.</em></p>
<ul>
<li>Insert Reference 1, <a href="https://www.earthdatascience.org/courses/earth-analytics/document-your-science/add-images-to-rmarkdown-report/">Adding
markdown images</a></li>
<li>Insert Reference 2, <a href="https://help.tableau.com/current/guides/get-started-tutorial/en-us/get-started-tutorial-focus.htm">Getting
Started with Tableau</a></li>
<li>Insert Reference 3, <a href="https://observablehq.com/@tomb/a-taste-of-observable">A Taste of
Observable</a></li>
</ul>



</body></html>
