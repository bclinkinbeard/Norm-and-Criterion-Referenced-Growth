<div id="literasee-tech-report">


<div id="TOC", class="TOC">
<p>Table of Contents:</p>
<ul>
<li><a href="#introduction---why-student-growth"><span class="toc-section-number">1</span> Introduction - Why Student Growth?</a></li>
<li><a href="#student-growth-percentiles"><span class="toc-section-number">2</span> Student Growth Percentiles</a></li>
<li><a href="#sgp-calculation"><span class="toc-section-number">3</span> SGP Calculation</a></li>
<li><a href="#sgp-estimation"><span class="toc-section-number">4</span> SGP Estimation</a></li>
<li><a href="#discussion-of-model-properties"><span class="toc-section-number">5</span> Discussion of Model Properties</a></li>
<li><a href="#references">References</a></li>
</ul>
<!--
<ul>
<li></li>
<li><a href="#references">References</a></li>
<li></li>
</ul>
-->
</div>

<div id="document">


<div class="content-node document selected">

<div class="content">
<div class="document-title">Norm- and Criterion-Referenced Growth</div>
<div class="document-subtitle" title="">An Overview of the SGP Methodology</div>
<div class="authors" id="authors">Damian W. Betebenner</div>
<div class="authors" id="authors">Adam R. VanIwaarden</div>
<div class="authors" id="authors"><em>National Center for the Improvement<br></br> of Educational Assessment (NCIEA)</em></div>
<p class="published" style='text-indent: 0px;'>May 2015</p>
</div>

