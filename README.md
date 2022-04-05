<img src="http://unmaintained.tech/badge.svg"/>

<h1 align="center">
  <img src="https://github.com/marcosRoos/Tests-Study/blob/main/img/icons/bug_report_white_24dp.svg" width="64px"/> <br/>
  A Study About Tests</h1>
<p align="justify"> 
  &emsp; Test are not only a matter of quality assurance, it is something more deep, more interesting than this. Testing can show us our own flaws as programmers. It is used to find bugs, yes, but bugs are caused by humans. Maybe choosing a framework which had a serious unresolved issue can cause your software to break apart on later stages of development, that is a human error, both by the people developing the framework and by the one who choose the framework. If a bug is find on earlyer stages (e.g. during the design stage) it is cheaper to resolve, so it may cost more time to create good tests, but it pays it self on long term. <br/> <br/>
</p>

<p align="center">
    <img src="https://github.com/marcosRoos/Tests-Study/blob/main/img/chartCostByTime.png" width="100%"/>
    <em>[image 1-1] relation of time/cost to solve a bug </em>
</p> <br/> 

Testing is not the same as debuging, while testing involves planning, designing, coding, evaluating and reporting data about tests with the pourpose of finding problems, debuging is focused on finding these problems on the code and solving them. <br/> <br/>

### Automation 
<p align="justify">&emsp; It happens from time to time, that a system needs to be refactored, this leads to a bunch of problems, a lot of times the person who is refactoring is not the same who implemented, and even if it is the same person, it is really easy to make a mistake and break the code, but fear not! if your testing is good, it eases the search for the problem and therefore to solve it. <br/>
  &emsp; As you may imagine, testing may be time consuming and creating a lot of tests <ins>will</ins> be laborious. So tests automation is the hero of the day, automation still needs to be coded, but with pratice enough, they will fast forward a lot of the work. </p> <br/>
  
### Test Pyramid
<p align="center">
  <img src="https://github.com/marcosRoos/Tests-Study/blob/main/img/pyramidOfTests.png" width="100%"/>
  <em>[image 1-2] pyramid layers </em>
</p> <br/>
<p align="justify">&emsp; This pyramid is a great reference when you are starting to write your own tests, but at the same time it is too generalist, test are way more complex than this and need to be treated as such. Even tho, it is a good remember that you should maintain different granularity between tests and that the more high-level you get the fewer tests you should have. <br/>
&emsp; OK, but what is high-level / low-level in testing ? THAT is a good question, i'm glad to see you are interested. Low-level means we are testing a smaller part of the system, as a method, while high-level means we are testing a big part of the system or the system it self.</p>
