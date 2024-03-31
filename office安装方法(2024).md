# office安装方法(2024).md

### 1.官网下载 Office Deployment Tool   
[https://www.microsoft.com/en-us/downl...](https://www.microsoft.com/en-us/download/details.aspx?id=49117)

### 2.配置config文件
[https://config.office.com/deploymentsetting](https://config.office.com/deploymentsettings)  

导出 xml  

### 3.安装

cd c:\office（文件夹目录）  
setup.exe /download config.xml  
setup.exe /configure config.xml  

### 4.激活
cd C:\Program Files(x86)\Microsoft Office\Office16   
或者 cd C:\Program Files\Microsoft Office\Office16  

cscript ospp.vbs /sethst:kms.03k.org   
cscript ospp.vbs /act  

### 5.备选的KMS  
kms.03k.org  
kms.chinancce.com  
kms.luody.info  
kms.lotro.cc  
kms.luochenzhimu.com  
kms8.MSGuides.com  
kms9.MSGuides.com  

### 查看Youtube视频
https://www.youtube.com/watch?v=Kl1j2GjhaRA  
