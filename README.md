This is the python library for the [Samurai API](http://feefighters.com/samurai) from [Fee Fighters](http://feefighters.com).

(README in progress)

## Installation ##

This library currently isn't a proper Python module, so you will have to get the source. The main directory serves as a module. It also serves as a Django app, if you're interested in that.

## Core

If you're just interested in using the API in itself 

## Django


In settings.py:

    import samurai_client_python.core as samurai

    SAMURAI_CREDENTIALS = samurai.FeeFighters(merchant_key = [your merchant key], merchant_password = [your merchant password])
    SAMURAI_SALT = # A randomly generated string
    SAMURAI_NEWMETHOD_ERROR_REDIRECT = # name of URL you want to redirect to upon error creating a new mayment method
    SAMURAI_NEWMETHOD_REDIRECT = # name of URL you want to redirect to upon success creating a new mayment method
    SAMURAI_UPDATEMETHOD_ERROR_REDIRECT = # name of URL you want to redirect to upon error updating a mayment method
    SAMURAI_UPDATEMETHOD_REDIRECT = # name of URL you want to redirect to upon success updating a mayment method


To create a transparent redirect form.

    import samurai_client_python.views

    
    

how to use the trans_redir thing 







How the views work:



test_credentials.py

    Django-authentication required. Django-South supported, migrations included.

## Testing

### Credentials

If you want any of the tests to pass, you will need to create a file called test_credentials.py

### Django

If you don't have this properly configured as part of Django, the Django tests will not pass.