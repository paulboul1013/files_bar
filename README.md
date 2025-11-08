# files_bar

## 介紹
計算檔案數目，模擬動畫進度條

## 控制變量
顯示進度字符  
```c
local bar_char='#'
```
顯示未完成進度字符
```c
local empty_char='.' 
```
找尋目標檔案，這裡範例是找跟cache名子有關的檔案
```c
files=(./**/*cache)
```
控制顯示速度
```c
batchsize=5
```
