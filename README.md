# form-5500-aggregator
Aggregating Form 5500 filings from the U.S. Department of Labor website.

## wtf are 5500's
The Employee Retirement Income Security Act of 1974 (ERISA) and provisions of the Internal Revenue Code require
certain employee benefit plans to submit information on their size, funding, operations, and other characteristics to the
Government every year on the Form 5500 series.

## who gives a shit
Employers provide information such as the number of employees enrolled, the number active particpatates, the total plan assets and their breakdowns by asset class, and their annual change in NAV (with contributions being backed out). In addition, it lists the various mutual fund / investment options avaible, and their fees. Balance sheets are also provided (and maybe even more indepth investment breakdowns), so one should easily be able to calculat the historical returns for each plan / firm.

## what's da plan
- Given the really shitt interface/design on EFAST2, I'm hoping to whip something up that pulls, scrubs, and organizes everything into a database that can be interfaced with an API. The API will be private at first, but I'm obv gonna try and make that shit open ASAP.
- Make a simple website where you can serach by your Employer's plan, and also see high level stats / time-series analyses that are interesting.

## credits
This was heavily inspired by the 401(k) fee browser over at [Future Advisor](https://www.futureadvisor.com/401k), but their shit's super out of date (my previous employer's plan is current as of 2010 😑). I want to create a resource that has the most up-to-date information, and dope ass interface.
