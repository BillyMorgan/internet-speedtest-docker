# internet-speedtest-docker
Here in Brazil is a mess to contract a good ISP, they just don't delivery the speed they should for the users. Generally in a small business or a residence you can't pay for a very expensive plans where they certify the bandwidth delivered. So you have to call them many times complaining about the speed of your internet connection and always they will ask you to do that Internet Tests Online, such as [SpeedTest](http://www.speedtest.net), [AT&T SpeedTest](http://www.att.com/speedtest/), [TestMyNet](http://testmy.net), most of this tests is based only on ICMP messages that don't reflect your real bandwidth on that time. Or even worse your ISP can allow all trafic ICMP so when you test appers that you have a good speed but when you have to download some content you can't do it well.

This project won't help you with your connect, acctually this project born when I need to start monitoring the speed, create a report to send to my ISP take some action. So, using **Docker Compose** I put together three containers with all the tools needed to monitoring and display the status of your Internet Speed (and I know that tool can do more or can be better).

- 
