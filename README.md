# APIs

Repositório de APIs.

# Executando a solução

Para executar a solução é preciso ter o Docker instaldo na máquina e seguir os seguintes passos:

    1. Navegue até a pasta que contém o arquivo docker-compose.yml
	2. Execute o comando "docker-compose up -d".
	3. Execute o comando "docker container ps -a" para verificar os containers em execução.
	    1. Verifique se os containers apis_jurosapione_1 e  apis_jurosapitwo_1 estão rodando.
	4. Teste as APIs por uma API Client (Postman, ...)
	    1.Teste a API1 a partir da URI: [http://localhost:8080/api/juros/taxajuros](http://localhost:8080/api/juros/taxajuros)
	    2.Teste a API2 a partir da URI: [http://localhost:8084/api/juros/calculajuros?valorInicial=50&meses=3](http://localhost:8084/api/juros/calculajuros?valorInicial=50&meses=3)
		