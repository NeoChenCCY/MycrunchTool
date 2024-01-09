# MycrunchTool
密碼產生器
##此程式是用字典產生工具crunch，產生破解密碼專用的密碼字典。
##裡面的密碼符合國際密碼組織(NIST)規定的舊版密碼格式(nistspecialpublication800-63ver1.0.2):
#1. 長度超過8碼
#2. 至少涵蓋1個大寫英文字母
#3. 至少涵蓋1個小寫英文字母
#4. 至少涵蓋1個特殊符號
##備註: 輸出容量很大!光只有8碼的PASSWORD檔案容量就大約56941832366 MB =55607258 GB =54303 TB =53 PB，總計有6634204312890625組密碼!

##【指令】crunch 5 8 -f /usr/share/crunch/charset.lst mixalpha-numeric-all-space -o ~/Mycrunch/Mypasswordlist.txt  
##【環境設定說明】
#1. 請自己建立新的資料夾(資料夾名稱指名 Mycrunch)，將.py檔案放入資料夾內執行
#2. OS建議使用Kali(版本 5.7.0-kali1-amd64):kali-linux-2020.3-installer-amd64.iso、kali-linux-2020.3-installer-i386.iso
