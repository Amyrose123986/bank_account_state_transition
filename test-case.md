
Not registered

| Step | Event | Expected State |
|---|---|---|
| 1 | User signs up | Registered but not logged in |
| 2 | User logs in | Logged in |
| 3 | User logs out | Registered but not logged in |
| 4 | User tries to sign up again with same email | Registered but not logged in |
| 5 | User logs in | Logged in |
| 6 | User deletes account | Account deleted |
| 7 | User tries to log in after deletion | Account deleted |

