# Backend-Engineer-Notes
## RESTful API
1. GET:獲得資源
2. POST:新增資源
3. PUT:修改資料(無資料新增)
4. PATCH:修改資料(只修改資料)
5. DELETE:刪除資料
## git 常用
1. git status 確認狀態
2. git init 創一個新版控
3. 'git add 文件名稱' 加入文件
4. 'git commit -m 存檔名稱'
5. git branch 查詢目前線路
6. git log 看存檔資訊
7. git restore 回復檔案
### branch
8. 'git checkout 支線名稱' 切換支線
9. git branch -D 支線名稱 刪除支線
10. git branch -B 支線名稱 創造支線並前往
11. git merge 支線名稱 合併主支線
### Cherry-Pick
先選擇壞節點的前一點  
12. git reset --hard 讀取存檔之前檔案都刪掉  
開始採櫻桃(須按照先後順序)  
13. git cherry-pick commithash
### 救命解藥
14. git reflog 顯示之前操作的每一步
### stash
15. git stash 暫時儲存
16. git stash save '名稱'
17. git stash list 查看目前暫時存檔
18. git stash pop  調出暫時存檔
19. git stash apply 0 將暫存取出並保留
## GitHub
1. git clone 'repo' 抓repo
2. git pull 更新資料

