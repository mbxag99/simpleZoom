# simpleZoom
1.פתח את הפרויקט באמצעות :

visual studio code 
---------------------------------
2.התקן את התלות הבאות באמצעות הפקודה למטה(וודא ש nodejs קיים במערכת שלך)

npm i express ejs socket.io

npm i uuid

npm i --save-dev nodemon

npm i -g peer

----------------------------------
3.בשביל להפעיל את התוכנה כתוב ב powershell/terminal :

npm run devStart
--------------------------------
4.גם אתה חייב לפתוח עוד חלון powershell/terminal (לא באותו מסך של שלב 3) ולכתוב : (//השלב הזה הוא בשביל להפעיל את API שמאפשר למערכת 
לזהה את המשתמשים במספר זיהוי ייחודי//)

peerjs --port 3001

אם נתקלתה עם בעית 
"\peerjs.ps1 cannot be loaded because running scripts is disabled on this system. For more 
information"

כתוב את זה

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted
-------------------------------

--בשביל להשתתף באותו חדר העתיק את הכתובת של החלון (localhost:3000/**uuid) ופתוח חלון חדש והדביק את הכתובת בו

APIS ו ספריות ו ציודים שהשתמשתי בו

1.express - השרת שבו נשתמש

2.ejs - כשפת תבנית

3.socket.io- ערוץ המאפשר לנו לקיים תקשורת בזמן אמת עם הלקוח והשרת

4.uuid -תלות ביצירת כתובות אתרים דינמיות, כך שמשתמשים יכולים לשוחח בצ'אט בחדרים שונים עם כתובות אתרים ייחודיות שנוצרו

5.nodemon- תלות מפתח המאפשרת לנו לרענן את השרת באופן אוטומטי

6.peerjs -מפשט את תקשורת וידאו peer-to-peer



- add share screen button
- add button to play games (connect 4/15 puzzle multiplayer)