<div class="content-node section"><!--SGPreport-->
<div id="introduction---why-student-growth" class="section level1">
<h1><span class="header-section-number">1</span> Introduction - Why Student Growth?</h1>
<p>Accountability systems constructed according to federal adequate yearly progress (AYP) requirements currently rely upon annual “snap-shots” of student achievement to make judgments about school quality. Since their adoption, such <em>status measures</em> have been the focus of persistent criticism <span class="citation">(Linn, 2003; Linn, Baker, &amp; Betebenner, 2002)</span>. Though appropriate for making judgments about the achievement level of students at a school for a given year, they are inappropriate for judgments about educational <em>effectiveness</em>. In this regard, status measures are blind to the possibility of low achieving students attending effective schools. It is this possibility that has led some critics of No Child Left Behind (NCLB) to label its accountability provisions as unfair and misguided and to demand the use of growth analyses as a better means of auditing school quality.</p>
<p>A fundamental premise associated with using student growth for school accountability is that “good” schools bring about student growth in excess of that found at “bad” schools. Students attending such schools - commonly referred to as highly effective/ineffective schools - tend to demonstrate extraordinary growth that is causally attributed to the school or teachers instructing the students. The inherent believability of this premise is at the heart of current enthusiasm to incorporate growth into accountability systems. It is not surprising that the November 2005 announcement by Secretary of Education Spellings for the Growth Model Pilot Program (GMPP) permitting states to use growth model results as a means for compliance with NCLB achievement mandates and the Race to the top competitive grants program were met with great enthusiasm by states <span class="citation">(Spellings, 2005)</span>.</p>
<p>Following these use cases, the primary thrust of growth analyses over the last decade has been to determine, using sophisticated statistical techniques, the amount of student progress/growth that can be justifiably attributed to the school or teacher - that is, to disentangle current <em>aggregate</em> level achievement from effectiveness <span class="citation">(Ballou, Sanders, &amp; Wright, 2004; Braun, 2005; Raudenbush, 2004; Rubin, Stuart, &amp; Zanutto, 2004)</span>. Such analyses, often called <em>value-added</em> analyses, attempt to estimate the teacher or school contribution to student achievement. This contribution, called the <em>school</em> or <em>teacher effect</em>, purports to quantify the impact on achievement that this school or teacher would have, on average, upon similar students assigned to them for instruction. Clearly, such analyses lend themselves to accountability systems that hold schools or teachers responsible for student achievement.</p>
<p>Despite their utility in high stakes accountability decisions, the causal claims of teacher/school effectiveness addressed by value-added models (VAM) often fail to address questions of primary interest to education stakeholders. For example, VAM analyses generally ignore a fundamental interest of stakeholders regarding student growth: How much growth did a student make? The disconnect reflects a mismatch between questions of interest and the statistical model employed to answer those questions. Along these lines, <span class="citation">(Harris, 2007)</span> distinguishes value-added for program evaluation (VAM-P) and value-added for accountability (VAM-A) - conceptualizing accountability as a difficult type of program evaluation. Indeed, the current climate of high-stakes, test-based accountability has blurred the lines between program evaluation and accountability. This, combined with the emphasis of value-added models toward causal claims regarding school and teacher effects has skewed discussions about growth models toward causal claims at the expense of description. Research <span class="citation">(Yen, 2007)</span> and personal experience suggest stakeholders are more interested in the reverse: description first that can be used secondarily as part of causal fact finding.</p>
<p>In a survey conducted by Yen<span class="citation">(2007)</span>, supported by the author’s own experience working with state departments of education to implement growth models, parents, teacher, and administrators were asked what “growth” questions were most of interest to them.</p>
<ul>
<li><strong>Parent Questions:</strong>
<ul>
<li>Did my child make a year’s worth of progress in a year?</li>
<li>Is my child growing appropriately toward meeting state standards?</li>
<li>Is my child growing as much in Math as Reading?</li>
<li>Did my child grow as much this year as last year?</li>
</ul></li>
<li><strong>Teacher Questions:</strong>
<ul>
<li>Did my students make a year’s worth of progress in a year?</li>
<li>Did my students grow appropriately toward meeting state standards?</li>
<li>How close are my students to becoming Proficient?</li>
<li>Are there students with unusually low growth who need special attention?</li>
</ul></li>
<li><strong>Administrator Questions:</strong>
<ul>
<li>Did the students in our district/school make a year’s worth of progress in all content areas?</li>
<li>Are our students growing appropriately toward meeting state standards?</li>
<li>Does this school/program show as much growth as that one?</li>
<li>Can I measure student growth even for students who do not change proficiency categories?</li>
<li>Can I pool together results from different grades to draw summary conclusions?</li>
</ul></li>
</ul>
<p>As Yen remarks, all these questions rest upon a desire to understand whether observed student progress is “reasonable or appropriate” <span class="citation">(Yen, 2007)</span>. More broadly, the questions seek a description rather than a parsing of responsibility for student growth. Ultimately, questions may turn to who/what is responsible. However, as indicated by this list of questions, they are not the starting point for most stakeholders.</p>
<p>In the following paragraphs, student growth percentiles and percentile growth projections/trajectories are introduced as a means of understanding student growth in both norm-referenced and criterion referenced ways. With these values calculated we show how growth data can be utilized in both a norm- and in a criterion-referenced manner to inform discussion about education quality. We assert that the establishment of a norm-referenced basis for student growth eliminates a number of the problems of incorporating growth into accountability systems providing needed insight to various stakeholders by addressing the basic question of how much a student has progressed <span class="citation">(Betebenner, 2008; D. W. Betebenner, 2009)</span>.</p>
<!-- HTML_Start -->
<!-- LaTeX_Start 
\pagebreak
LaTeX_End -->
</div>
<div id="student-growth-percentiles" class="section level1">
<h1><span class="header-section-number">2</span> Student Growth Percentiles</h1>
<p>It is a common misconception that to quantify student progress in education, the subject matter and grades over which growth is examined must be on the same scale - referred to as a vertical scale. Not only is a vertical scale not necessary, but its existence obscures concepts necessary to fully understand student growth. Growth, fundamentally, requires change to be examined for a single construct like math achievement across time - <em>growth in what?</em></p>
<p>Consider the familiar situation from pediatrics where the interest is on measuring the height and weight of children over time. The scales on which height and weight are measured possess properties that educational assessment scales aspire towards but can never meet.<a href="#fn1" class="footnoteRef" id="fnref1"><sup>1</sup></a></p>
<blockquote>
<p>An infant male toddler is measured at 2 and 3 years of age and is shown to have grown 4 inches. The magnitude of increase - 4 inches - is a well understood quantity that any parent can grasp and measure at home using a simple yardstick. However, parents leaving their pediatrician’s office knowing only how much their child has grown would likely be wanting for more information. In this situation, parents are not interested in an absolute criterion of growth, but instead in a norm-referenced criterion locating that 4 inch increase alongside the height increases of similar children. Examining this height increase relative to the increases of similar children permits one to diagnose how (a)typical such an increase is.</p>
</blockquote>
<p>Given this reality in the examination of change where scales of measurement are perfect, we argue that it is unreasonable to think that in education, where scales are at best quasi-interval <span class="citation">(Lord, 1975; Yen, 1986)</span> one can/should examine growth differently.</p>
<p>Going further, suppose that scales did exist in education similar to height/weight scales that permitted the calculation of absolute measures of annual academic growth for students. The response to a parent’s question such as, “How much did my child progress?”, would be a number of scale score points - an answer that would leave most parents confused wondering whether the number of points is good or bad. As in pediatrics, the search for a description regarding changes in achievement over time (i.e., growth) is best served by considering a norm-referenced quantification of student growth - <em>a student growth percentile</em> <span class="citation">(Betebenner, 2008; D. W. Betebenner, 2009)</span>.</p>
<p>A student’s growth percentile (SGP) describes how (a)typical a student’s growth is by examining his/her current achievement relative to his/her <em>academic peers</em> - those students beginning at the same place. That is, a student growth percentile examines the current achievement of a student relative to other students who have, in the past, “walked the same achievement path”. Heuristically, if the state assessment data set were extremely large (in fact, infinite) in size, one could open the infinite data set and select out those students with the exact same prior scores and compare how the selected student’s current year score compares to the current year scores of those students with the same prior year’s scores - his/her academic peers. If the student’s current year score exceeded the scores of most of his/her academic peers, in a norm-referenced sense they have done as well. If the student’s current year score was less than the scores of his/her academic peers, in a norm-referenced sense they have not done as well.</p>
<p>The four panels of Figure B.1. depict what a student growth percentile represents in a situation considering students having only two consecutive achievement test scores.</p>
<ul>
<li><strong>Upper Left Panel</strong> Considering all pairs of 2011 and 2012 scores for all students in the state yields a bivariate (two variable) distribution. The higher the distribution, the more frequent the pair of scores.<br />
</li>
<li><strong>Upper Right Panel</strong> Taking account of prior achievement (i.e., conditioning upon prior achievement) fixes the value of the 2011 scale score (in this case at approximately 460) and is represented by the red slice taken out of the bivariate distribution.</li>
<li><strong>Lower Left Panel</strong> Conditioning upon prior achievement defines a <em>conditional distribution</em> which represents the distribution of outcomes on the 2012 test assuming a 2011 score of 460. This distribution is indicated by the solid red slice of the distribution.<br />
</li>
<li><strong>Lower Right Panel</strong> The conditional distribution provides the context against which a student’s 2012 achievement can be examined and provides the basis for a norm-referenced comparison. Students with achievement in the upper tail of the conditional distribution have demonstrated high rates of growth relative to their academic peers whereas those students with achievement in the lower tail of the distribution have demonstrated low rates of growth. Students with current achievement in the middle of the distribution could be described as demonstrating “average” or “typical” growth. In the figure provided the student scores approximately 500 on the 2012 test. Within the conditional distribution, the value of 500 lies at the 75<sup>th</sup> percentile. Thus the student’s progress from 460 in 2011 to 500 in 2012 met or exceeded that of 75 percent of students starting from the same place. It is important to note that qualifying a student growth percentile as “adequate”, “good”, or “enough” is a standard setting procedure that requires stakeholders to examine a student’s growth <em>vis-a-vis</em> external criteria such as performance standards/levels.</li>
</ul>
<!-- HTML_Start -->
<!-- LaTeX_Start 
\pagebreak
LaTeX_End -->
<!--
###### **Fig. B.1:**   Depiction of the distribution associated with 2011 and 2012 student scale scores together with the conditional distribution and associated growth percentile.
![](../img/Appendices/SGP_Method/bidensity_p1.jpg) ![](../img/Appendices/SGP_Method/bidensity_p2.jpg) ![](../img/Appendices/SGP_Method/bidensity_p3.jpg) ![](../img/Appendices/SGP_Method/bidensity_p4.jpg)
-->
<!-- HTML_Start -->
<div class="section level6">
<h6><h6>
<strong>Fig. B.1:</strong> Depiction of the distribution associated with 2011 and 2012 student scale scores together with the conditional distribution and associated growth percentile.
</h6>
<p>
<img src="img/Appendices/SGP_Method/bidensity_p1.jpg" width=50% /> <img src="img/Appendices/SGP_Method/bidensity_p2.jpg" width=50% /> <img src="img/Appendices/SGP_Method/bidensity_p3.jpg" width=50% /> <img src="img/Appendices/SGP_Method/bidensity_p4.jpg" width=50% />
</p>
</div>
<!-- LaTeX_Start 
\begin{figure}[H]
\caption*{\label{fig:Bidensity} {\bf{Fig. B.1:}} Depiction of the distribution associated with 2011 and 2012 student scale scores together with the conditional distribution and associated growth percentile.}
  \begin{subfigure}[b]{0.5\textwidth}
    \includegraphics[width=\textwidth]{../img/Appendices/SGP_Method/bidensity_p1.jpg}
  \end{subfigure}
  %
  \begin{subfigure}[b]{0.5\textwidth}
    \includegraphics[width=\textwidth]{../img/Appendices/SGP_Method/bidensity_p2.jpg}
  \end{subfigure}
  \begin{subfigure}[b]{0.5\textwidth}
    \includegraphics[width=\textwidth]{../img/Appendices/SGP_Method/bidensity_p3.jpg}
  \end{subfigure}
  %
  \begin{subfigure}[b]{0.5\textwidth}
    \includegraphics[width=\textwidth]{../img/Appendices/SGP_Method/bidensity_p4.jpg}
  \end{subfigure}
