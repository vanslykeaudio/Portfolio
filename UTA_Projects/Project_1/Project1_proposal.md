<div style="text-align: center;">
  <img src="../Images/UTA_logo.png" alt="UTA LOGO" height="133" width="500" style="display: block; margin-left: auto; margin-right: auto; width: 50%;">
</div>

### PROJECT 1:
### A PROOF OF CONCEPT FOR FIXED ROUTE TIME PREDICTION
***

#### PROBLEM STATEMENT FORMATION:

Train a Proof of Concept Model with 90-95% accuracy by the end of September 2024; demonstrating the potential for an accurate Route planning model to benefit the UTA Planning Department for future changes.

#### CONTEXT:
As a public transit service provider, The Utah Transit Authority is subject to massive amounts of variance when trying to plan their routes.  This problem is however largely seasonal in it's predictability Ex: predicing the longer amount of time it takes to travel during the morning and afternoon rush hours.  Due to the layout of Salt Lake City where this project will be localized, traffic also has a tendency to become hyper condensed in specific areas especially during construction periods.  The over arching objective of which this project is but a small step is to be able to predict how traffic will react to changes in the system and thus have our routes/detours be planned proactively rather than reactively.

#### CRITERIA FOR SUCCESS:
Success is very simple in this instance: Can we accurately predict bus times between time points on a given route?  We will be utilizing RMSE as a metric for measuring predicted vs ground truth data hoping to achieve a value approximately between 0.05 to 0.01 RMSE

#### SCOPE OF SOLUTION SPACE:
For the time being we will be strictly focusing on Routes operating within the Salt Lake Business Unit as well as solely focusing time predictions.

#### CONSTRAINTS:
This project will unfortuneatly be limited to public data made availabel via the UTA API.

#### STAKEHOLDERS:
A short list of stakeholders:
- UTA Governing body
- Passengers
- IT Department
- Planning Department
- Dispatch

#### DATA SOURCES:
- UTA Open Data Platform.