# pywifi

原作: https://github.com/awkman/pywifi

## 建置 Docker 環境
需求: docker

構建 Docker 環境
```
./buold-env.sh
```

## 建置 Apt Package
構建 deb 檔案
```
./build-deb.sh
```

能在 `dist` 資料夾中找到輸出檔
```
├── dist
│   ├── deb_dist
│   ├── python3-pywifi_1.1.12-1_all.deb <--- 目標檔案
│   ├── pywifi-1.1.12
│   ├── pywifi_1.1.12-1.debian.tar.xz
│   ├── pywifi_1.1.12-1.dsc
│   ├── pywifi_1.1.12-1_arm64.buildinfo
│   ├── pywifi_1.1.12-1_arm64.changes
│   ├── pywifi_1.1.12-1_source.buildinfo
│   ├── pywifi_1.1.12-1_source.changes
│   └── pywifi_1.1.12.orig.tar.gz
```