\end{figure}
LaTeX_End -->
<p>Figure B.1 also serves to illustrate the relationship between the state’s assessment scale and student growth percentiles. The scale depicted in the panels of Figure B.1 is not vertical. Thus the comparisons or subtraction of scale scores for individual students is not supported. However, were such a scale in place, the figure would not change. With or without a vertical scale, the conditional distribution can be constructed.</p>
<p>In situations where a vertical scale exists, the increase/decrease in scale score points can be calculated and the growth percentile can be understood alongside this change. For example, were the scales presented in Figure B.1 vertical, then one can calculate that the student grew 40 points (from 460 to 500) between 2011 and 2012. This 40 points represents the absolute magnitude of change. Quantifying the magnitude of change is scale dependent. For example, different vertical achievement scales in 2011 and 2012 would yield different annual scale score increases: A scale score increase of 40 could be changed to a scale score increase of 10 using a simple transformation of the vertical scale on which all the students are measured. However, relative to other students, their growth has not changed - their growth percentile is invariant to scale transformations common in educational assessment. Student growth percentiles norm-referencedly situate achievement change bypassing questions associated with the magnitude of change, and directing attention toward relative standing which, we would assert, is what stakeholders are most interested in.</p>
<p>To fully understand how many states intend to use growth percentiles to make determinations about whether a student’s growth is sufficient, the next section details specifics of how student growth percentiles are calculated. These calculations are subsequently used to calculate percentile growth projections/trajectories that are used to establish how much growth it will take for each student to reach his/her achievement targets.</p>
<!-- HTML_Start -->
<!-- LaTeX_Start 
\pagebreak
LaTeX_End -->
</div>
<div id="sgp-calculation" class="section level1">
<h1><span class="header-section-number">3</span> SGP Calculation</h1>
<p>Quantile regression is used to establish curvilinear functional relationships between the cohort’s prior scores and their current scores. Specifically, for each grade by subject cohort, quantile regression is used to establish 100 (1 for each percentile) curvilinear functional relationships between the students prior score(s) and their current score. For example, consider 7<sup>th</sup> graders in 2014. Their grade 3, grade 4, grade 5, and grade 6 prior scores are used to describe the current year grade 7 score distribution.<a href="#fn2" class="footnoteRef" id="fnref2"><sup>2</sup></a> The result of these 100 separate analyses is a single coefficient matrix that can be employed as a look-up table relating prior student achievement to current achievement for each percentile. Using the coefficient matrix, one can plug in <em>any</em> grade 3, 4, 5, and 6 prior score combination to the functional relationship to get the percentile cutpoints for grade 7 conditional achievement distribution associated with that prior score combination. These cutpoints are the percentiles of the conditional distribution associated with the individual’s prior achievement. Consider a student with the following mathematics scores:</p>
<!-- HTML_Start -->
<table class="gmisc_table breakboth" style="border-collapse: collapse; margin-top: 1em; margin-bottom: 1em;" FALSE>
<thead>
<tr>
<td colspan="5" style="text-align: left;">
<strong>Table 1:</strong> Scale scores for a hypothetical student across 5 years in mathematics.
</td>
</tr>
<tr>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
Grade 3/2010
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
Grade 4/2011
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
Grade 5/2012
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
Grade 6/2013
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
Grade 7/2014
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="border-bottom: 2px solid grey; text-align: right;">
819
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
818
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
822
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
834
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
836
</td>
</tr>
</tbody>
</table>
<!-- LaTeX_Start
%latex.default(my_tbl, file = "", where = where, col.just = tex.align,     caption = tmp_caption, ...)%
\begin{table}[H]
\caption{**Table 1:** Scale scores for a hypothetical student across 5 years in mathematics.\label{my}} 
\begin{center}
\begin{tabular}{rrrrr}
\hline\hline
\multicolumn{1}{c}{Grade 3/2010}&\multicolumn{1}{c}{Grade 4/2011}&\multicolumn{1}{c}{Grade 5/2012}&\multicolumn{1}{c}{Grade 6/2013}&\multicolumn{1}{c}{Grade 7/2014}\tabularnewline
\hline
$819$&$818$&$822$&$834$&$836$\tabularnewline
\hline
\end{tabular}\end{center}

\end{table}

