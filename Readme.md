# Juz[dʒu:z]

Juz is a new api-gateway designed for enterprise,mainly focus on performance,security and extensibility, juz is totally opensorced, and no premium edition.

- Homepage: http://juz.io
- <a href="ReadmeCn.md">中文Readme</a>


### Project status
Beta version: 0.5.0, it is not recommanded using juz production, we will do more tests to verify.

When refered to traditional api-gateway, there are some problems:
- Manageability
- Performance
- Features lacking
- Need more on authority management
- Monitoring

So, we developed a new one which has been used in our enterprise for two years,  and it got widely praised. Now, you can also use it in your enviroment and enjoy its convenience.

### Install
English doc  is comming soon,before 2018.9.23

### Docs
English doc  is comming soon,before 2018.9.23

### Features

1. Request Proxy
- HTTP and Websocket supported
- Versioning control
- Authentication, signature verification
- Black/White List
- Traffic rate limiting
- Hystrix like 
- Fail and Retry
- Caching
- Canary test

2. Advanced
- Debug mode and logs
- Beautiful UI
- Online managing
- Param verify with regexp
- Multi access mode

2. Application Firewall: WAP
- SQL injection/Command injection/XSS/Webshell etd
- DDOS for application layer
- CC attack

3. Logs
- Access log
- Audit log
- Log analysis

4. Monitoring
- Metrics export to Prometheus
- Jager based distribute tracing
- Application health checking


Juz flow
--- 
![Juz flow](https://upload-images.jianshu.io/upload_images/8245841-09ab7c05653b1bfd.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)