# Java Hello World: Frontend ve Backend

Bu proje Docker ve AWS kullanmadan yerelde çalışacak basit bir örnektir.

## Klasörler

- `frontend/`: Tarayıcıda açılan tek sayfa
- `backend/`: Java 19 + Spring Boot REST API

## Backend'i çalıştırın

Java 19 ve Maven kurulu olmalıdır.

```bash
cd backend
mvn spring-boot:run
```

Kontrol için: `http://localhost:8080/api/hello`

## Frontend'i açın

`frontend/index.html` dosyasını tarayıcıda açın. Sayfa backend'e istek atar ve **Hello World!** mesajını gösterir.
## API Endpointleri

Backend çalışırken aşağıdaki adresler kullanılabilir:

- `GET /api/hello` — Hello World mesajını döndürür.
- `GET /api/health` — Uygulamanın çalıştığını kontrol eder.

Örnek:

```text
http://localhost:8080/api/health