# Tourism-Route-Planning

Plan Your Best Route To Travel Over China's Most Popular Tourist Attractions!
==============

* This project aims at planning a good route for who wants to travel over China.

Information
--------------

* We choose 12 most popular tourist attractions of China: Beijing (1), Pingyao (2), Xi'an (3), Chengdu (4), Huangshan (5), Suzhou (6), Shanghai (7), Hangzhou (10), Zhangjiajie (9), Chongqing (8), Guilin (11), Hong Kong (12).
* The tour begins in Beijing and ends in Hong Kong.
  * ![Destinations](https://images.chinahighlights.com/allpicture/2017/10/75a83cba186649d5a73d341e.jpg)
* Information of time-spending and prices of airplanes and trains:
  * [Ctrip](http://www.ctrip.com/)

What To Optimize
--------------

* The route which spend the least time on passage.
* The route which spend the least money on passage.

Method
---------------

* Matlab linear programming. Notice this is an integer programming problem.
* Algorithm: 
  * Shortest path.
  * Max flow.

Data Visualization:
---------------

* The diagrams of traffic network.
  ![Aviation Network](http://oz5h8pmj2.bkt.clouddn.com/Aviation.png)
  ![Railway Network](http://oz5h8pmj2.bkt.clouddn.com/Railway.png)
* The diagrams of optimization results.
  ![The Least Time Route](http://oz5h8pmj2.bkt.clouddn.com/LeastTime.png)
  ![The Least Money Route](http://oz5h8pmj2.bkt.clouddn.com/LeastMoney.png)
* Note that red arrows represent the aviation and blue arrows represent the railway in the result diagrams. 

Result
----------------

* The least time on passage: 29.03 hours.
* The least money on passage: ¥2555.

Acknowledgement
----------------

I want to express thanks to:
  * My group members: James GUAN & Blues FU
  * My instructor: Prof. Hong Mingyi
