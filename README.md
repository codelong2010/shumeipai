# 接受mjpg-streamer视频流的网页
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
最近接触树莓派，想利用树莓派做一个家庭的实时监控。家庭监控发现用motion和mjpg-streamer两个软件的比较多。但后者较为稳定，最后选用了它。
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
这是自己写的一个接受mjpg-streamer视频流的画面，虽然mjpg-streamer有自带一个js的页面，但是最后还是觉得自己写一个比较好。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
html是一个的视频流是局域网的，没有经过外网穿透。
html2是一个可以接受外网访问的网页，经过外网穿透，可以实时观看家里监控的。