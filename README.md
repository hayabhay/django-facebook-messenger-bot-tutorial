# Facebook Messenger Bot tutorial using Django/Python

This has the starter code for the tutorial I wrote on my Blog.

[Tutorial: How to build a Facebook Messenger bot using Django, Ngrok](https://abhaykashyap.com/blog/post/tutorial-how-build-facebook-messenger-bot-using-django-ngrok)

## How to use

Run the following commands. You will need Python 2.7+/3.3+ and have [Virtual Environment Wrapper](http://virtualenvwrapper.readthedocs.io/en/latest/) setup.

    git clone https://github.com/abhay1/django-facebook-messenger-bot-tutorial.git
    cd django-facebook-messenger-bot-tutorial
    mkvirtualenv bottutorial
    pip install -r requirements.txt
    cd yomamabot
    python manage.py runserver

Follow the tutorial to setup Ngrok.
Edit the `VERIFY_TOKEN` variable in `django-facebook-messenger-bot-tutorial/yomamabot/fb_yomamabot/views.py` to include the Verify token.
It is set to `2318934571` as default that is used in the tutorial. This can be any token as long as it matches the one you tell Facebook.

Once you have your webhook setup, get your Page Access Token. Then set the `PAGE_ACCESS_TOKEN` variable in the file `django-facebook-messenger-bot-tutorial/yomamabot/fb_yomamabot/views.py` to your page access token. 
