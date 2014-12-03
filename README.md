nalkutin
========

Running check_hours script:

Get Toggl API token from https://www.toggl.com/app/profile to secret.py:
```
api_token = 'xxxxxxxxxxxxxxxxx' # toggl api key
```

Running get_userids script:

```
get_userids --wid WORKSPACE_ID
```

Fastest way to find out your WORKSPACE_ID is to visit https://www.toggl.com/app/projects/ and observe the address bar.

Your workspace id is shown as follows:

```
https://www.toggl.com/app/projects/%WORKSPACE_ID%/
```
