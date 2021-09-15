# CYBR3120-HW1
GitHub Repo Homework for CYBR3120

HTTP Response Codes:

## 200
Site:
https://dunwoody.instructure.com/courses/7792/modules

Raw Response from Chrome:

cache-control: no-cache, no-store
content-encoding: br
content-type: text/html; charset=utf-8
date: Thu, 09 Sep 2021 01:52:29 GMT
etag: W/"cda1b187100e33266d1672d9ed8d3a01"
p3p: CP="None, see http://www.instructure.com/privacy-policy"
pragma: no-cache
referrer-policy: no-referrer-when-downgrade
server: Apache
set-cookie: _csrf_token=R77wiSWvQljRuujY%2Bgl%2B3iW0Px1fqB3GasKXF3H9uUsgz7rhF%2FwHDZPpio6xIjyHQoJVLgueKpEj9cd2IYT8cw%3D%3D; path=/; secure
set-cookie: log_session_id=bfa3bef3ce47314c4df54a446af28dbf; path=/; secure; HttpOnly
status: 200 OK
strict-transport-security: max-age=31536000
vary: Accept-Encoding
x-a11y-ally: Dana Danger Grey
x-canvas-meta: q=868;a=1;g=8cDORZAX0gyZcyxWaSDwUai5y34cTLlUzJNZbdRv;s=8900;c=cluster21;z=us-east-1b;o=context_modules;n=index;t=Course;i=7792;x=5.0;p=f;e=3570653;f=2021-09-09T01:52:29.25Z;b=1592156;m=1592156;u=0.21;y=0.02;d=0.05;
x-canvas-user-id: 89000000000004668
x-content-type-options: nosniff
x-download-options: noopen
x-frame-options: SAMEORIGIN
x-permitted-cross-domain-policies: none
x-rate-limit-remaining: 700.0
x-request-context-id: a6f3be8d-853f-4559-be46-951a734b400f
x-request-cost: 0.26091096400614333
x-request-processor: 01b6fea50b3df5917
x-runtime: 0.310824
x-session-id: bfa3bef3ce47314c4df54a446af28dbf
x-xss-protection: 1; mode=block

## 301
General Header from Chrome:

Request URL: http://google.com/
Request Method: GET
Status Code: 301 Moved Permanently
Remote Address: 142.250.190.142:80
Referrer Policy: strict-origin-when-cross-origin

## 400
curl -i https://dunwoody.instructure.com/courses/7792/assignments/170929?module_item_id=276914

HTTP/2 400 
date: Wed, 15 Sep 2021 22:06:40 GMT
content-type: text/plain; charset=utf-8
server: Apache
x-request-context-id: 9699bef4-fd93-4e98-bdf3-392fb519d804
vary: Accept-Encoding
x-rate-limit-remaining: 700.0
x-canvas-meta: q=1057;a=1;g=8cDORZAX0gyZcyxWaSDwUai5y34cTLlUzJNZbdRv;s=8900;c=cluster21;z=us-east-1c;o=assignments;n=show;t=Course;i=7792;b=1221444;m=1221444;u=0.02;y=0.00;d=0.00;
pragma: no-cache
x-frame-options: SAMEORIGIN
x-request-cost: 0.022028476999253144
cache-control: no-cache, no-store
strict-transport-security: max-age=31536000
referrer-policy: no-referrer-when-downgrade
x-permitted-cross-domain-policies: none
x-xss-protection: 1; mode=block
x-download-options: noopen
x-runtime: 0.033011
x-content-type-options: nosniff
set-cookie: _csrf_token=yQ3zQ%2F66cXhRiNxME3wb7NglXcj65oki%2BQVmJIAecXuCV5UokM0UCBLQtRVkK3elmlxyo56kw1edYU1w8WocSw%3D%3D; path=/; secure
x-request-processor: 01b61db9ec2c99c8d
x-a11y-ally: Dana Danger Grey
status: 400 Bad Request
p3p: CP="None, see http://www.instructure.com/privacy-policy"

endpoint does not support   

## 404
General Header from Chrome:

Request URL: https://en.wikipedia.org/poopsicle
Request Method: GET
Status Code: 404 
Remote Address: 208.80.154.224:443
Referrer Policy: strict-origin-when-cross-origin
