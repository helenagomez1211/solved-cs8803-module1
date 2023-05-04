Download Link: https://assignmentchef.com/product/solved-cs8803-module1
<br>



<ul>

 <li>Intro &amp; Chapter 1: Weapons of Math Destruction (What is a Model?)</li>

 <li>Kosinski, D. Stillwell, T. Graepel, “Digital records of behavior expose personal traits,”</li>

</ul>

Proceedings of the National Academy of Sciences Apr 2013, 110 (15) 5802-

5805; DOI:10.1073/pnas.1218772110, <u>http://www.pnas.org/content/110/15/5802</u>

In this basic assignment, you’ll begin the process of discovering how data from a user’s social media profile is used by various organizations. You’ll accomplish this task by examining your own data profile on social media. We will focus on Facebook for this assignment (see the note below if you’d like to choose another social media platform).

<ul>

 <li>Step 1: Information on how to download a coy of your data can be found at:</li>

</ul>

https://www.facebook.com/help/1701730696756992

<ul>

 <li>Step 2: Download your data associated with the “Select Ads” category (two formats are available:</li>

</ul>

html and json).

<ul>

 <li>Step 3: Based on the data file <em>html</em>, categorize advertisers into (no less than) 5 categories and (no more than) 10 categories.</li>

 <li>Step 4: Create a data flow graph (using <u>http://sankeymatic.com/build/</u>) that associates your advertiser categories with three types of data buckets: Relevant, Not Relevant, Way Off. Feel free to be creative in the naming of your buckets.</li>

 <li>Step 5: Compute basic statistical measures on the data (per category): count, mean, accuracy (= %Relevant), and rubbish (%Way Off). Identify which category was the most accurate and which was the least.</li>

 <li>Step 6: Identify which advertisers are associated with a regulated domain in law (i.e. Credit,</li>

</ul>

Education, Employment, Housing and ‘Public Accommodation’). For each regulated domain, list how many fall within and the associated advertiser.

<ul>

 <li>Step 7: Turn in a report documenting your findings, including number of advertisers, categories identified, script (if using sankeymatic) and data flow graphic, statistical measures, regulated domain/advertiser list. As an example, here’s the report associated with my data:</li>

</ul>

Number of Advertisers: 1700

Categories Identified (5):

Car Companies (e.g. International Autos Mercedes Benz)

<table width="623">

 <tbody>

  <tr>

   <td width="623"> Table: Summary Statistics Count (<em>Partial Example for One Category</em>)

    <table width="557">

     <tbody>

      <tr>

       <td width="82">Variable</td>

       <td width="170">Ordinal Categories</td>

       <td width="61">Count</td>

       <td width="59">Mean</td>

       <td width="71">Accuracy</td>

       <td width="113">Rubbish Meter</td>

      </tr>

      <tr>

       <td width="82">Shopping</td>

       <td width="170">-1. U Got to be Kidding</td>

       <td width="61">85</td>

       <td width="59"> </td>

       <td width="71"> </td>

       <td width="113"> </td>

      </tr>

      <tr>

       <td width="82"> </td>

       <td width="170">0. No</td>

       <td width="61">85</td>

       <td width="59"> </td>

       <td width="71"> </td>

       <td width="113"> </td>

      </tr>

      <tr>

       <td width="82"> </td>

       <td width="170">1. Yes</td>

       <td width="61">0</td>

       <td width="59"> </td>

       <td width="71"> </td>

       <td width="113"> </td>

      </tr>

      <tr>

       <td width="82"> </td>

       <td width="170">Total</td>

       <td width="61">170</td>

       <td width="59">-0.5</td>

       <td width="71">0%</td>

       <td width="113">50%</td>

      </tr>

     </tbody>

    </table> My most accurate category: Social ImpactMy least accurate category (i.e. rubbish): ShoppingAdvertisers and Associated Regulated Domains in Law:Credit (2):Alliant Credit UnionAnchor Capital Education (3):Baylor College of MedicineDaniels College of BusinessGeorgia State UniversityEmployment (0)Housing (2):Ashton Woods HomesEcho Fine Properties </td>

  </tr>

 </tbody>

</table>




Note: If choose to use another social media platform, you are allowed to do so for this assignment, but you must deliver similar information to the advertiser list provided by Facebook.