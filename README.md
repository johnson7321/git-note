# git-note
mkdir hello-world
cd hello-world/
git init
vi README.md
git add README.md
git commit
git diff
git commit -a
git lg
1. `mkdir hello-world`：這個指令創建一個名為 "hello-world" 的新目錄（資料夾）。

2. `cd hello-world/`：這個指令將你的當前工作目錄更改為剛剛創建的 "hello-world" 目錄。

3. `git init`：這個指令初始化了一個新的 Git 儲存庫，將 "hello-world" 目錄轉換為一個 Git 儲存庫，從而可以進行版本控制。

4. `vi README.md`：這個指令使用 Vi 或 Vim 文本編輯器創建或打開了一個叫做 "README.md" 的檔案，通常用於編輯文件。

5. `git add README.md`：這個指令將 "README.md" 檔案添加到 Git 的暫存區，表示你準備將這個檔案的更改提交到儲存庫中。

6. `git commit`：這個指令將暫存區中的更改提交到 Git 儲存庫中。通常需要在此步驟中提供一個提交訊息，以描述這個提交所做的更改。

7. `git diff`：這個指令顯示當前工作目錄中的檔案與上一個提交版本之間的差異。

8. `git commit -a`：這個指令將當前工作目錄中所有已經被 Git 追蹤（tracked）的檔案的更改添加到暫存區，並提交到儲存庫中。

9. `git lg`：這個指令可能是一個自訂的 Git 別名，用於顯示提交歷史。通常 `git log` 用於查看提交歷史。
