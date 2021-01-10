# Description
- gilgil's network suricata-rule lab
- https://gitlab.com/gilgil/sns/-/wikis/suricata/report-suricata-rule

# Usage
```bash
sudo suricata -s homework.rules -i ens33
```
```bash
cd /var/log/suricata/
tail -f fast.log
```

# Detecting Site List
### HTTPS (16)
```
www.naver.com                                           
notion.so     
mail.google.com    
www.youtube.com 
github.com   
gitlab.com        
na.leagueoflegends.com
sugang.snu.ac.kr
www.facebook.com
twitter.com 
twitch.tv             
j-jaeyoung.tistory.com
suricata.readthedocs.io
dreamhack.io
webhacking.kr  
www.acmicpc.net
```
### HTTP (4)
```
warning.or.kr
www.kyobobook.co.kr
pwnable.kr
afreecatv.com
```


# Reference
- https://suricata.readthedocs.io/en/suricata-6.0.1/index.html
- https://linefilt.tistory.com/category