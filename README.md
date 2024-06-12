# ANPR

Bước 1: Tạo môi trường: 
-   python -m venv venv 
-   Python3 -m venv venv

Bước 2: Cài các thư viên cần thiết
-   Cái các thư viện trong file setup.txt: pip install -r setup.txt
-   Các các thư viện đặc biệt: 
    -   Gỡ các thư viện bị lỗi: pip uninstall torch torchvision
    -   Cài đặt các thư viện đặc biệt: pip install torch==2.2.2+cpu torchaudio==2.2.2+cpu torchvision==0.17.2+cpu torchmetrics==0.10.3 -f https://download.pytorch.org/whl/torch_stable.html

Bước 3: Chạy file main: python source_code\main.py