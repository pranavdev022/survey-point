# survey-point
This is a full featured polling app. A user has to register in this app to show the polls and to vote. If a user has already voted, they can not vote again. Only the owner of a poll can add a poll, edit a poll, update a poll, delete a poll, add a choice, update a choice, delete a choice, and end a poll. If a poll is ended, it can not be voted. The ended poll only shows the user the final result of the poll. There is a search option for polls. Also, users can filter polls by name, publish date, and by number of votes. Pagination will work even after applying a filter.

<h2>Prerequisites</h2>
<code>python== 3.5 or up and django==2.0 or up</code>

<h2>To migrate the database open terminal in project directory and type</h2>
<code>python manage.py makemigrations</code><br>
<code>python manage.py migrate</code>

<h2>To use admin panel you need to create superuser using this command </h2>
<code>python manage.py createsuperuser</code>

<h2>To Create some dummy text data for your app follow the step below:</h2>
<code>pip install faker</code>
<code>python manage.py shell</code>
<code>import seeder</code>
<code>seeder.seed_all(30)</code>
<p>Here 30 is a number of entry. You can use it as your own</p>

<h2> To run the program in local server use the following command </h2>
<code>python manage.py runserver</code>

<p>Then go to http://127.0.0.1:8000/home in your browser</p>

