# docs
docs.cdnsop.com - documentation 


## Use cases


### dns records read

+ backup
+ check before update
+ list configuration

#### backup as files

+ domainname.com/
  + _jloads.www.txt 
```json
{
 "head": [
   "//code.jquery.com/jquery-3.5.1.min.js",
   "//stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js",
   "//stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css",
   "//app.wapka.pl/css/style.css"
 ],
 "body": [
   "//app.wapka.pl/html/body.html"
 ],
 "#form": [
   "//app.wapka.pl/html/create.html",
   "//app.wapka.pl/js/create.js"
 ],
 "#image": [
   "//logo.wapka.pl/wapka-300.png"
 ]
}
```

  + www.cname -> cloud provider: username.platform.com  
  + [dns-srv-record](https://www.cloudflare.com/learning/dns/dns-records/dns-srv-record/)


### dns records update

+ txt:
  + environment: docker hub url
  + application: git repo url
  + data: git repo url 
    
+ cname -> platform
+ 

### dns records graph

+ show all connetcions, dependencies