LaTeX_End -->
<p>Using the coefficient matrix derived from the quantile regression analyses based upon grade 3, 4, 5, and 6 scale scores as independent variables and the grade 7 scale score as the dependent variable together with this student’s vector of grade 3, 4, 5, and 6 grade scale scores provides the scale score percentile cutpoints associated with the grade 7 conditional distribution for these prior scores.</p>
<!-- HTML_Start -->
<table class="gmisc_table breakboth" style="border-collapse: collapse; margin-top: 1em; margin-bottom: 1em;" FALSE>
<thead>
<tr>
<td colspan="16" style="text-align: left;">
<strong>Table 2:</strong> Percentile cutscores for grade 7 mathematics based upon the grade 3, 4, 5, and 6 mathematics scale scores given in Table 1.
</td>
</tr>
<tr>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
1st
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
2nd
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
3rd
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
…
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
10th
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
…
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
25th
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
…
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
50th
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
51th
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
…
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
75th
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
…
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
90th
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
…
</th>
<th style="border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
99th
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="border-bottom: 2px solid grey; text-align: right;">
804.8
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
814.9
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
819.9
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
…
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
825.9
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
…
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
830.8
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
…
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
835.5
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
836.3
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
…
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
868.9
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
…
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
887.1
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
…
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
909.8
</td>
</tr>
</tbody>
</table>
<!-- LaTeX_Start
%latex.default(my_tbl, file = "", where = where, col.just = tex.align,     caption = tmp_caption, ...)%
\begin{table}[H]
\caption{**Table 2:** Percentile cutscores for grade 7 mathematics based upon the grade 3, 4, 5, and 6 mathematics scale scores given in Table 1.\label{my}} 
\begin{center}
\begin{tabular}{rrrrrrrrrrrrrrrr}
\hline\hline
\multicolumn{1}{c}{1st}&\multicolumn{1}{c}{2nd}&\multicolumn{1}{c}{3rd}&\multicolumn{1}{c}{...}&\multicolumn{1}{c}{10th}&\multicolumn{1}{c}{...}&\multicolumn{1}{c}{25th}&\multicolumn{1}{c}{...}&\multicolumn{1}{c}{50th}&\multicolumn{1}{c}{51th}&\multicolumn{1}{c}{...}&\multicolumn{1}{c}{75th}&\multicolumn{1}{c}{...}&\multicolumn{1}{c}{90th}&\multicolumn{1}{c}{...}&\multicolumn{1}{c}{99th}\tabularnewline
\hline
804.8&814.9&819.9&...&825.9&...&830.8&...&835.5&836.3&...&868.9&...&887.1&...&909.8\tabularnewline
\hline
\end{tabular}\end{center}

\end{table}

