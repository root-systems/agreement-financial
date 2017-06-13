# Financial Agreement

## Dependancies
This agreement is dependant on two others:

 - Activity Types Agreement 
 - Self Management Agreement
 - Buffer Agreement

## Member Remuneration
Our simplified formula for a months pay can be described as:

**Base Income + Business Viability Bonus + Performance Bonus**

 - **Base Income:** This is the monthly amount a core member will always receive, no matter what number of hours they work.
 - **Business Viability Bonus:** A top up amount that based on how sustainable we percieve our business to be.
 - **Performance Bonus:** A top up based on work that brings money to organisation.

How we generate these different amounts is a little more complex as it depends on two factors: 

 - Our current Buffer level
 - Activity Types conducted during the month

 We use activity types and buffer levels to determine what amounts are added to these three components: 

Variables:

 - COR - Charge out rate (How much a member costs per hour to the client)
 - BH - Billable hours (number of billable hours a member billed to a client in a month)
 - Day Activity Types:
    - Personal - only basic income
    - Internal investment or administration - basic income + an internal top up for the day
    - Contracting - basic income + a contracting top up for the day + BH * COR *10% 
 - Buffer: 
    - Level 1
    - Level 2
    - Level 3
    - Level 4
 - Commission = 10%

### The Formula
To calculate the amount someone recieves, take their booked in activity types for a month and refer to the table below.

### Calculating daily amounts
| buffer level\activity type 	| Personal 		| Internal Top up	| Contracting Top up|
| :---         				| ---:      			| ---: 			| ---:				|
| Level 0  				| 100     			| 160    			| 200			|
| Level 1        				| 100          		| 190        		| 240			|
| Level 2        				| 100          		| 220	      		| 280			|
| Level 3        				| 100          		| 250        		| 320			|
| Level 4        				| 100          		| 280        		| 360			|

### Forcasting example 

Given we are planning for febuary of a non leap year
And we are at Buffer Level 2
And a Member has booked in:

 - 4 Personal days
 - 6 Internal days
 - 10 Contracting days
 
And we can estimat:

 - 6 billable hours contracting day
 - a charge out rate of $140

When we run a cashflow forecast
Then we can calculate the member will recieve:


                     4 * 100
                     4 * 220
                    10 * 280
              60 * 0.1 * 100
            ----------------
                 Total: 5120

### End of Month
At the end of a month we produce the invoices for our members. This follows the same process as forecasting except that we substitute in the actual billable hours worked and charge out rate.

### !Important (very experimental)
We do not adjust peoples pay down because of changes to their schedule. eg if a person gets sick and can't work we don't demote their days to a personal type. We will adjust people's pay up if they have had to do extra days they didn't intend to.

It is the job of the Coordinators to keep an eye on this overtime and checkin with the group and members about how things are going. A transparent monthly report will be shared to all members.

### Buffer as control lever (What's the point of all this?)
By coupling several factors to buffer events we can create a self regulating system. The intent is that as the buffer increases so to does the money flowing away from the pod. These are the scaling money outflows and do not include fixed costs such as space hire and SaaS tools.

## Contribution to a commons
Contribution to a commons is done as a percentage of total revenue of the pod/manth. Unless agreed otherwise this is a scaling amount of between 0-8% depending on the buffer level.

## Collaborative funding
Giving individuals control over a discretionary amount of organisation funds that they (by themselves or with others) can use for a business expense they identify. eg new computer, desk, coffee machine, plants etc...

## Invoicing
Invoices to our customers are sent within the first 5 days of the month following the billing month. Invoices are sent via Xero.

## Reporting 
A cashflow report is published at the end of each month.


# Glossary

## Income
The pods funds come from the following sources:

#### Contracting/Bodyshopping
We sell our time to work as directed - often augmenting an existing team. We charge by the hour.

#### Brownfields project work
We manage and deliver a project that is extending/refining an existing code base. May be charged by the hour or by negotiated value.

#### Greenfields project work
We manage and deliver a project with a new code base.

#### Technical Discovery workshops/Code audits
Typically a days work these are tools we use to deepen our and the client's understanding of the requirements.

#### Retainers/Maintenance Agreements
A fixed monthly sum paying for us to update, refactor and slowly develop the code base.

## Expenses
Money flowing away from the pod happens as follows

#### Fixed costs
Paying for our operation cost has the highest priority and happens before paying individuals.

#### Payment for services rendered
Paying for contractors by the hour.

#### Livelihood
Eating together

#### Basic Income
All members recieve $100 a day (5 days/week) all year. Regardless of what activities you conduct.

