# electron-active-win-crash

Reproducible on Windows 10.

```shell
npm i
electron-rebuild
npm start
```

In the `main.js` there is a code which will take `activeWindow` each 5 sec. After `npm start` just wait for 10 seconds.
Do not change active window during this time.
App will crash when will try to take activeWindow for the same window second time.
