# 如何使用Google Colab免費算力訓練自己的模型_google colab算力
1.登入GoogleDriverhttps://drive.google.com/drive/my-drive  
2.安裝Colaboratory外掛程式,並新建Colaborator,如下圖  
右鍵我的雲端硬碟—>選擇更多—>選擇關聯更多應用程式—>搜尋Colaborator插件並安裝。  
![image](https://github.com/Black-05/AI_midterm/blob/main/1.jpg)

新建Colaborator

![image](https://github.com/Black-05/AI_midterm/blob/main/2.jpg)
![image](https://github.com/Black-05/AI_midterm/blob/main/3.jpg)

3.連接Google drive  
首先在儲存格中輸入並執行以下命令  

![image](https://github.com/Black-05/AI_midterm/blob/main/4.jpg)
會出現2次校驗,詳細資訊
![image](https://github.com/Black-05/AI_midterm/blob/main/5.png)

會發現上面的程式碼的授權網站無法進入,因為版本過舊
![image](https://github.com/Black-05/AI_midterm/blob/main/6.png)

所以我們用了最新版本的掛載雲端方式,如下圖  
![image](https://github.com/Black-05/AI_midterm/blob/main/7.3.png)  

然後輸入並執行執行以下命令：  
![image](https://github.com/Black-05/AI_midterm/blob/main/7.4.png)    

輸入ls指令，若drive資料夾已列出則說明連線成功  

![image](https://github.com/Black-05/AI_midterm/blob/main/8.1.png)    

4.檢視GPU、CPU狀況  
查看GPU是否在colab中  
![image](https://github.com/Black-05/AI_midterm/blob/main/9.png)  

如果結果為空，則無法使用GPU，如果結果為/device:GPU:0  
使用!/opt/bin/nvidia-smi查看顯存狀況
![image](https://github.com/Black-05/AI_midterm/blob/main/10.png)  

查看顯示卡記憶體使用上限  
![image](https://github.com/Black-05/AI_midterm/blob/main/11.png) 

5.clolab筆記本的使用  

．install  
![image](https://github.com/Black-05/AI_midterm/blob/main/12.png)  

．uninstall   
![image](https://github.com/Black-05/AI_midterm/blob/main/13.png) 

．改變目錄  
![image](https://github.com/Black-05/AI_midterm/blob/main/14.png)  

．git clone  
!git clone https://github.com/wxs/keras-mnist-tutorial.git  

![image](https://github.com/Black-05/AI_midterm/blob/main/15.png)  

．下載數據  
!wget https://raw.githubusercontent.com/vincentarelbundock/Rdatasets/master/csv/datasets/Titanic.csv -P drive/app  

![image](https://github.com/Black-05/AI_midterm/blob/main/16.png)    

．查看記憶體資訊  
!cat /proc/meminfo  

![image](https://github.com/Black-05/AI_midterm/blob/main/17.png)   

．查看CPU資訊  
!cat /proc/cpuinfo  

![image](https://github.com/Black-05/AI_midterm/blob/main/18.1.png)   

6.訓練自己的模型
-未完待續


