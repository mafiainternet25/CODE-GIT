🚀 1. Khởi tạo & kết nối repo
rm -rf .git # xóa hoàn toàn git
git init # tạo repo git
git remote add origin <url> # nối với GitHub
git clone <url> # clone repo về máy

📦 2. Commit code (dùng mỗi ngày)
git status # xem thay đổi
git add . # add toàn bộ file
git add <file> # add file cụ thể
git commit -m "message" # commit

☁️ 3. Push / Pull (làm việc với GitHub)
git push # đẩy code lên
git push -u origin main # push lần đầu + set upstream
git pull # kéo code mới về

🌿 4. Branch (cực quan trọng)
git branch # xem branch
git branch <name> # tạo branch
git checkout <name> # chuyển branch
git checkout -b <name> # tạo + chuyển luôn
git branch -M main # đổi tên branch

🔄 5. Đồng bộ code (hay gặp lỗi)
git pull origin main # kéo code về
git pull --rebase # pull sạch hơn (pro)

💣 6. Fix lỗi & undo (cực hữu ích)
🔙 Quay lại commit cũ
git log --oneline
git reset --hard <commit>

    ❌ Huỷ file đã add
        git restore --staged <file>

    🧹 Xoá file khỏi git (giữ trên máy)
        git rm --cached <file>

    💥 Push đè (danger nhưng hay dùng)
        git push -f origin main

🧪 7. Debug & kiểm tra
git log --oneline # xem lịch sử commit
git diff # xem thay đổi
git reflog # cứu dữ liệu (rất mạnh)
