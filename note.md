# Terems // danh tu

Repository (Repo) : hiện tại thư mục dự án của chúng ta mang tên GITHUB.VN  là 1 Repository

Brand (cành ,  nhánh) : 1 dự án có nhiều cành khác nhau và cành mặc định của chúng là ' master '

Conflict (Xung đột) 

local (địa phương) : những dữ liệu nằm trên máy tính của chúng ta

remote : những dữ liệu nằm trên 1 sever khác

# Commands // lenh

- git init : lệnh này làm Repository của chúng ta trở thành 1 " git Repository "

- git status : lệnh này cho chúng ta thấy dự án của mình tất cả thay đổi gì ta sẽ thấy được

- git add : cho phép chúng ta chuẩn bị lưu giữ lại thời điểm hiện tại của dự án " chúng ta có thể đánh 'git add ten_file'
'git add .' để lưu tất cả file

- git reset : lấy ra file chuẩn bị lưu

- git commit -m {note} : chính thức lưu

- git log : coi những thời điểm chúng ta đã lưu

- git log --oneline : giống git log nhưng nhìn gọn hơn 

- git checkout {name branch} : trở lại branch

- git check out id_commit : trở lại thời điểm ban đầu

- git branch : thấy được cành hiện tại

- git checkout -b {name branch} : để tạo ra 1 branch mới 

- git merge {name branch} : tổng hợp các branch với nhau

- git branch -d {name branch} : xóa đi branch

- git push {repo url} {name branch}: đẩy local repo lên remote repo

- git remote add origin {repo url} : liên kết remote repository với local repository

- git clone {repo url} : tải thư mục trên github về

- git push -u origin {name branch} : đẩy branch lên github

- git fetch origin 
- git checkout -b {name branch} origin/{name branch} : lấy branch từ remote về local

- git pull : lấy thay đổi master merger branch trên github về local

