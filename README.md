# python_cheatsheet

#### Python Tutorial: Logging Basics - Logging to Files, Setting Levels, and Formatting
https://www.youtube.com/watch?v=-ARI4Cz-awo

#### Python Tutorial: Logging Advanced - Loggers, Handlers, and Formatters
https://www.youtube.com/watch?v=jxmzY9soFXg

#### How to embed plotly graphs in websites
https://www.youtube.com/watch?v=kxPZV9ileKI

#### LEARN PLOTLY - CREATING MAPS
https://www.youtube.com/watch?v=D35m2CdMhVs

#### Plotly Tricks
https://plot.ly/python/hover-text-and-formatting/
https://plot.ly/python/colorscales/#customizing-tick-text-on-logarithmic-color-bars

#### Dropping rows from a PANDAS dataframe where some of the columns have value 0
https://codereview.stackexchange.com/questions/185389/dropping-rows-from-a-pandas-dataframe-where-some-of-the-columns-have-value-0/185390
```
df = df[(df[['A','C']] != 0).all(axis=1)]
```

#### Not all parameters were used in the SQL statement (Python, MySQL)
https://stackoverflow.com/questions/20818155/not-all-parameters-were-used-in-the-sql-statement-python-mysql
The parameter marker is `%s` not `%d`.
```
add_user = """INSERT INTO DB.tbluser 
              (username, department, startyear, currentpos, link) 
              VALUES (%s, %s, %s, %s, %s)"""
```
Note that the parameter markers used by `mysql.connector` may look the same as the `%s` used in Python string formatting but the relationship is only coincidental. Some database adapters like oursql and sqlite3 use ? as the parameter marker instead of `%s`.


#### How to get the home directory in Python?
https://stackoverflow.com/questions/4028904/how-to-get-the-home-directory-in-python

#### Data Visualization GUIs with Dash and Python
https://www.youtube.com/watch?v=J_Cy_QjG6NE&list=PLQVvvaa0QuDfsGImWNt1eUEveHOepkjqt

#### Python Selenium Refused to connect to URL because it violates the following Content Security Policy directive: connect-src self URL
https://stackoverflow.com/questions/59207838/refused-to-load-the-script-because-it-violates-the-following-content-security-po
<br>https://stackoverflow.com/questions/53304222/relaxing-chromes-csp-while-running-tests-webdriver-content-security-policy
<br>https://stackoverflow.com/questions/54980323/refused-to-load-the-script-xyz-js-because-it-violates-the-following-content-se

#### Extract a part of URL - python
https://stackoverflow.com/questions/17695662/extract-a-part-of-url-python
