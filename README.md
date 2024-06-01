Follow Invidious Docs - [https://docs.invidious.io/improve-public-instance/#2-multiple-invidious-processes](https://docs.invidious.io/improve-public-instance/#2-multiple-invidious-processes)

My documentation (may not be up to date) - [https://docs.msinfo32.uk/Self%20Hosting/Invidious/Invidious/](https://docs.msinfo32.uk/Self%20Hosting/Invidious/Invidious/)

Archived copy of my docs (just incase!) - [https://archive.ph/oHQkb](https://archive.ph/oHQkb)

Cronjob:

```cron
0 */1 * * * docker restart invidious-invidious-1
1 */1 * * * docker restart invidious-invidious-2
2 */1 * * * docker restart invidious-invidious-3
```
