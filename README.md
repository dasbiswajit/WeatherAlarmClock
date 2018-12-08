# WeatherAlarmClock

![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/logo.png)

Introduction
-----------------
The weather alarm clock is an alarm clock with a weather reminder. It is inspired by the embarrassing situation of forgetting to watch the weather forecast without an umbrella before going out.

Main functions: alarm clock, weather forecast, timer, recording, city management, city search, automatic positioning, theme switching, scanning QR code, creating QR code, clearing cache, one-click cleaning, etc.

### PlayStore Link:
<a href='https://play.google.com/store/apps/details?id=com.bisw.weac&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png'/></a>


Screenshot
--------------
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/1.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/2.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/3.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/4.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/5.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/6.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/7.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/8.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/9.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/10.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/11.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/12.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/13.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/14.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/15.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/16.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/17.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/18.jpeg)
![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/19.jpeg)

Reference item
--------------

* [ZXingLib](https://github.com/xuyisheng/ZXingLib) Reference QR code scanning
* [SimplifyReader](https://github.com/SkillCollege/SimplifyReader)   See browsing local images
* [superCleanMaster](https://github.com/joyoyao/superCleanMaster)  Reference memory cleanup
* [TimerView](https://github.com/pheynix/TimerView)  Refer to custom timer drawing
* [AndroidDaemonService](https://github.com/D-clock/AndroidDaemonService)  Reference gray keep alive

Library created for the weather alarm clock
-------------------------------------------
* [WeatherChartView](https://github.com/kaku2015/WeatherChartView) 

![image](https://github.com/kaku2015/WeatherAlarmClock/blob/master/screenshots/wcv.png)

Open source library
-------------
* [PagerSlidingTabStrip](https://github.com/astuetz/PagerSlidingTabStrip) 
* [leakcanary](https://github.com/square/leakcanary) 
* [Android-PullToRefresh](https://github.com/chrisbanes/Android-PullToRefresh) 
* [Android-AppDaemon](https://github.com/Coolerfall/Android-AppDaemon) 
* [otto](https://github.com/square/otto) 
* [okhttp](https://github.com/square/okhttp) 
* [glide](https://github.com/bumptech/glide) 
* [SmoothProgressBar](https://github.com/castorflex/SmoothProgressBar) 
* [zxing](https://github.com/zxing/zxing) 
* [waveloadingview](https://github.com/tangqi92/WaveLoadingView) 
* [material-dialogs](https://github.com/afollestad/material-dialogs) 
* [SwipeBackLayout](https://github.com/ikew0ng/SwipeBackLayout) 
* [recyclerview-animators](https://github.com/wasabeef/recyclerview-animators) 
* [material-ripple](https://github.com/balysv/material-ripple) 
* [RoundedImageView](https://github.com/vinc3m1/RoundedImageView) 
* [overscroll-decor](https://github.com/EverythingMe/overscroll-decor) 
* [LitePal](https://github.com/LitePalFramework/LitePal)
* [umeng](http://www.umeng.com/)
* [locSDK](http://lbsyun.baidu.com/)


About the weather alarm clock
---------------
This project adopts the traditional MVC architecture mode. It is the first work of the introduction exercise after I contacted Android. Due to the limited knowledge of Android programming and the industry in the initial stage of the project, I did not have the current mainstream architecture and open source library. Such as: MVP, Rxjava, Retrofit, Dagger, etc. applied to this project.

Because the younger brother is too shallow to learn, and is not currently engaged in the Android industry, there must be many shortcomings in the code, but in the attitude of learning and sharing, I hope to get your guidance and help. If you feel that it is not bad, welcome everyone to star喽╭(╯3╰)╮

about me
---------------
I also encountered large and small problems during the development of the weather alarm, but in the end most of the problems were solved. Due to my poor writing and less spare time, many problems are not resolved in a timely manner. I am deeply sorry::__<:: In the future, I will try my best to develop a good habit even if I summarize it! I also hope to help more people.



Follow-up
---------------
I will continue to maintain this project and add some new features and even refactoring in the future.
Next, I will adopt the MVP architecture and use the current mainstream open source libraries: Rxjava, Retrofit2, Dagger2, etc. to develop a brand new Material style app, which is also a worship of the great gods and an advanced for them. I am now in the hands, so stay tuned...

PS
---------------
The main task of the alarm clock is of course the bell on time. The premise of punctual ringing is that the program has not been killed. However, given the current ecosystem of Adroid, it is still limited and difficult to be killed by the system and third-party software. I am also trying my best to solve this problem. I have tried all kinds of methods on the Internet. Most of them have no effect. At present, I have not been able to have a perfect solution for Android5.0 and above. To ensure that you can ring on time, it is recommended to add a weather alarm to your protection list. Of course, if you have any good ideas for the great gods, you will be grateful.


License
---------------
  ```
   Copyright (c) 2018 Biswajit <Biswajitbangalore@gmail.com>
   Copyright (c) 2016 咖枯 <kaku201313@163.com>


   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```





