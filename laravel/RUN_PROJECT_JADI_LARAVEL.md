# NGEJALANIN PROJECT JADI LARAVEL (DAPET DI GITHUB/LAINNYA)

## 1. [RUN] COPY FILE ENV
```bash
cp .env.example .env
```
## 2. [RUN] INSTALL VENDOR MODULE PAKE COMPOSER
```
composer install
```
## 3. [RUN] GENERATE KEY DI ENV
```
php artisan key:generate
```
## 4. [BIKIN DATABASE](https://github.com/urisuzy/tutorial/blob/main/database/BIKIN_DATABASE.md) & [MASUKIN KE ENV / KONEKIN KE LARAVEL](https://github.com/urisuzy/tutorial/blob/main/laravel/database/KONEK_LARAVEL_KE_DATABASE.md)

## 5. [RUN] MIGRATE DATABASE

```
php artisan migrate:refresh
```
## 6. [RUN] STORAGE LINK

```
php artisan storage:link
```
## 7. [RUN] CLEAR CACHE

```
php artisan optimize:clear
```
## 8. [RUN] SERVE RUN LARAVEL

```
php artisan serve
```
## 9. BUKA LINK PROJECT
```
http://localhost:8000
```
## 10. SELESAI