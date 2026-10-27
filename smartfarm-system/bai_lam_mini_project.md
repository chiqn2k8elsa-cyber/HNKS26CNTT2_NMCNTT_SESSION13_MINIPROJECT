# BÀI LÀM – MINIPROJECT

- **Họ tên: Nguyễn Quỳnh Chi** 
- **Lớp:CNTT2** 
- **Link repository: https://github.com/chiqn2k8elsa-cyber/HNKS26CNTT2_NMCNTT_SESSION13_MINIPROJECT**
- **Hệ điều hành (Windows/macOS):Windows** 

## Chức năng 1

### Các lệnh đã chạy

```shell
#### mkdir smartfarm-system/docs, smartfarm-system/scripts, smartfarm-system/data, smartfarm-system/backup
#### cd smartfarm-system
#### cd data
#### ni ../.evn
#### "DB_PASSWORD=demo_123456" > ..\.evn
```

## Chức năng 2

### Lệnh đã chạy

```shell
#### cd..
#### ni scripts\auto_report.ps1
#### Cd scripts
#### -ExecutionPolicy Bypass -File
#### .\auto_report.ps1
#### cd ..
#### ni backup/bao-cao-su-co.txt
#### "=== BAO CAO SU CO ===" > backup/bao-cao-su-co.txt
#### "Ngay gio lay bang: 27/10/2026 8:45" >> backup/bao-cao-su-co.txt
#### get-content data\log-he-thong.log | select-string “ERROR” >> backup/bao-cao-su-co.txt
#### "TONG SO SU CO:" >> backup/bao-cao-su-co.txt
#### get-content data\log-he-thong.log | select-string “ERROR” |Measure-Object >> backup/bao-cao-su-co.txt
```

## Chức năng 3

### Lệnh đã chạy
```
#### =TRIM($B$2:$B$11)
#### =VLOOKUP(E2,'danh-muc-linh-kien'!$A$1:$B$7,2,FALSE)
#### Bôi đen toàn bộ bảng -> chọn "Data" -> chọn "Filter"
```

## Chức năng 4: tài liệu  README.md 