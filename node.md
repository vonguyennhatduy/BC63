# git checkout <tên file> đưa file về trạng thái ban đầu 
# git checkout . => đưa tất cả các file về trạng thái ban đầu 


# xem lịch sử commit
git log
git log --oneline
=> để exit thì nhấn phím Q

# branch
liệt kê branch đang có 

git branch <tên branch> => tạo 1 cái branch mới 
nhấm phím Q thể thoát ra 

git switch <tên branch> => chuyển qua branch <tên branch>

git checkout -b <tên branch> => tạo ra một branch mới và nhảy qua branch vừa mới tạo (= git branch + git switch)

git branch -m <tên branch mới> => đổi tên branch 

git branch -D <tên branch> => xóa branch (chỉ xóa khi đang ở branch khác)

git pull origin main => lấy code mới nhất về 



