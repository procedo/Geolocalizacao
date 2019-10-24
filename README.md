# Geolocalização

Projeto contendo a lógica da API de geolocalização do GoogleMaps

## Preparando instalação

No arquivo `composer.json` adicione:

```
{
	...,
	"repositories": [
		{
			"type": "vcs",
			"url": "https://gitlab.com/procedo/geolocalizacao.git"
		}
	],
}
```

## Removendo bibloteca antiga
Se o projeto já possuir uma versão da geolocalização, remover usando o comando: 

```
$ dex composer remove cmparrela/geolocalizacao
```

## Instalando

Para instalar a nova versão da biblioteca é necessário executar o comando abaixo:

```
$ dex composer require procedo/geolocalizacao:"dev-master"
```

Será solicitado o acesso do usuário no GitLab, o mesmo deverá ser membro do projeto geolocalização, caso contrário a dependência não será instalada.