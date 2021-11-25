
# README
把 pack 檔案加入 commit 推上來之後再打上 tag 就會自動執行 action  
## example
```
git tag v350
git push origin v350
```
版本號以後面數字為準  


## 拆包特定檔案
```
mabi-pack extract -i 341_to_342.pack -o ./342 --filter "race.xml"
```
