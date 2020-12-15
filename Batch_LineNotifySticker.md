# การยิงคำสั่งไปยัง LineNotify และส่งกลับมาทาง Line ในรูปแบบ sticker และ ข้อความ
~~~
curl -X POST -H "Authorization: Bearer TOKEN" -F "message=najafamily" -F "stickerId=280" -F "stickerPackageId=4" https://notify-api.line.me/api/notify
~~~
