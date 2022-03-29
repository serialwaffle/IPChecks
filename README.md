# My IP Query
 
 An alphabetical list of URLs that will return the requester's external IP address.
 
All examples below are used/tested in Linux bash and Windows cmd.

For use cases in other languages, [Click Here.](https://github.com/serialwaffle/MyIPQuery/blob/main/CodeSamples.md)

For the list in text form, [Click Here.](https://github.com/serialwaffle/MyIPQuery/blob/main/list.txt)
 
 @serialWaffle if you want to contribute.

## The list.


https://akamai.com
```
curl http://whatismyip.akamai.com
```
<details>
  <summary>Notes</summary>
None.
</details>

 <br />

https://amazon.com
```
curl https://checkip.amazonaws.com
```
<details>
  <summary>Notes</summary>
None.
</details>

 <br />
 
https://dyndns.org
```
curl http://checkip.dyndns.org
```
<details>
  <summary>Notes</summary>
None.
</details>

 <br />
 
https://google.com
```
 dig TXT +short o-o.myaddr.l.google.com @ns1.google.com
```
<details>
  <summary>Notes</summary>
If dig is available.
</details>

 <br />
 
https://hostip.info
```
 curl http://api.hostip.info/get_json.php
```
<details>
  <summary>Notes</summary>
Returns JSON.
</details>

 <br />

https://icanhazip.com
```
curl https://icanhazip.com
```
<details>
  <summary>Notes</summary>
None. 
</details>

<br />

https://ident.me
```
curl https://ident.me
```
<details>
  <summary>Notes</summary>
None. 
</details>

<br />

https://ifconfig.co
```
curl https://ifconfig.co
```
<details>
  <summary>Notes</summary>
None. 
</details>

<br />

https://ifconfig.me
```
curl https://ifconfig.me
```
<details>
  <summary>Notes</summary>
None. 
</details>

<br />

https://ipgrab.io
```
curl https://ipgrab.io
```
<details>
  <summary>Notes</summary>
None. 
</details>

<br />

https://ipapi.co
```
curl https://ipapi.co/ip/
```
<details>
  <summary>Notes</summary>
None. 
</details>

<br />

https://ipecho.net
```
curl https://ipecho.net/plain
```
<details>
  <summary>Notes</summary>
None. 
</details>

<br />

https://ipify.org
```
curl https://api.ipify.org
```
<details>
  <summary>Notes</summary>
Use:
  
  ```
   curl https://api.ipify.org?format=json
  ```
  To return JSON
</details>

 <br />
 
 https://ipinfo.io
```
curl https://ipinfo.io/ip
```
<details>
  <summary>Notes</summary>
Leave off /ip for more info. 
</details>

 <br />
 
 https://jsontest.com
```
curl http://ip.jsontest.com/
```
<details>
  <summary>Notes</summary>
None. 
</details>

 <br />

https://myexternalip.com
```
curl https://myexternalip.com/raw
```
<details>
Use:
  
  ```
   curl https://myexternalip.com/json
  ```
  To return JSON
</details>

<br />

https://myip.com
```
curl https://api.myip.com/
```
<details>
  <summary>Notes</summary>
Returns JSON.
</details>

 <br />
 
 https://opendns.com
```
nslookup myip.opendns.com. resolver1.opendns.com
```
<details>
  <summary>Notes</summary>
Uses resolver1.opendns.com dns server to resolve the magical myip.opendns.com hostname to your ip address.
Also works with dig:
 
 ```
 dig +short myip.opendns.com @resolver1.opendns.com 
 ```

 Returns DNS response.
</details>

 <br />
 
https://seeip.org
```
curl https://ip.seeip.org/
```
<details>
  <summary>Notes</summary>
None.
</details>

 <br />
 
https://trackip.net
```
curl https://www.trackip.net/ip
```
<details>
  <summary>Notes</summary>
None.
</details>

 <br />






