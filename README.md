### Môn: Phát triển ứng dụng với mã nguồn mở-TEE0421
# Nguyễn Phương Nam
# Lớp: 58KTPM
# Bài tập 02: SỬ DỤNG DJANGO ĐỂ TẠO WEB QUẢN LÝ TIỆM CẦM ĐỒ
Deadline : 23h59 ngày 09 tháng 5 năm 2026.
Ngày làm: 09/05/2026

1. TỔ CHỨC CSDL CHO HỆ THỐNG QUẢN LÝ TIỆM CẦM ĐỒ
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/b2ebfae2-6d0f-4998-a1bb-e79bd1e6b0d3" />

2. SỬ DỤNG DOCKER TRÊN UBUNTU ĐỂ:
Tạo thư mục chứa dự án:
<img width="597" height="37" alt="image" src="https://github.com/user-attachments/assets/ca08edfd-485e-4859-a719-a89d7cb26101" />
Thêm các dịch vụ vào trong file docker-compose.yml ( sử dụng sudo nano docker-compose.yml):
a. Mariadb : chứa csdl của hệ thống này
b. Phpmyadmin: để soi được csdl
<img width="748" height="622" alt="image" src="https://github.com/user-attachments/assets/6fd2947a-64ac-4cca-a176-2604ce256438" />
3.Django: build 1 docker container (dùng Dockerfile): trên nền python, sử dụng django, nhớ mount thư mục để dễ edit, edit dùng: sudo nano ten_file - Tạo 1 thư mục riêng cho Django:
<img width="621" height="28" alt="image" src="https://github.com/user-attachments/assets/476a6cae-ce72-454d-80d3-fd1794600a9c" />
<img width="1915" height="1012" alt="image" src="https://github.com/user-attachments/assets/2cb2dd6f-5add-4d46-97fd-20ba93042fec" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5ae244e6-2d94-4d7d-a3da-1daa79e6828e" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b0f1daa7-fee6-4d11-b801-76b051e17137" />
<img width="962" height="1019" alt="image" src="https://github.com/user-attachments/assets/75faf21e-8dc3-4a63-8cdc-18b620fd6433" />
<img width="950" height="1012" alt="image" src="https://github.com/user-attachments/assets/60b47a17-383a-46a3-81b5-1d41eeee2a53" />

 Sử dụng cloudflare tunnel để public kết quả lên 1 sub-domain:
<img width="1920" height="1013" alt="image" src="https://github.com/user-attachments/assets/15ecf47a-dc9a-4fcf-b088-5a1176dd4ea0" />
