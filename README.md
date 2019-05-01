New-Labelme
===


labelme版本：3.14.1

<br>

版本：1.3

1.更新mask儲存方式(相同label存一張)

(下版本更新不同label相同顏色問題)

<br>

程式說明：

此程式可直接將label後的json檔轉為dataset，並將多個mask分成不同圖片儲存。

<br>

安裝步驟：

1.請先安裝Anaconda並建立環境

2.進入環境後安裝labelme(需為指定版本)
> pip install labelme==3.14.1

3.進入``.\Anaconda\envs\LabelEnv\Lib\site-packages``內，覆蓋原有labelme檔案(LabelEnv為環境名稱)