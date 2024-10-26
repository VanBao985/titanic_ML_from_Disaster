## Project Titanic - Machine Learning from Disaster

<a href= https://www.kaggle.com/c/titanic/data>Data from Kaggle</a>
### 1. The Challenge
<div>
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).
</div>

### 2. Dataset description
<table>
  <thead>
    <tr>
      <th>Variable</th>
      <th>Definition</th>
      <th>Key</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>survival</td>
      <td>Survival</td>
      <td>0 = No, 1 = Yes</td>
    </tr>
    <tr>
      <td>pclass</td>
      <td>Ticket class</td>
      <td>1 = 1st, 2 = 2nd, 3 = 3rd</td>
    </tr>
    <tr>
      <td>sex</td>
      <td>Sex</td>
      <td></td>
    </tr>
    <tr>
      <td>Age</td>
      <td>Age in years</td>
      <td></td>
    </tr>
    <tr>
      <td>sibsp</td>
      <td># of siblings / spouses aboard the Titanic</td>
      <td></td>
    </tr>
    <tr>
      <td>parch</td>
      <td># of parents / children aboard the Titanic</td>
      <td></td>
    </tr>
    <tr>
      <td>ticket</td>
      <td>Ticket number</td>
      <td></td>
    </tr>
    <tr>
      <td>fare</td>
      <td>Passenger fare</td>
      <td></td>
    </tr>
    <tr>
      <td>cabin</td>
      <td>Cabin number</td>
      <td></td>
    </tr>
    <tr>
      <td>embarked</td>
      <td>Port of Embarkation</td>
      <td>C = Cherbourg, Q = Queenstown, S = Southampton</td>
    </tr>
  </tbody>
</table>


### 3. Goal and metric 
- Goal
It is your job to predict if a passenger survived the sinking of the Titanic or not.
For each in the test set, you must predict a 0 or 1 value for the variable.

- Metric
Your score is the percentage of passengers you correctly predict. This is known as accuracy.