LaTeX_End -->
<p>The percentile cutscores for 7<sup>th</sup> grade mathematics in Table FALSE are used with the student’s <em>actual</em> grade 7 mathematics scale score to establish his/her growth percentile. In this case, the student’s grade 7 scale score of 836 lies above the 50<sup>th</sup> percentile cut and below the 51<sup>st</sup> percentile cut, yielding a growth percentile of 50. Thus, the progress demonstrated by this student between grade 6 and grade 7 exceeded that of 50 percent of his/her academic peers - those students with the same achievement history. States can qualify student growth by defining ranges of growth percentiles. For example, the Utah Growth Model designates growth percentiles between 35 and 60 as being <em>typical</em>. Using Table FALSE, another student with the exact same grade 3, 4, 5, and 6 prior scores but with a grade 7 scale score of 804, would have a growth percentile of 1, which is designated as <em>low</em>.</p>
<p>This example provides the basis for beginning to understand how growth percentiles in the SGP Methodology are used to determine whether a student’s growth is <em>(in)adequate</em>. Suppose that in grade 6 a one-year (i.e., 7<sup>th</sup> grade) achievement goal/target of proficiency was established for the student. Using the lowest proficient scale score for 7<sup>th</sup> grade mathematics, this target corresponds to a scale score of 900. Based upon the results of the growth percentile analysis, this one year target corresponds to 95<sup>th</sup> percentile growth. Their growth, obviously, is less than this and the student has not met this individualized growth standard.</p>
<!-- HTML_Start -->
<!-- LaTeX_Start 
\pagebreak
LaTeX_End -->
</div>
<div id="sgp-estimation" class="section level1">
<h1><span class="header-section-number">4</span> SGP Estimation</h1>
<p>Calculation of a student’s growth percentile is based upon the estimation of the conditional density associated with a student’s score at time <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=t" alt="t" title="t" /> using the student’s prior scores at times <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=1%2C%202%2C%20%5Cldots%2C%20t-1" alt="1, 2, \ldots, t-1" title="1, 2, \ldots, t-1" /> as the conditioning variables. Given the conditional density for the student’s score at time <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=t" alt="t" title="t" />, the student’s growth percentile is defined as the percentile of the score within the time <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=t" alt="t" title="t" /> conditional density. By examining a student’s current achievement with regard to the conditional density, the student’s growth percentile situates the student’s outcome at time <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=t" alt="t" title="t" /> taking account of past student performance. The percentile result reflects the likelihood of such an outcome given the student’s prior achievement. In the sense that the student growth percentile translates to the probability of such an outcome occurring (i.e., rarity), it is possible to compare the progress of individuals not beginning at the same starting point. However, occurrences being equally rare does not necessarily imply that they are equally “good.” Qualifying student growth percentiles as “(in)adequate,” “good,” or as satisfying “a year’s growth” is a standard setting procedure requiring external criteria (e.g., growth relative to state performance standards) combined with the wisdom and judgments of stakeholders.</p>
<p>Estimation of the conditional density is performed using quantile regression <span class="citation">(Koenker, 2005)</span>. Whereas linear regression methods model the conditional mean of a response variable <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=Y" alt="Y" title="Y" />, quantile regression is more generally concerned with the estimation of the family of conditional quantiles of <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=Y" alt="Y" title="Y" />. Quantile regression provides a more complete picture of both the conditional distribution associated with the response variable(s). The techniques are ideally suited for estimation of the family of conditional quantile functions (i.e., reference percentile curves). Using quantile regression, the conditional density associated with each student’s prior scores is derived and used to situate the student’s most recent score. Position of the student’s most recent score within this density can then be used to characterize the student’s growth. Though many state assessments possess a vertical scale, such a scale is not necessary to produce student growth percentiles.</p>
<p>In analogous fashion to the least squares regression line representing the solution to a minimization problem involving squared deviations, quantile regression functions represent the solution to the optimization of a loss function <span class="citation">(Koenker, 2005)</span>. Formally, given a class of suitably smooth functions, <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Ccal%7BG%7D" alt="\cal{G}" title="\cal{G}" />, one wishes to solve</p>
<p><br /><img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Chspace%7B2pt%7D%20%5Ctext%7B%281%29%7D%20%5Chspace%7B55pt%7D%20%5Ctextit%7Barg%20min%7D_%20%7Bg%20%5Cin%20%5Ccal%7BG%7D%7D%20%5Csum_%20%7Bi%3D1%7D%5En%20%5Crho_%20%7B%5Ctau%7D%20%28Y%28t_%20i%29%20-%20g%28t_%20i%29%29%2C" alt="\hspace{2pt} \text{(1)} \hspace{55pt} \textit{arg min}_ {g \in \cal{G}} \sum_ {i=1}^n \rho_ {\tau} (Y(t_ i) - g(t_ i))," title="\hspace{2pt} \text{(1)} \hspace{55pt} \textit{arg min}_ {g \in \cal{G}} \sum_ {i=1}^n \rho_ {\tau} (Y(t_ i) - g(t_ i))," /><br /></p>
<p>where <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=t_i" alt="t_i" title="t_i" /> indexes time, <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=Y" alt="Y" title="Y" /> are the time dependent measurements, and <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Crho_%7B%5Ctau%7D" alt="\rho_{\tau}" title="\rho_{\tau}" /> denotes the piecewise linear loss function defined by</p>
<p><br /><img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Chspace%7B2pt%7D%20%5Ctext%7B%282%29%7D%20%5Chspace%7B55pt%7D%20%5Crho_%20%7B%5Ctau%7D%20%28u%29%20%3D%20u%20%5Ccdot%20%28%5Ctau%20-%20I%28u%20%3C%200%29%29%20%3D%20%5Cbegin%7Bcases%7D%20u%20%5Ccdot%20%5Ctau%20%26%20u%20%5Cgeq%200%20%5C%5C%20u%20%5Ccdot%20%28%5Ctau%20-%201%29%20%26%20u%20%3C%200.%20%20%5Cend%7Bcases%7D" alt="\hspace{2pt} \text{(2)} \hspace{55pt} \rho_ {\tau} (u) = u \cdot (\tau - I(u &lt; 0)) = \begin{cases} u \cdot \tau &amp; u \geq 0 \\ u \cdot (\tau - 1) &amp; u &lt; 0.  \end{cases}" title="\hspace{2pt} \text{(2)} \hspace{55pt} \rho_ {\tau} (u) = u \cdot (\tau - I(u &lt; 0)) = \begin{cases} u \cdot \tau &amp; u \geq 0 \\ u \cdot (\tau - 1) &amp; u &lt; 0.  \end{cases}" /><br /></p>
<p>The elegance of the quantile regression Expression 1 can be seen by considering the more familiar least squares estimators. For example, calculation of <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Ctextit%7Barg%20min%7D%20%5Csum_%20%7Bi%3D1%7D%5En%20%28Y_%20i%20-%20%5Cmu%29%5E2" alt="\textit{arg min} \sum_ {i=1}^n (Y_ i - \mu)^2" title="\textit{arg min} \sum_ {i=1}^n (Y_ i - \mu)^2" /> over <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Cmu%20%5Cin%20%5Cmathbb%7BR%7D" alt="\mu \in \mathbb{R}" title="\mu \in \mathbb{R}" /> yields the sample mean. Similarly, if <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Cmu%28x%29%20%3D%20x%5E%7B%5Cprime%7D%20%5Cbeta" alt="\mu(x) = x^{\prime} \beta" title="\mu(x) = x^{\prime} \beta" /> is the conditional mean represented as a linear combination of the components of <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=x" alt="x" title="x" />, calculation of <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Ctextit%7Barg%20min%7D%20%5Csum_%20%7Bi%3D1%7D%5En%20%28Y_%20i%20-%20x_%20i%5E%7B%5Cprime%7D%20%5Cbeta%29%5E2" alt="\textit{arg min} \sum_ {i=1}^n (Y_ i - x_ i^{\prime} \beta)^2" title="\textit{arg min} \sum_ {i=1}^n (Y_ i - x_ i^{\prime} \beta)^2" /> over <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Cbeta%20%5Cin%20%5Cmathbb%7BR%7D%5Ep" alt="\beta \in \mathbb{R}^p" title="\beta \in \mathbb{R}^p" /> gives the familiar least squares regression line. Analogously, when the class of candidate functions <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Ccal%7BG%7D" alt="\cal{G}" title="\cal{G}" /> consists solely of constant functions, the estimation of Expression 1 gives the <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Ctau" alt="\tau" title="\tau" /><sup>th</sup> sample quantile associated with <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=Y" alt="Y" title="Y" />. By conditioning on a covariate <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=x" alt="x" title="x" />, the <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Ctau" alt="\tau" title="\tau" /><sup>th</sup> conditional quantile function is given by</p>
<p><br /><img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Chspace%7B2pt%7D%20%5Ctext%7B%283%29%7D%20%5Chspace%7B55pt%7D%20Q_y%20%28%5Ctau%20%7C%20x%29%20%3D%20%5Ctextit%7Barg%20min%7D_%7B%5Cbeta%20%5Cin%20%5Cmathbb%7BR%7D%5E%7B%5Ep%7D%7D%20%5Csum_%7Bi%3D1%7D%5En%20%5Crho_%7B%5Ctau%7D%20%28y_i%20-%20x_i%5E%7B%5Cprime%7D%20%5Cbeta%29." alt="\hspace{2pt} \text{(3)} \hspace{55pt} Q_y (\tau | x) = \textit{arg min}_{\beta \in \mathbb{R}^{^p}} \sum_{i=1}^n \rho_{\tau} (y_i - x_i^{\prime} \beta)." title="\hspace{2pt} \text{(3)} \hspace{55pt} Q_y (\tau | x) = \textit{arg min}_{\beta \in \mathbb{R}^{^p}} \sum_{i=1}^n \rho_{\tau} (y_i - x_i^{\prime} \beta)." /><br /></p>
<p>In particular, if <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Ctau%3D0.5" alt="\tau=0.5" title="\tau=0.5" />, then the estimated conditional quantile line is the median regression line.<a href="#fn3" class="footnoteRef" id="fnref3"><sup>3</sup></a></p>
<p>Following Wei and He <span class="citation">(2006)</span>, we parameterize the conditional quantile functions as a linear combination of B-spline cubic basis functions. B-splines are employed to accommodate non-linearity, heteroscedasticity and skewness of the conditional densities associated with values of the independent variable(s). B-splines are attractive both theoretically and computationally in that they provide excellent data fit, seldom lead to estimation problems <span class="citation">(Harrell, 2001)</span>, and are simple to implement in available software.</p>
<p>Figure B.2 gives a bivariate representation of linear and B-splines parameterization of decile growth curves. The assumption of linearity imposes conditions upon the heteroscedasticity of the conditional densities. Close examination of the linear deciles indicates slightly greater variability for higher grade 5 scale scores than for lower scores. By contrast, the B-spline based decile functions better capture the greater variability at both ends of the scale score range together with a slight, non-linear trend to the data.</p>
<!-- 
###### **Fig. B.2:**   Linear and B-spline conditional deciles based upon bivariate math data, grades 5 and 6.
![](../img/Appendices/SGP_Method/linearquantileplot.png) ![](../img/Appendices/SGP_Method/bsplinequantileplot.png)
-->
<!-- HTML_Start -->
<div class="section level6">
<h6><h6>
<strong>Fig. B.2:</strong> Linear and B-spline conditional deciles based upon bivariate math data, grades 5 and 6.
</h6>
<p>
<img src="img/Appendices/SGP_Method/linearquantileplot.png" width=50% /> <img src="img/Appendices/SGP_Method/bsplinequantileplot.png" width=50% />
</p>
</div>
<!-- LaTeX_Start 
\begin{figure}[H]
\caption*{\label{fig:quantPlot} {\bf{Fig. B.2:}} Linear and B-spline conditional deciles based upon bivariate math data, grades 5 and 6.}
  \begin{subfigure}[b]{0.5\textwidth}
    \includegraphics[width=\textwidth]{../img/Appendices/SGP_Method/linearquantileplot.png}
  \end{subfigure}
  %
  \begin{subfigure}[b]{0.5\textwidth}
    \includegraphics[width=\textwidth]{../img/Appendices/SGP_Method/bsplinequantileplot.png}
  \end{subfigure}
