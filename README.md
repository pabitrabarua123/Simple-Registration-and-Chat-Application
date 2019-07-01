# Simple-Registration-and-Chat-Application
This project is done using PHP, Mysql, Javascript and Ajax. For testing you can use WAMP OR XAMP local server. But internet connection is required because jquery and logo image is taken from third party server. If you want to deploy it in live server the you need to do some changes in the script that you can understand by going through rest of the documentation. 

## Basic Setup
Download the repository and change the folder name 'Simple-Registration-and-Chat-Application-master' to 'mounty'. Copy the folder and paste it into your XAMP's htdocs OR WAMP's www folder. Changing the folder name to 'mounty' is important. Otherwise routing and other php script will not work.

![enter image description here](https://lh3.googleusercontent.com/Th91szbdr-Om2l59egqi-hJ8tIedlz4AwjoadJZH2-eqWwvR_25b0_gYI1Lok6bmG__E3vX69VCt "routing")

## Database
Open the 'mounty' folder and navigate to 'Database' folder. Copy the 'mounty_db.sql' file and import it to your database server by creating a database named mounty_db. If you want to change the database name then you have to change it in the connection.php accordingly.

![enter image description here](https://lh3.googleusercontent.com/WtQGwvIPTYwh6_as346zEfqkUqJbR4GjTfoSJxruOV5Twq3qALjjDV73NJOY2hXRHm-GWDSSOdrc "conn")

Now open 'localhost/mounty' in your browser and you should see...

![enter image description here](https://lh3.googleusercontent.com/0jyL4m4eZtAwu0yfud-zkrUHP4MhuVWUv2UyhVl10xccVpnrJJtrQv6Fg4YQF90I7nC-uaZWQEHK "login")

Ready, set, go ... register, login and enjoy chating.
