## 1 Cài đặt Rust vào máy tính cá nhân (MAC OS)

Hệ điều hành MacOS

1. Cài đặt curl hoặc brew 

2. Mở Terminal , update Homebrew

```bash 
brew update
```
3. Cài đặt thư viện OpenSSL
```bash 
brew install openssl
```
4. Tải rustup (Sửa lại do máy dùng zsh)
```bash
sudo curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- --no-modify-path
```

5. Chọn cài đặt mặc định
Thêm câu lệnh cargo vào shell
```bash
source ~/.cargo/env
```

6. Kiểm tra Rust sau khi cài đặt
```bash
rustc --version
```
~rustc 1.81.0 (eeb90cda1 2024-09-04)~