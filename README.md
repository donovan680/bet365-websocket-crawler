  
    
# English version:

### 一、Introduction：
Monitor bet365 in-play football matches scores.

### 二、Getting Started：
require PyExecJS,requests,autobahn,twisted. 
  
  
&nbsp;&nbsp;pip install PyExecJS  

&nbsp;&nbsp;pip install requests  

&nbsp;&nbsp;pip install autobahn  

&nbsp;&nbsp;pip install twisted
  
  
Run bet365_websocket_spider.py and see output logs.

### 三、Note：
If it can't get data after running, try using the following API.

1. Get all live football matches, url: http://106.52.68.20/b365/soccer/test/allEv?lang=en
2. Get odds of all matches for goal line, url： http://106.52.68.20/b365/soccer/test/oneHd2allEv/C1-G15?lang=en
    
