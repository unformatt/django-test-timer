# django-test-timer

Print the amount of time that each unit test took. 

Tested with Django 1.11, Python 2.7

## Install

`pip install django-test-timer`

Then in your Django settings

```
TEST_RUNNER = 'django_test_timer.TimedTestRunner'
```
