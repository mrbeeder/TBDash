<div align="center">
<h2> TBDash - Client dành cho Pterodactyl.</h2>
<img src="https://img.shields.io/badge/Version-1.0-0040ff.svg"></img>
<img src="https://img.shields.io/badge/Codename-novaya_veshsh-0000aa.svg"></img>
</div>

# Cập nhật lớn: v1.0 (novaya veshsh)
> Làm mới toàn bộ hệ thống!

# Nhật ký thay đổi: v1.0.1
- Thêm Cloudflare Turnstile để chống bot  
- Điều chỉnh nhỏ giao diện UI  

# Tính năng chính
* Quản lý server Pterodactyl  
* Treo AFK để nhận coin  
* Trang quản trị (Admin)  
* Dễ sử dụng  
* Tùy chỉnh client với màu sắc yêu thích  

# Yêu cầu
- Python 3.10 trở lên  
- Các thư viện có trong file `requirements.txt`  

# Cài đặt
<details>

<summary>Cấu hình Nginx</summary>

## Nếu bạn sử dụng nginx làm web server, hãy thực hiện bước này trước khi cài đặt chính:

- Tạo file cấu hình nginx:
```bash
sudo touch /etc/nginx/sites-available/<ten_file>.conf
