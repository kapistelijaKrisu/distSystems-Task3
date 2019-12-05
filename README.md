# Report #

### 1 ###
Time ticks in time display and chrono mode, not in que to edit mode.
### 2 ###
When top right is clicked light is turned on. When top right is released it enters countdown mode to turn off the light. (thus spamming light button does not keep light on, only holding). After 2sec passes in countdown the light is turned off.
### 3 ###
Clicking top left toggles between chrono and time display. The time still moves in chrono mode but flickers because both are drawn.
### 4 ###
Partially complete. In chrono it shows time as hh:mm:ss and moves once per sec
### 5 ###
Enters a countdown of 1.5 sec. When complete enters time edit mode. Time does not move while in que. Early release exits countdown.
### 6 ###
Not done due to the fact that graph of states already looks quite messy with 9 states and all transactions.
### 7 ###
When in time edit mode time does not tick. Holding lower left increases time by 1sec every 0.3sec. Not pressing bottom right or bottom left (not all buttons work as refresh to countdown) for 5sec or holding bottom right again for 2sec exits the time edit mode.
### No concurrency ###
Due to the fact we did no go through how to write SVM or the fact that starting point chart does not work. we decided to avoid concurrency to avoid other problems after tryharding for a while. 

### State chart ###



![Chart of states and their transitions](/chart.png)
