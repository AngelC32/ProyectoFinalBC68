# ProyectoFinalBC68
Proyecto Final Para el Bootcamp 68

## Repositorios:
- Repositorio para archivos yaml de configuracion: https://github.com/AngelC32/banking-config-repo
- Config Server: https://github.com/AngelC32/config-server
- Discovery Server(Eureka): https://github.com/AngelC32/discovery-server
- Microservicio Para Gateway: https://github.com/AngelC32/gateway-msvc
- Repositorio del microservicio de clientes: https://github.com/AngelC32/customers-msvc
- Repositorio del microservicio de cuentas bancarias: https://github.com/AngelC32/accounts-msvc
- Repositorio del microservicio de transacciones bancarias: https://github.com/AngelC32/transactions-msvc

## Pasos:
1. Clonar los repositorios en alguna carpeta
2. Ejecutar los archivos docker compose desde la carpeta raiz donde están clonados los proyectos:
   - docker compose -f docker-compose.infra.yaml up --build -d
   - docker compose -f docker-compose.msvc.yaml up --build -d
