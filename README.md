## Docker
### Utilização prática no cenário de Microsserviços

> Denilson Bonatti, Instrutor - Digital Innovation One

Muito se tem falado de containers e consequentemente do Docker no ambiente de desenvolvimento. Mas qual a real função de um container no cenários de microsserviços? Qual a real função e quais exemplos práticos podem ser aplicados no dia a dia? Essas são algumas das questões que serão abordadas de forma prática pelo Expert Instructor Denilson Bonatti nesta Live Coding. IMPORTANTE: Agora nossas Live Codings acontecerão no canal oficial da dio._ no YouTube. Então, já corre lá e ative o lembrete! Pré-requisitos: Conhecimentos básicos em Linux, Docker e AWS.

### Estrutura do projeto

```
.
├── config
│   ├── mariadb
│   │   └── banco.sql
│   ├── nginx
│   │   ├── Dockerfile
│   │   └── nginx.conf
│   └── php
│       └── Dockerfile
├── docker-compose.yaml
├── README.md
└── src
    └── index.php
```

### Executando o projeto

1) Confirme se o docker e docker-compose estão instalados no seu ambiente
2) Execute o comando:
    ```
    docker compose up -d
    ```
3) Abra o navegador e acesse o endereço: http://localhost:8080
