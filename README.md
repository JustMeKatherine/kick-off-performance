# Kickstart your performance testing

Agile & Automation 2018 workshop materials

### Description

[Workshop: Kickstart your performance testing ](http://aadays.pl/speakers/konrad-marszalek/)

### Prerequisites

Preferred OS: macOS or Windows.

Download and install:

1. Chrome
2. [Java 8 or 9](https://www.java.com/pl/download/)

JMeter with plugins is already installed inside this repository under apache-jmeter-5.0 directory. It was installed according to [this guide](JMETER_INSTALL.md) 

Install Chrome add-on [Blazemeter plugin](https://chrome.google.com/webstore/detail/blazemeter-the-continuous/mbopgmdnpcbohhpnfglgohlbhfongabi)


### Run JMeter

* macOS: 
```
    ➜  apache-jmeter-5.0 pwd
    /Users/kmarszalek/code/aadays_2018/apache-jmeter-5.0
    ➜  apache-jmeter-5.0 ./bin/jmeter.sh
```

* Windows:
    Go to [YOUR_JMETER_LOCATION]/bin. Run jmeter.bat
    
# Resources

### General
[Performance Testing Guidance for Web Applications](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/bb924375(v=pandp.10))

[Everything You Know About Latency Is Wrong](https://bravenewgeek.com/everything-you-know-about-latency-is-wrong/)

### Tools presented

[Charles](https://www.charlesproxy.com/)

[JMeter](https://jmeter.apache.org/)

[New Relic](https://newrelic.com/products/application-monitoring)

### JMeter tutorials
[Blazemeter channel](https://www.youtube.com/channel/UCTk28DffO_SHVmyonQpgDCg)

### Response time
https://www.nngroup.com/articles/powers-of-10-time-scales-in-ux/
https://developers.google.com/web/fundamentals/performance/rail
https://blog.codinghorror.com/performance-is-a-feature/

### Averages, Percentiles
https://www.vividcortex.com/blog/why-percentiles-dont-work-the-way-you-think

### User think time
https://medium.com/@malith.jayasinghe/performance-testing-with-a-think-time-64b6b737e3f9

### JMeter + InfluxDB + Graphana
http://www.testautomationguru.com/jmeter-real-time-results-influxdb-grafana/

### Example application problems
https://www.appdynamics.com/media/uploaded-files/rootcause.pdf

### JMeter alternatives
[Taurus](http://gettaurus.org/) - ease JMeter automation

[Gatling](https://gatling.io/)

[Lucust](https://locust.io/)

### Cloud based load testing

[Blazemeter](https://www.blazemeter.com/) - can execute your JMeter scripts

[Flood IO](https://flood.io/) - can execute your JMeter scripts

[Loadimpact](https://loadimpact.com/)
