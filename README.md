
# Giới thiệu

Code Java thực hiện mã hóa và giải mã (phá khóa) theo hệ mã RSA.

# Web Demo
[https://ruanshiron.github.io/rsa-demo/](https://ruanshiron.github.io/rsa-demo/)

# Tạo khóa

1. Chọn hai số nguyên tố p và q sao cho p ≠ q
2. Tính n = p * q
3. Tính giá trị hàm Euler m = Φ(n) = (p-1) * (q-1)
4. Chọn public key e sao cho 1 < e < m và ƯCLN (e, m) = 1
5. Tính private key d sao cho d * e mod m = 1

# Files

## 1. RSA.java
Bản hoàn thiện: Thực hiện mã hóa và giải mã với mọi độ to nhỏ của n và public key e.

## 2. Draft.java
Bản chưa hoàn thiện: Chỉ mã hóa và giải mã các ký tự alphabet tiếng Anh 'a' ~ 'z'.

## 3. Presentation.pptx
Slide Power Point thuyết trình.

## 4. PublicKeyCryptography.pdf
Slide PDF kiến thức lý thuyết về hệ mã công khai nói chung và hệ mã RSA nói riêng.