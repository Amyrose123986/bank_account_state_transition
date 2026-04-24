# State Transition Table

| Initial State | Event | Next State |
|---|---|---|
| Not registered | User signs up | Registered but not logged in |
| Registered but not logged in | User logs in | Logged in |
| Logged in | User logs out | Registered but not logged in |
| Logged in | User deletes account | Account deleted |
| Account deleted | User tries to log in | Account deleted |
| Registered but not logged in | User tries to sign up again with same email | Registered but not logged in |
