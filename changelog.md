2022-08-08

* Added config.py to gitignore file

* Added IMDb-API api key to config.py

* Created MovieDict object to get data from IMDb-API

* Created data folder to store movie dataset

* Note: Duplicated API calls are running. Ice Age 5: Collision Course ran twice
  in the same run. Maybe it has something to do with updating the dictionary 
  while it's in the same outer for loop? Not sure.




2022-07-24

* changed import statenents to potentially catch/prevent version errors (??) 

* updated test_cases.json to use movieNames as keys

* added a quiz page

* reordered pages (About --> RandomGenerator --> Quiz)

2022-07-23

* forked repo (state: 2022-07-23)

* created a basic app using Dash (hompage with click-for-random, quiz page, about page)

* added a requirements.txt file

* added a test_cases.json file

* added "if name..." boilerplate to fortune_cookie.py so it didn't trigger on import to dash app

* moved fortune_cookie.py and test_cases.py so they could be imported into the app (otherwise above top-level imports)