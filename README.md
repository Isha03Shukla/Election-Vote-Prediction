# Election-Vote-Prediction
ML Project - Coded

**Problem 1**<br>
**Context**<br>
CNBE, a prominent news channel, is gearing up to provide insightful coverage of recent elections, recognizing the importance of data-driven analysis. A comprehensive survey has been conducted, capturing the perspectives of 1525 voters across various demographic and socio-economic factors. This dataset encompasses 9 variables, offering a rich source of information regarding voters' characteristics and preferences.<Br><BR>

**Objective**<br>
The primary objective is to leverage machine learning to build a predictive model capable of forecasting which political party a voter is likely to support. This predictive model, developed based on the provided information, will serve as the foundation for creating an exit poll. The exit poll aims to contribute to the accurate prediction of the overall election outcomes, including determining which party is likely to secure the majority of seats.<br>

**Data Description**
_vote:_ Party choice: Conservative or Labour <br>
_age_ :in years <br>
_economic.cond.national:_ Assessment of current national economic conditions, 1 to 5. <br>
_economic.cond.household:_ Assessment of current household economic conditions, 1 to 5. <br>
_Blair: _Assessment of the Labour leader, 1 to 5. <br>
_Hague_ :Assessment of the Conservative leader, 1 to 5. <br>
_Europe_:an 11-point scale that measures respondents' attitudes toward European integration.   High scores represent ‘Eurosceptic’ sentiment. <br>
_political.knowledge_: Knowledge of parties' positions on European integration, 0 to 3. <br>
_gender: _female or male. <br>
 

**Problem 2** <br>
 

In this particular project, we are going to work on the inaugural corpora from the nltk in Python. We will be looking at the following speeches of the Presidents of the United States of America:<br>

President Franklin D. Roosevelt in 1941 <br>
President John F. Kennedy in 1961 <br>
President Richard Nixon in 1973 <br>
Code Snippet to extract the three speeches: <br>

"<br>
import nltk <br>
nltk.download('inaugural')<br>
from nltk.corpus import inaugural <br>
inaugural.fileids() <br>
inaugural.raw('1941-Roosevelt.txt') <br>
inaugural.raw('1961-Kennedy.txt') <br>
inaugural.raw('1973-Nixon.txt')<br>
"<br>
