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


### DNS records config

+ _code_url_git.app -> //github.com/cdnsop/docs.git	

+ _data_url_json.app -> //raw.githubusercontent.com/cdnsop/docs/main/README.md
	
+ _deploy_config_json.app ->  URL for CD: docker,code,data
	
+ _docker_url_image.app


### dns records update

+ setup
+ restore

  
+ txt:
  + docker: docker hub url
  + code: git repo url
  + data: git repo url 
    
+ cname -> platform
+ 

### dns records graph

+ show all connetcions, dependencies





