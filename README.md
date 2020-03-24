Django-Project Steps:

Go to any working directory you want.

Use following command to create Virtualenv space

      Windows: mkvirtualenv mysubject
      
Go into your Virtualenv space using:

       Windows: workon mysubject
       
Install Django inside Virtualenv space using:

       pip install Django
       
Check Django version using:

       python -m django --version
       
Create first project using:

      django-admin startproject myapp
      
Check if project is built successfully, go to mysite directory first:

      python manage.py runserver
      
Create app called personalweb using:

     python manage.py startapp personalweb
     
Set up project url using information provided in mysite_url.txt(Django2 and Django1 aredifferent)

Go to personalweb directory, create a file called urls.py, copy paste the information provided inpersonalweb_url.txt

Add your personalweb app to settings.py (add following code to INSTALLED_APPS section):

      'personalweb.apps.PersonalwebConfig',
      
Go to personalweb directory, define a new view called index in views.py.(information providedin personalweb_view.txt)

Go to personalweb directory, create a directory called templates. In templates, create adirectory called personalweb, in personalweb create a file called index.html. ( content ofindex.html is provided in index_html.txt)

