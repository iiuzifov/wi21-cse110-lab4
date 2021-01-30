* The bug was addon both numbers as strings, therefore appending them
* The fix would be to change line 9 to this, aka force convert them all to int
```let result = parseInt(num1) + parseInt(num2)```

1. citylogs.json
2. part2.js
3. 11687628 bytes
4. 70.10ms
5. Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.104 Safari/537.36
6. Apache
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. fetch()