\end{figure}
LaTeX_End -->
<p>Calculation of student growth percentiles is performed using <code>R</code> <span class="citation">(R Development Core Team, 2015)</span>, a language and environment for statistical computing, with <code>SGP</code> package <span class="citation">(Betebenner, VanIwaarden, Domingue, &amp; Shang, 2014)</span>. Other possible software (untested with regard to student growth percentiles) with quantile regression capability include SAS and Stata. Estimation of cohort referenced student growth percentiles is conducted using all available prior data, subject to certain suitability conditions. Given assessment scores for <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=t" alt="t" title="t" /> occasions, (<img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=t%20%5Cgeq%202" alt="t \geq 2" title="t \geq 2" />), the <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Ctau" alt="\tau" title="\tau" /><sup>th</sup> conditional quantile for <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=Y_%20t" alt="Y_ t" title="Y_ t" /> based upon <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=Y_%20%7Bt-1%7D%2C%20Y_%20%7Bt-2%7D%2C%20%5Cldots%2C%20Y_1" alt="Y_ {t-1}, Y_ {t-2}, \ldots, Y_1" title="Y_ {t-1}, Y_ {t-2}, \ldots, Y_1" /> is given by</p>
<p><br /><img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Chspace%7B2pt%7D%20%5Ctext%7B%284%29%7D%20%5Chspace%7B55pt%7D%20Q_%20%7BY_%20t%7D%20%28%5Ctau%20%7C%20Y_%20%7Bt-1%7D%2C%20%5Cldots%2C%20Y_%201%29%20%3D%20%5Csum_%20%7Bj%3D1%7D%5E%7Bt-1%7D%20%5Csum_%20%7Bi%3D1%7D%5E3%20%5Cphi_%20%7Bij%7D%28Y_%20j%29%5Cbeta_%20%7Bij%7D%28%5Ctau%29%2C" alt="\hspace{2pt} \text{(4)} \hspace{55pt} Q_ {Y_ t} (\tau | Y_ {t-1}, \ldots, Y_ 1) = \sum_ {j=1}^{t-1} \sum_ {i=1}^3 \phi_ {ij}(Y_ j)\beta_ {ij}(\tau)," title="\hspace{2pt} \text{(4)} \hspace{55pt} Q_ {Y_ t} (\tau | Y_ {t-1}, \ldots, Y_ 1) = \sum_ {j=1}^{t-1} \sum_ {i=1}^3 \phi_ {ij}(Y_ j)\beta_ {ij}(\tau)," /><br /></p>
<p>where <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Cphi_%20%7Bi%2Cj%7D" alt="\phi_ {i,j}" title="\phi_ {i,j}" />, <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=i%3D1%2C2%2C3" alt="i=1,2,3" title="i=1,2,3" /> and <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=j%3D1%2C%20%5Cldots%2C%20t-1" alt="j=1, \ldots, t-1" title="j=1, \ldots, t-1" /> denote the B-spline basis functions. Currently, bases consisting of 7 cubic polynomials are used to “smooth” irregularities found in the multivariate assessment data. A bivariate rendering of this is found is Figure B.2 where linear and B-spline conditional deciles are presented. The cubic polynomial B-spline basis functions model the heteroscedasticity and non-linearity of the data to a greater extent than is possible using a linear parameterization.</p>
<p>The B-spline basis functions require the selection of boundary and interior knots. Boundary knots are end points outside of the scale score distribution that anchor the B-spline basis. These are generally selected by extending the range of scale scores by 10%. That is, they are defined as lying 10% below the lowest obtainable (or observed) scale score (LOSS) and 10% above the highest obtainable scale score (HOSS). The interior knots are the <em>internal</em> breakpoints that define the spline.</p>
<p>The default choice in the <code>SGP</code> package <span class="citation">(Betebenner et al., 2014)</span> is to select the 20<sup>th</sup>, 40<sup>th</sup>, 60<sup>th</sup> and 80<sup>th</sup> quantiles of the observed scale score distribution. In general the knots and boundaries are computed using a distribution from several years of compiled test data (i.e. multiple cohorts) so that any irregularities in a single year are smoothed out. Subsequent annual analyses then use these same knots and boundaries as well. All defaults were used to compile the knots and boundaries for Utah from the CRT tests. New knots and boundaries were required beginning with the 2015 SGP analyses when SAGE assessments were first used as dependent variables in the quantile regressions.</p>
<p>Finally, it should be noted that the independent estimation of the regression functions can potentially result in the crossing of the quantile functions. This occurs near the extremes of the distributions and is potentially more likely to occur given the use of non-linear functions. The result of allowing the quantile functions to cross in this manner would be <em>lower</em> percentile estimations of growth for <em>higher</em> observed scale scores at the extremes (give all else equal in prior scores) and vice versa. In order to deal with these contradictory estimates, quantile regression results are isotonized to prevent quantile crossing following the methods derived by Chernozhukov, Fernandez-Val and Glichon <span class="citation">(2010)</span>.</p>
<!-- HTML_Start -->
<!-- LaTeX_Start 
\pagebreak
LaTeX_End -->
</div>
<div id="discussion-of-model-properties" class="section level1">
<h1><span class="header-section-number">5</span> Discussion of Model Properties</h1>
<p>Student growth percentiles possess a number of attractive properties from both a theoretical as well as a practical perspective. Foremost among practical considerations is that the percentile descriptions are familiar and easily communicated to teachers and other non-technical stakeholders. Furthermore, implicit within the percentile quantification of student growth is a statement of probability. Questions of “how much growth is enough?” or “how much is a year’s growth?” ask stakeholders to establish growth percentile thresholds deemed adequate. These thresholds establish growth standards that translate to probability statements. In this manner, percentile based growth forms a basis for discussion of rigorous yet attainable growth standards for all children supplying a norm-referenced context for Linn’s existence proof <span class="citation">(Linn, 2003)</span> with regard to student level growth.</p>
<p>In addition to practical utility, student growth percentiles possess a number of technical attributes well suited for use with assessment scores. The more important theoretical properties of growth percentiles include:</p>
<ul>
<li><strong>Robustness to outliers.</strong> Estimation of student growth percentiles are more robust to outliers than is traditionally the case with conditional mean estimation. Analogous to the property of the median being less influenced by outliers than is the median, conditional quantiles are robust to extreme observations. This is due to the fact that influence of a point on the <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5Ctau" alt="\tau" title="\tau" /><sup>th</sup> conditional quantile function is not proportional (as is the case with the mean) to the distance of the point from the quantile function but only to its position above or below the function <span class="citation">(Koenker, 2005, p. 44)</span>.</li>
<li><strong>Uncorrelated with prior achievement.</strong> Analogous to least squares derived residuals being uncorrelated with independent variables, student growth percentiles are not correlated with prior achievement. This property runs counter to current multilevel approaches to measuring growth with testing occasion nested within students <span class="citation">(Singer &amp; Willett, 2003)</span>. These models, requiring a vertical scale, fit lines with distinct slopes and intercepts to each student. The slopes of these lines represent an average rate of increase, usually measured in scale score points per year, for the student. Whereas a steeper slope represents more learning, it is important to understand that using a norm-referenced quantification of growth, one cannot necessarily infer that a low achieving student with a growth percentile of 60 “learned as much” as a high achieving student with the same growth percentile. Growth percentiles bypass questions associated with magnitude of learning and focus on norm-referencedly quantifying changes in achievement.<br />
</li>
<li><strong>Equivariance to monotone transformation of scale.</strong> An important attribute of the quantile regression methodology used to calculate student growth percentiles is their invariance to monotone transformations of scale. This property, denoted by <span class="citation">(Koenker, 2005)</span> as <em>equivariance to monotone transformations</em> is particularly helpful in educational assessment where a variety of scales are present for analysis, most of which are related by some monotone transformation. For example, it is a common misconception that one needs a vertical scale in order to calculate growth. Because vertical and non-vertical scales are related via a monotone transformation, the student growth percentiles do not change given such alterations in the underlying scale. This result obviates much of the discussion concerning the need for a vertical scale in measuring growth.<a href="#fn4" class="footnoteRef" id="fnref4"><sup>4</sup></a></li>
</ul>
<p>Formally, given a monotone transformation <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=h" alt="h" title="h" /> of a random variable <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=Y" alt="Y" title="Y" />,</p>
<p><br /><img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%20%5Chspace%7B2pt%7D%20%5Ctext%7B%285%29%7D%20%5Chspace%7B55pt%7D%20Q_%20h%28Y%29%7CX%20%28%5Ctau%20%7C%20X%29%20%3D%20h%28Q_%20Y%7CX%20%28%5Ctau%20%7C%20X%29%29." alt=" \hspace{2pt} \text{(5)} \hspace{55pt} Q_ h(Y)|X (\tau | X) = h(Q_ Y|X (\tau | X))." title=" \hspace{2pt} \text{(5)} \hspace{55pt} Q_ h(Y)|X (\tau | X) = h(Q_ Y|X (\tau | X))." /><br /></p>
<p>This result follows from the fact that <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=%5CPr%20%28T%20%3C%20t%20%7C%20X%29%20%3D%20%5CPr%20%28h%28T%29%20%3C%20h%28t%29%20%7C%20X%29" alt="\Pr (T &lt; t | X) = \Pr (h(T) &lt; h(t) | X)" title="\Pr (T &lt; t | X) = \Pr (h(T) &lt; h(t) | X)" /> for monotone <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=h" alt="h" title="h" />. It is important to note that <em>equivariance to monotone transformation</em> does not, in general, hold with regard to least squares estimation of the conditional mean. That is, except for affine transformations <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=h" alt="h" title="h" />, <img style="vertical-align:middle" src="http://chart.apis.google.com/chart?cht=tx&amp;chl=E%28h%28Y%29%7CX%29%20%5Cnot%3D%20h%28E%28Y%7CX%29%29" alt="E(h(Y)|X) \not= h(E(Y|X))" title="E(h(Y)|X) \not= h(E(Y|X))" />. Thus, analyses built upon mean based regression methods are, to an extent, scale dependent.</p>
<!-- HTML_Start -->
<!-- LaTeX_Start 
\pagebreak
LaTeX_End -->
</div>
<div id="references" class="section level1 unnumbered">
<h1>References</h1>
<div id="refs" class="references">
<div id="ref-BallSand:2004">
<p>Ballou, D., Sanders, W., &amp; Wright, P. (2004). Controlling for student background in value-added assessment for teachers. <em>Journal of Educational and Behavioral Statistics</em>, <em>29</em>(1), 37–65.</p>
</div>
<div id="ref-Betebenner:2008">
<p>Betebenner, D. W. (2008). Toward a normative understanding of student growth. In K. E. Ryan &amp; L. A. Shepard (Eds.), <em>The future of test-based educational accountability</em> (pp. 155–170). New York: Taylor &amp; Francis.</p>
</div>
<div id="ref-Betebenner:2009">
<p>Betebenner, D. W. (2009). Norm- and criterion-referenced student growth. <em>Educational Measurement: Issues and Practice</em>, <em>28</em>(4), 42–51.</p>
</div>
<div id="ref-sgp2014">
<p>Betebenner, D. W., VanIwaarden, A., Domingue, B., &amp; Shang, Y. (2014). <em>SGP: An r package for the calculation and visualization of student growth percentiles &amp; percentile growth trajectories.</em> Retrieved from <a href="https://github.com/CenterForAssessment/SGP" class="uri">https://github.com/CenterForAssessment/SGP</a></p>
</div>
<div id="ref-Braun:2005">
<p>Braun, H. I. (2005). <em>Using student progress to evaluate teachers: A primer on value-added models</em>. Princeton, New Jersey: Educational Testing Service.</p>
</div>
<div id="ref-chernozhukov2010quantile">
<p>Chernozhukov, V., Fernández-Val, I., &amp; Galichon, A. (2010). Quantile and probability curves without crossing. <em>Econometrica</em>, <em>78</em>(3), 1093–1125. Wiley Online Library.</p>
</div>
<div id="ref-Harrell:2001">
<p>Harrell, F. E. (2001). <em>Regression modeling strategies</em>. New York: Springer.</p>
</div>
<div id="ref-Harris:2007">
<p>Harris, D. N. (2007). <em>The policy uses and “policy validity” of value-added and other teacher quality measures</em>. Princeton, NJ: Educational Testing Service.</p>
</div>
<div id="ref-Koenker:2005">
<p>Koenker, R. (2005). <em>Quantile regression</em>. Cambridge: Cambridge University Press.</p>
</div>
<div id="ref-Linn:2003a">
<p>Linn, R. L. (2003). <em>Accountability: Responsibility and reasonable expectations</em>. Los Angeles, CA: Center for the Study of Evaluation, CRESST.</p>
</div>
<div id="ref-LinnBake:2002">
<p>Linn, R. L., Baker, E. L., &amp; Betebenner, D. W. (2002). Accountability systems: Implications of requirements of the No Child Left Behind Act of 2001. <em>Educational Researcher</em>, <em>31</em>(6), 3–16.</p>
</div>
<div id="ref-Lord:1975">
<p>Lord, F. M. (1975). The “ability” scale in item characteristic curve theory. <em>Psychometrika</em>, <em>20</em>, 299–326.</p>
</div>
<div id="ref-Rsoftware">
<p>R Development Core Team. (2015). <em>R: A language and environment for statistical computing</em>. Vienna, Austria: R Foundation for Statistical Computing. Retrieved from <a href="http://www.R-project.org" class="uri">http://www.R-project.org</a></p>
</div>
<div id="ref-Raudenbush:2004">
<p>Raudenbush, S. W. (2004). What are value-added models estimating and what does this imply for statistical practice? <em>Journal of Educational and Behavioral Statistics</em>, <em>29</em>(1), 121–129.</p>
</div>
<div id="ref-RubiStua:2004">
<p>Rubin, D. B., Stuart, E. A., &amp; Zanutto, E. L. (2004). A potential outcomes view of value-added assessment in education. <em>Journal of Educational and Behavioral Statistics</em>, <em>29</em>(1), 103–116.</p>
</div>
<div id="ref-SingWill:2003">
<p>Singer, J. D., &amp; Willett, J. B. (2003). <em>Applied longitudinal data analysis</em>. New York: Oxford University Press.</p>
</div>
<div id="ref-Spellings:2005">
<p>Spellings, M. (2005). Secretary spellings announces growth model pilot. <em>Secretary Spellings Announces Growth Model Pilot</em>. Press Release, U.S. Department of Education.</p>
</div>
<div id="ref-WeiHe:2006">
<p>Wei, Y., &amp; He, X. (2006). Conditional growth charts. <em>The Annals of Statistics</em>, <em>34</em>(5), 2069–2097.</p>
</div>
<div id="ref-Yen:1986">
<p>Yen, W. M. (1986). The choice of scale for educational measurement: An IRT perspective. <em>Journal of Educational Measurement</em>, <em>23</em>, 299–325.</p>
</div>
<div id="ref-Yen:2007">
<p>Yen, W. M. (2007). Vertical scaling and No Child Left Behind. In N. J. Dorans, M. Pommerich, &amp; P. W. Holland (Eds.), <em>Linking and aligning scores and scales</em> (pp. 273–283). New York: Springer.</p>
</div>
</div>
</div>
<div class="footnotes">
<hr />
<ol>
<li id="fn1"><p>The scales on which students are measured are often assumed to possess properties similar to height and weight but they don’t. Specifically, scales are assumed to be interval where it is assumed that a difference of 100 points at the lower end of the scale refers to the same difference in ability/achievement as 100 points at the upper end of the scale. <span class="citation">(See Lord, 1975; and Yen, 1986 for more detail on the interval scaling in educational measurement.)</span><a href="#fnref1">↩</a></p></li>
<li id="fn2"><p>For the mathematical details underlying the use of quantile regression in calculating student growth percentiles, see the <em>SGP Estimation</em> section<a href="#fnref2">↩</a></p></li>
<li id="fn3"><p>For a detailed treatment of the procedures involved in solving the optimization problem associated with Expression 1, see <span class="citation">(Koenker, 2005)</span>, particularly Chapter 6.<a href="#fnref3">↩</a></p></li>
<li id="fn4"><p>As already noted with regard to pediatrics, the existence of nice “vertical” scales for measuring height and weight still leads to observed changes being normed.<a href="#fnref4">↩</a></p></li>
</ol>
</div></div>

</div>


</div>
