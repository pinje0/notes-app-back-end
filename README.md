for CORS problem change browser://flags

| Features                                                        |                                                           Listed                                                            |
| --------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------: |
| Insecure origins treated as secure                              | Enabled (You can add <br> `http://localhost,http://localhost:5000,http://notesapp-v1.dicodingacademy.com`on origin section) |
| Allow invalid certificates for resources loaded from localhost. |                                                           Enabled                                                           |
| Block insecure private network requests                         |                                                           Default                                                           |

Run command PM2:

-   Start initialization : `pm2 start npm --name "notes-api" -- run "start-prod"`
-   Restart : `pm2 restart notes-`api`
-   Stop : `pm2 stop notes-api`
-   Start again : `pm2 start notes-api`
