# A-Simple-C-Thread-Pool

Introduction
--------------
1、线程池中的线程分为管理线程、工作线程<br>
2、管理线程负责动态监控线程池，动态创建工作线程、或杀死多余空闲工作线程<br>
3、每个工作线程创建时会注入一个相应的回调函数
