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
3. git push 推送資料
4. git push -u origin '分支名稱'
5. git revert commitHash 修正錯誤
6. git rebase -i HEAD~3 融合commit
7. git branch -r 查看GitHub上分支
8. git pull origin main 更新支線main進度
### Merge Conflict 合併衝突  
9. git config pull.rebase false
並在執行一次 git pull 進行選擇變更
# OOP 四大原則
## 封裝（Encapsulation）  
將數據和操作數據的方法綁定在一起，並限制外部對數據的直接訪問。這樣可以保護內部狀態不被外部隨意修改，並且只通過指定的接口（如方法）進行交互。
## 繼承（Inheritance）
允許一個類從另一個類獲得屬性和方法的能力。通過繼承，子類可以復用父類的代碼，並且可以根據需要對其進行擴展或修改，實現代碼的重用和結構的清晰。
## 多態（Polymorphism）
允許對象通過相同的接口表現出不同的行為。這意味著一個接口可以有多種不同的實現，根據對象的實際類型來執行相應的操作。多態可以通過方法重寫（Override）或接口實現。
## 抽象（Abstraction）
將複雜的系統細節隱藏起來，僅保留必要的、對外有意義的屬性和方法。抽象可以幫助開發者專注於更高層次的設計，並提高系統的靈活性和可擴展性。

# CI/CD Docker
### CI 持續整合 continuous Integration
### CD 持續交付/部屬 continuous Delivery/Deployment
## jenkins






