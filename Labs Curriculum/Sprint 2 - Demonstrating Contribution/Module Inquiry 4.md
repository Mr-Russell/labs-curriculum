# Module Inquiry 4

## Questions

1. Link to the pull request you are most proud of.

    https://github.com/buildweek-water-my-plants-1-06222020/backend/pull/8/files


2. Why are you proud of this feature? What was difficult about its implementation?

    This pull request was to replace my original SQLite3 database with a PostgreSQL database. I am very proud that I got this to work because I had spent much more time using SQLite3, and was much more comfortable with that instead of PostgreSQL. This was difficult because I had minimal experience with PostgreSQL and had to do a fair amount of research on my own time in order to get it to work properly


3. How does this feature help the user?

    Originally when I was using SQLite3, every time I pushed new code, that would completely reset the database and erase any user data that had been created since my last update. PostgreSQL is a persistent database structure, meaning any time I pushed new code, the database would never get reset, and users did not have to constantly recreate new accounts.


4. Think about the process of delivering this feature: from ideation, to scoping, to pairing, to testing. Knowing what you know now, what would you change about the way in which you delivered this feature?

    When I originally deployed my backend code, I set it up to use SQLite3. It wasn't terribly difficult to change everything over to PostgreSQL, but if I had to do everything over again I would definitely build it with PostgreSQL from the beginning. I'm sure I could take a look at my code and figure it out again, but I wish I took better notes on how to build a PostgreSQL database step by step. Using SQLite3 gave the frontend developers a lot of issues, and after switching to PostgreSQL everything ran very smoothly