# Curso-Spring-Rest
		AULA 01
		
REST -> Formaliza um conjunto de Constraits (Regras)

Por que usar REST API?
	Separação entre cliente e servidor
	Escalabilidade
	É independente de linguagem de programação
	Demanda de mercado -> REST ajuda muito na integração, pois usam o mesmo modelo estrutural

REGRAS:
	CLIENTE-SERVIDOR: Podem evoluir separadamente
	STATELESS: Aplicação sem estado. Protocolo HTTP, a requisição deve conter tudo que precisa para ser processado
	CACHE: Fazer cache das requisões. Guardar sempre as informações quando repetidas vezes - Memória de consulta rápida. Diminui a quantidade de consulta no servidor
	INTERFACE UNIFORME: Simplifica e desacopla arquitetura. 
	SITEMAS EM CAMADAS: Entre o cliente que hospeda e o que fornece API,pode existir além dessas
	CÓDIGO SOB DEMANDA

MODELO ESTRUTRAL HEST, INDEPENDENTE DE PROTOCOLOS, MAS O MAIS COMUM É O HTTP

HTTP -> REQUISIÇÃO -> RESPOSTA (Faz entender o cliente e servidor)

	ELEMENTOS PARA FORMAR UMA REQUISIÇÃO PRECISAMOS DE:
		[MÉTODO] [URI] [HTTP/VERSAO DO PROTOCOLO] [CABEÇALHOS] [CORPO/PAYLOAD]	
		EX: post/produtos HTTP/1.1 
		CABEÇALHO CONTENT-TYPE:Para o servidor saber como interpretar o corpo da requisição.
		CABEÇALHO ACCEPT: Para aceitar só um tipo de formato.

	COMPOSIÇÃO DA RESPOSTA:
		[HTTP/VERSAO DO PROTOCOLO] [STATUS] [CABEÇALHOS] [CORPO/PAYLOAD]

RECURSOS REST:

	Qualquer coisa exposta na internet. É como se fosse uma instância de uma classe

	URI:
		Identificador de recursos. Usa URI para dar endereços para os recursos de forma não ambigua.
		Referência a identificação de um recurso
		Deve se referir a uma coisa, a um substantivo, não à verbos.
		Usar nomes no plural
		
	URI X URL: 
		URL é um tipo de URI, mas ela especifica não apenas o recurso, mas também a localização dele, através do protocolo HTTP.
		Referência a identificação de um recurso.

SPRING REST O QUE É?

	Apenas um termo. Spring é um conjunto de projetos que resolvem problemas no dia a dia. Ajuda a criar aplicações com facilidades.
	Spring é modular, open source, tem uma grande comunidade, popularidade.	
	Site: spring.io -> 38 min
	


			
		


 	
	
