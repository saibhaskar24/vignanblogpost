# Vignan

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/cef97503b1a64949a0876a0c27b2c969)](https://app.codacy.com/manual/oscvizag/vignanblogpost?utm_source=github.com&utm_medium=referral&utm_content=saibhaskar24/vignanblogpost&utm_campaign=Badge_Grade_Dashboard)

[![Known Vulnerabilities](https://snyk.io/test/github/saibhaskar24/vignanblogpost/badge.svg?targetFile=requirements.txt)](https://snyk.io/test/github/saibhaskar24/vignanblogpost?targetFile=requirements.txt)

To run locally, do the usual:

## Create a Python 3.5 virtualenv

## Install dependencies

    pip install -r requirements.txt


## Setting up database access

### Create a superuser

   ./manage.py createsuperuser

## File locations

Static files such as CSS, JavaScript or image files can be found in the
``vignanblogpost/static`` subdirectory.

Templates can be found in the ``vignanblogpost/templates`` subdirectory.

CSS is written in `Bootstrap`.



This is a simple blog post written in django. It has features like authentication, user profile , separation of posts based on branch, pagination, UI , adding comments to post, public profiles, social meda authentication and linking, searching if posts based on text, creating new post by authorised users, email confirmation if the user didn't creat his/her account from social authentication, deletion and updation of post by admin and the author of the post. This is using bootstrap as frountend and postgresql as database. This is deployed in heroku.  
