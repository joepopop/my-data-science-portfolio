#### [Soccer betting simulation](https://github.com/joepopop/soccer_betting_simulation.git)

##### Part 1: Using Machine Learning

<img width="1279" alt="image" src="https://user-images.githubusercontent.com/102631336/178599853-d2bcd3f7-aa6a-47bc-84e1-6bf34e2716df.png">

Summary:

A betting simulation on matches in the top 5 European football leagues between 2020-2022 was run based on predictions (H = home win, A = away win, D = draw) made by four hypertuned machine learning models trained using fixtures and odds data.

Results:

- All models except for Boosted Trees consistently yielded positive profits from betting whenever they predict an away win.
- The models rarely predict a draw and the profitability is unclear.
- Even though most games end up in a home win, the models consistently yielded negative profits from betting whenever they predict a home win.

##### Part 2: Exploiting Arbitrage

<img width="1276" alt="image" src="https://user-images.githubusercontent.com/102631336/178593469-02734de0-7bbf-4533-a78c-26e290fd5760.png">

Summary:

Another betting simulation on the same matches was run based on arbitrage opportunities.  The alogrithm took advantage of different odds provided by several bookmakers and bet only when (1/market maximum odds for home + 1/market maximum odds for draw + 1/market maximum odds for away) was less than 1.

Results:
- The return on investment was about 9.5% ($75 profit / 2360 matches * $3)


#### [Budget manager](https://joeomatoi.shinyapps.io/budgetmanager/)
<img width="1266" alt="image" src="https://user-images.githubusercontent.com/102631336/178178483-90db8ec7-bb52-4ec4-a8eb-d90194716bc2.png">
<img width="1267" alt="image" src="https://user-images.githubusercontent.com/102631336/178179409-7f74f489-5054-4a7a-83b1-e9d6b3c6f421.png">

Purpose: 

This budget manager allows users to examine their spendings/earnings amounts and categories (rent, groceries, salary, passive income, etc) over time.

How it works:
- Upload Excel file: Uploads a bank transaction excel file (can be downloaded from almost any bank website and the tool is compatible with transaction files of many major banks in the US).
- Assign by:  Assigns a desired category to transactions based on keywords that appear in their names.  For instance, a user can assign the Entertainment category to all transactions whose name includes the keyword "Netflix."  Once assigned, the tool automatically saves the information on category, which will be applied to any new file uploaded later.
- Filter by: Filters the data by date, transaction type, keyword, amount, and category.
- Enter monthly budget: Specifies a monthly budget goal, which appears as a red horizontal line on the left most chart.


#### [Personal task planner](https://joeomatoi.shinyapps.io/shiny_task_planner/)

<img width="1279" alt="image" src="https://user-images.githubusercontent.com/102631336/178034258-537d24cd-9d98-41fc-a284-fa815d83d919.png">

Purpose:

This personal task planner simplifies task management into 1) the optimal order in which tasks should be completed and 2) the number of hours/day required to complete tasks on time.

How it works:

- MANAGE TASKS: Adds to or removes tasks from the calendar, which displays them in 30 minute chunks and orders them by deadline first and then priority level. The surrounding and filled colors of each task communicate whether it is on time, due, or overdue and the priority level relative to other tasks, respectively. 
- EDIT VIEW: Adjusts the number of work hours/day and allows users to observe how many hours/day are required to complete tasks on time.  This function is especially useful when there are overdue tasks in the calendar (surrounded by red).
- EXPORT CALENDAR: The automatically saved calendar can also be exported to Google Calendar through a downloadable csv file (when importing the csv in Google Calendar, the blocks of tasks from the dashboard will be added to the corresponding day, starting at 10 am.)











