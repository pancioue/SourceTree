> SourceTree Is an Atlassian product

安裝
--------
一開始會出現log in Atlassian account 及連結到Atlassian account。  
由於公司使用Bitbucket，在此選擇Bitbucket Cloud。  
這裡的步驟可以直接略過，應該也就只是帳號綁定的差別；進去SourceTree都可以再新增或移除帳號，如圖示。
* Bitbucket Server可能是有架Bitbucket server才選，基本上選了也會失敗
* Bitbucket也是Atlassian的產品，git cloud 平台，類似github。

![sourcetree-account](https://user-images.githubusercontent.com/24542187/185780587-fcdb972c-c76f-439e-a03f-74dc559ce70a.png)


Connet to Bitbucket
--------
Bitbucket帳號就是Atlassian帳號，要從bitbucket垃東西時會要求輸入密碼，  
但由於一開始申請Atlassian使用的是google login，並沒有密碼，所以只能選擇ssh方式。  
在Windows環境設定ssh key時，注意有Putty/plink跟OpenSSH兩個選項，  
若使用cmd自帶的ssh-keygen，記得選擇OpenSSH。
