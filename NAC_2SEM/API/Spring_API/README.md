# API para NAC de android FIAP 

> #### API utilizada como fonte de dados poara aplicativo Android construida em Spring conectada a um banco SQL Server hospedado na AWS
<br>

### Como Executar:
---

1. Clone esse repositorio , navegar até a pasta e buildar a imagem com o seguinte comando <br>
```docker build -t  api/android .```
2. Buildada a imagem, será necessario criar o container que executará a aplicação com o seguinte comando <br>
```docker run -d -p  8081:8081 api/android .```
3. Feito isso nossa aplicação estara rodando na porta 8081, e podemos acessar ela com a url: <br>
```localhost:8081/api/v1/techs```