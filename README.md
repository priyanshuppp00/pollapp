# Django-Poll-App
Django poll app is a full featured polling app. You have to register in this app to show the polls and to vote. If you already voted you can not vote again. Only the owner of a poll can add poll , edit poll, update poll, delete poll , add choice, update choice, delete choice and end a poll. If a poll is ended it can not be voted. Ended poll only shows user the final result of the poll. There is a search option for polls. Also user can filter polls by name, publish date, and by number of voted. Pagination will work even after applying filter.

<h1>Getting Started</h1>
<p>These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.</p>

<h2>Pre requisites</h2>
<code>python== 3.5 or up and django==2.0 or up</code>

<h2>Installing</h2>
<pre>open terminal and type</pre>
<code>git clone https://github.com/PPP-K/Pollapp</code><br><br>

<h4>or simply download using the url below</h4>
<code>https://github.com/PPP-K/Pollapp</code><br>

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


<h2>Configure Email - Poll Owner receives Email when vote is cast by user</h2>
<p>Get your smtp host details and replace following values in your</p> <code>settings.py</code>

<h3>Configure email settings</h3>
<code>EMAIL_HOST = '<your smtp host>'</code><br>
<code>EMAIL_PORT = '<smtp port>'</code><br>
<code>EMAIL_HOST_USER = '<smtp host user>'</code><br>
<code>EMAIL_HOST_PASSWORD = '<smtp host pass>'</code><br>
<code>DEFAULT_FROM_EMAIL = '<from email address>'</code><br>

<h2> To run the program in local server use the following command </h2>
<code>python manage.py runserver</code>

<p>Then go to http://127.0.0.1:8000/home in your browser</p>

<h2>Project snapshot</h2>

#### Home page
![Screenshot (52)](https://github.com/user-attachments/assets/cabbddbf-68fe-4f09-b10e-e8a58ee9dbbc)



#### Login Page
![Screenshot (53)](https://github.com/user-attachments/assets/4d54843f-5705-4a69-a4a7-23356f04a1f9)


#### Registration Page
![Screenshot (54)](https://github.com/user-attachments/assets/07279bcf-222f-428d-8d66-51a8e511df2c)

#### Poll List Page
![Screenshot (56)](https://github.com/user-attachments/assets/5ab0cf41-a570-4091-a534-5ae8c17851b4)



#### Poll Add Page
![Screenshot (59)](https://github.com/user-attachments/assets/34e2e813-0f21-474a-8822-5a7da1555a13)

#### Polling page
![Screenshot (58)](https://github.com/user-attachments/assets/dba13334-6f5a-4051-bcef-618ad096a0d9)

#### Poll Result Page
![Screenshot (61)](https://github.com/user-attachments/assets/ef80d906-eb86-4a4e-a940-12b6b58c1392)

#### Poll Edit Page
![Screenshot (60)](https://github.com/user-attachments/assets/139fbe2d-49f0-47f9-9827-76f89e0f8d3b)


<h2>Author</h2>
<blockquote>
  Priyanshu<br>
  Email: example@gmail.com
</blockquote>

<div align="center">
    <h3>========Thank You !!!=========</h3>
</div>
