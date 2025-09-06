
# Terms

Repository (Repo)
Branch
Confict
Local
Remote
# Commands

-git init
-git status
-git add : Chuẩn bị lưu lại thời điểm hiện tại của dư án
-git reset : Lấy ra file chuẩn bị lưu ( Có nghĩa là không lưu file nữa)
-git commit : Lưu 
-git log : Xem lại thời điểm lưu 
-git log --oneline : Gọn hơn git log
-git checkout : Trở lại thời điểm ban đầu cùng với id của commit
-git checkout + (branch name) : Quay trở lại thời điểm hiện tại của dự án
-git branch : nhánh của dự án
-git checkout -b + (branch name): Tạo thêm branch (nhánh)
-git merge : Tổng hợp lại tất cả branch
-git branch -d + (branch name) : Xóa 1 branch
-git push : Đẩy từ Local Repo => Remote Repo
-Nếu có local repo => muốn đẩy lên github:
git remote add origin + link http github web : Tạo alias (link http web => origin).
-Nếu có remote repo (github) => clone về local:
không cần setup alias => git push (Tự động đẩy dự án lên github)

# Case 1 
-Trường hợp tạo 1 branch ở local => đẩy local branch lên remote repo (github)
dung : git push -u origin dev1 (Chỉ cần dùng lần đầu push branch) => Từ lần tiếp theo chỉ git push

# Case 2
-Trường hợp nếu remote repo (github) có sẵn branch => lấy về local repo
dùng : 
- step 1 :git fetch origin 
- step 2 : git checkout -b (remote repo branch) origin/(remote repo branch)

# Case 3
-Trường hợp muốn merge hoặc kết hợp các branch khác với master
Dùng : Pull Request trên GITHUB

# Case 4 : Git Ignore
-Nếu không muốn Git theo dõi 1 file nào đó \

# Terminal OS
Step1 : cd E:\Cloud\git-flow
Step2 : git clone https://github.com/quanghuy2307qn/git-flow.git
Step3 : ls
Step4 : cd git-flow
Step5 : code .