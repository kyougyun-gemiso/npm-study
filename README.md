
# Nginx Proxy Manager 구성

Nginx Proxy Manager는 여러 개의 Nginx 인스턴스를 관리하고 프록시 설정을 쉽게 할 수 있도록 도와줍니다. 이 예제에서는 nginx1, nginx2, nginx3의 구성을 설명합니다.

## 구성도

```
npm
├── nginx1 (http://localhost/, http://localhost/nginx1/)
├── nginx2 (http://localhost/nginx2/)
└── nginx3 (http://localhost/nginx3/)
```

## Nginx 인스턴스 설정

각 Nginx 인스턴스는 다음과 같이 설정됩니다:

### nginx1

- URL: http://localhost
- URL: http://localhost/nginx1

### nginx2

- URL: http://localhost/nginx2

### nginx3

- URL: http://localhost/nginx3

각 인스턴스는 독립적으로 동작하며, Nginx Proxy Manager를 통해 쉽게 관리할 수 있습니다.
