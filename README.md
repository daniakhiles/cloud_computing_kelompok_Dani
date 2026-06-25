# Deploy WordPress dengan Docker (Cloud Computing Project)

## Kelompok Dani
- Dani Akhiles
- Fimantus Rainer Agung
- Etwaridus Nggera Hibur

---

## Deskripsi Project
Project ini merupakan implementasi sistem WordPress berbasis Docker Compose dengan arsitektur cloud sederhana yang terdiri dari beberapa layer:

- Application Layer: WordPress
- Database Layer: MariaDB
- Caching Layer: Redis
- Object Storage Layer: MinIO

---

## Teknologi yang Digunakan
- Docker
- Docker Compose
- WordPress
- MariaDB
- Redis
- MinIO

---

## Arsitektur Sistem

### Network
- frontend-net → akses WordPress
- backend-net → komunikasi antar service

### Layer System
- App Layer → WordPress
- Database Layer → MariaDB
- Cache Layer → Redis
- Storage Layer → MinIO

---