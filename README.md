# ANIME-API

**API** é a sigla para Application Programming Interface (ou Interface de Programação de Aplicações, em português). 

Uma API é como um "ponte" entre dois sistemas diferentes. Vamos usar um exemplo:

**Imagine o seguinte:**
Você vai a um restaurante e faz um pedido ao garçom. O garçom pega o seu pedido, leva para a cozinha e depois traz a comida pronta para você.

**No mundo da programação:**

Você é o programa que quer algum dado ou serviço (por exemplo, informações sobre animes).
O garçom é a API, que recebe sua solicitação e sabe como pedir as coisas para o sistema que tem as informações.
A cozinha é o banco de dados ou sistema que realmente guarda os dados.
A API conecta esses dois lados: o seu programa (cliente) e o sistema que fornece os dados (servidor).

**No caso do nosso projeto:**
A API Jikan é como o "garçom" que fala com o MyAnimeList (um site gigante sobre animes). Quando você pede os detalhes de um anime, ela vai lá no MyAnimeList, pega as informações e traz de volta para o seu aplicativo.

**Por exemplo:**

Você pede informações do anime com o ID 37999.
A API pega esses dados do MyAnimeList e devolve algo como:

### json

```
{
  "title": "Demon Slayer",
  "episodes": 26,
  "status": "Finished",
  "rating": "PG-13"
}
```

## Animes com API Jikan
Este projeto é uma demonstração simples que busca e exibe informações sobre animes usando a API Jikan. Ele foi desenvolvido com Next.js e tem como objetivo mostrar como obter dados de uma API externa e exibi-los em uma página de forma clara e organizada.

### Funcionalidades

- Mostra informações de animes como:
- Título
- Número de episódios
- Status (se está finalizado ou em andamento)
- Classificação indicativa
- Imagem de capa do anime
- Busca os dados automaticamente usando a API do Jikan.
- Interface básica, mas funcional, para exibir os animes.


## O que está acontecendo no código?
IDs dos Animes
No código, escolhemos alguns animes que queremos buscar, usando os IDs deles:

```
javascript

const animeIds = [37999, 5114, 40028];
```

**Buscando os dados**
O programa vai até a API (como se fosse buscar informações na internet) e pega as informações dos animes. Ele faz isso para todos os IDs que indicamos.

**Mostrando na tela**
Depois que os dados chegam, eles são organizados e mostrados de forma simples. Para cada anime, aparece:

- O título
- A quantidade de episódios
- O status (se está completo ou não)
- A classificação indicativa
- Uma imagem bonitona do anime.

### Conclusão

APIs são como atalhos que ajudam diferentes sistemas a conversar entre si. Elas tornam tudo mais simples, porque você não precisa reinventar a roda para buscar ou usar dados de outras plataformas. No nosso projeto, usamos a API Jikan para trazer informações sobre animes diretamente do MyAnimeList, o que facilitou muito a criação da aplicação.

Saber usar uma API é super útil, porque abre muitas possibilidades. Dá pra conectar seu projeto com vários serviços e oferecer coisas legais para os usuários, como fizemos aqui. É só pedir os dados, organizar e pronto! 🚀

  
### :family: Integrantes do Projeto


| ![Yasmin Mendes](https://avatars.githubusercontent.com/u/178385852?v=4) <br> <sub> Yasmin Mendes </sub> | ![Bruna Zakaib](https://avatars.githubusercontent.com/u/130071892?v=4) <br> <sub> Bruna Zakaib </sub> | ![Isabela Realli](https://avatars.githubusercontent.com/u/180230011?v=4) <br> <sub> Isabela Realli </sub> | ![Beatriz Soares](https://avatars.githubusercontent.com/u/180229545?v=4) <br> <sub> Beatriz Soares </sub> |
| --- | --- | --- | --- |
| [Yasmin Mendes](https://github.com/YasminMSouza) | [Bruna Zakaib](https://github.com/brunazpessoa) | [Isabela Realli](https://github.com/IsabelaReali) | [Beatriz Soares](https://github.com/Beatriz-sol) |

Licença 📝
Esse projeto está autorizado pelo MIT

