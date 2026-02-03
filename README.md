# start-menu-win-11-to-win-10
for thai people 

มันเรียกว่า ExplorerPatcher ซึ่งสามารหาใน github หรือลิ้งที่แนบนี้
https://github.com/valinet/ExplorerPatcher

แล้วไปด้านขวา กด relaeses โหลดตัวล่าสุด ep_setup.exe แล้วลงเลย

ถ้าอยากให้คลิกขวาที่ desktop เป็นแบบเดิม ให้ก๊อปคำสั่งนี้ไปวางใน cmd > enter  restart ทีนึง

reg.exe add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve

แล้วทุกอย่างก็จะเป็นเหมือน window 10 ทั้ง start menu และ คลิกขวา desktop



https://youtu.be/OMG7kuSJBm4
