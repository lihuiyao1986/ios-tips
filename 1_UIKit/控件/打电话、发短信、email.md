## 打电话、发短信、email

````objc
[[UIApplication sharedApplication] openURL:[NSURL URLWithString:@"sms://13851488992"]]; //sms
[[UIApplication sharedApplication] openURL:[NSURL URLWithString:@"tel://13851488992"]]; //tel
[[UIApplication sharedApplication] openURL:[NSURL URLWithString:@"mailto:coolnameismy@sina.com"]]; //email
````
