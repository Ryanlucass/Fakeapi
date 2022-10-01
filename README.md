# Criando API Fake para testes 

## Para que serve ? 
Quando estamos fazendo alguma aplicação que utiliza recebimento de informações por json, precisamos testar as funcionalidades do nosso código, mas muitas vezes não temos como. Por isso, você pode criar uma api fake com os possíveis dados que você irá receber no seu sistema, e já valida todas as partes do seu código

## Como funciona ? 🤔

O [{JSON} Placeholder](https://jsonplaceholder.typicode.com/) funciona como um servidor de hospedagem para um código json. você primeiro precisa criar um repositório **público** com um código json, intitulado **db.json**. dentro dele você cria o json de sua maneira ex.

```
{
    "profile":{
            "id": 23,
			"nome": "Rafael",
			"sobrenome": "Alves",
			"idade": 21,
    }
}
```
A partir dai sua API estará disponível no edereço de url **https://my-json-server.typicode.com/{nome_github}/{nome_repositorio}**

---
Para mais informações detalhadas sobre a api e sobre as suas possibilidads, aconselho dar uma olhada na documentação feita pelo Diego Martins Pinho, que me ajudou bastante na hora de criar a mihha.
[Criar api fake](https://medium.com/code-prestige/como-criar-um-a-api-rest-fake-para-testes-jsonplaceholder-7cc106ea3bd6)

Made with ♥ by Lucas Ryan :wave: 
