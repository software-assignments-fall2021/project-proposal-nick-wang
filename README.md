# Project Proposal: LifeNote

By Letian Ye, Yiming Yu, Yaolin Zhang, Zhuofeng Wang, Susan Liu, Laura Lou

### What and why?
LifeNote is a web app the helps people to take four main types of records of their life altogether in one app, and also provides visualization and some intelligence features.

**Four types of records:**

- Diary
- Account book
- Calendar and Schedule
- Memorandum and Reminders

We might see all sorts of apps for each of the four records, but few apps are able to take all four records equally well. LifeNote provides a single app for most of the records that people want to take about their life.


### For whom?
For students, workers, or basically anyone who is interested in planning their life, and wants to have a simple app to help them scheduling, for personal usage only.


### How?

**Friendly user interface !**

#### Diary:

- Basic diary format guiding and auto formatting (Different types of diary?)
- Capable of inserting emoji and pictures. (Support videos would be best.)
- Support underline highlights, keywords or add tags for each diary.
- **Overview and visualization:**
  - [ ] Tag/Keyword/Highlight sentence **cloud** of weeks, months and years.
  - [ ] Annual conclusion
  - [ ] "**That year today**"：What happened to you the same day last month or last year, and highlights.

#### Account book:

-  Similar to Google's main page. Logo (Function name) in the middle and a search bar that acts as an input bar here.
  - Capable of directly searching for amount, name, date...
  - Bar can split into four (visually). [Event/Item] [Spend/Receive] [Amount] [Tag/Type] when user want to input
- Budget this month/week/year. A bar under the search bar will fill in color to visualize the budget amount, and how close you are to the budget, with customize color.
- Pie/Fan chart under the Budget bar, visualize the percentage of each Type/Tag in the account book, click sections to see details. Can have several charts representing weeks/months/years in one line.
- Basic sorting of name, amount, date in detail page.

#### Calendar and Schedule

- Basic overview and function of a calendar for one month or one week.
- Basic functions for adding events and deadlines on days and time periods by selecting a time period/day.
- **For week's view**:
  - [ ] “Today” is always on the left second column, “Yesterday” is marked gray. “Days” are scrollable to the left.
  - [ ] Certain time periods can be locked, such as time periods for your classes.
  - [ ]  **"Deadline Mini Bar"**: created with the "new" button on top left, a mini bar will show up on the right. You can edit its title (no more than a certain amount of words) and color, and drag it into the week's view, anywhere to set the time. (Hold it on a time period for a while to zoom in into more detailed time scale, of course you can drag it again to reset time, or drag to bottom to delete it) When the time is set down:
    - [ ] Details about the assignment / event
    - [ ] Tag of the assignment, for example, "CS 101 (Prof name) homework" 
    - [ ] How much time you expect to finish this:
      - [ ] When the mouse hovers on this mini bar, it will show another bar (or time zone covering the days with the mini bar's color) that indicates when you should start. Users can also set that this will show in week's view by default
    - [ ] Users can set how much time they actually spent on this event later. We can also provide a Timer for users to voluntarily record the time：
      - [ ] These time data with tags on events can help to give a suggestion about "how much time you might need to finish the task" for next similar assignments.
      - [ ]  If users allow us to share their time spent and event tags to other users, we can have more data to give suggestions for new tasks and even more on events that share the same tag.
    - [ ] Suggestion: 4 colors for "mini bar":  among important and urgent, e.g. important but not urgent ...

#### Memorandum and Reminders

To be honest, this might not be suitable for a web app, your smartphone must have this and more convenient, but since we are "LifeNote", implement it!

#### Local Backup

Users can backup their data for all four types of records by downloading a single file to their local storage.


### Scope
This task needs massive front-end tasks, good visualization and animation will improve the app a lot. A little ambitious if want to implement exactly like what in the proposal, to be honest. **Six-people** group might be necessary. To act as a course assignment, **some functions that have a task check icon might need to be cut to reduce workload**.
