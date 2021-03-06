# ===============
# Django Polled:

# Polls App
# ===============

#### Polls is a Django app to conduct Web-based polls.  
#### For each question, visitors can choose between a fixed number of answers.  

#### Detailed documentation is in the "docs" directory.  

### Quick start  
-----------

1. Add "polls" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'polls',
    ]

2. Include the polls URLconf in your project urls.py like this::

    path('polls/', include('polls.urls')),

3. Run ``python manage.py migrate`` to create the polls models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a poll (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/polls/ to participate in the poll.

-----------
Github: 
https://github.com/edchelstephens/django-polled  

Package Index:
https://test.pypi.org/project/django-polled-edchelstephens/

Written with <3 by:  
Edchel Stephen B. Nini  
edchelstephens@gmail.com  
https://pypi.org/user/edchelstephens/  
https://github.com/edchelstephens  
https://www.linkedin.com/in/edchelstephens/  
