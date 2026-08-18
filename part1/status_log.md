On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	./

nothing added to commit but untracked files present (use "git add" to track)
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   notes.txt
	new file:   todo.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	draft.md
	status_log.md

diff --git a/part1/notes.txt b/part1/notes.txt
index e69de29..eba2fe0 100644
--- a/part1/notes.txt
+++ b/part1/notes.txt
@@ -0,0 +1,3 @@
+Dong1
+Dong2
+Dong3

git commit -a chỉ stage và commit những file đã đc track khi có sự thay đổi, còn với những file ch từng được track thì khi có sự thay đổi sẽ không thể dùng git commit -a mà phải dùng git add xong mới git commit được
fetch chỉ lấy thông tin trên web về máy, còn pull thì vừa lấy thông tin vừa đè lên file trên máy
