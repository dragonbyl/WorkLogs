1. google-chrome不能以root用户运行的解决方法
  打开/usr/share/applications/google-chrome.desktop文件, Exec那句加上--user-data-dir, 或者右键属性/应用程序 加上--user-data-dir.