# MovieApp 🎬

**MovieApp** é um aplicativo Flutter que permite aos usuários explorar detalhes sobre filmes, incluindo avaliações dos espectadores, recomendações, filmes similares e muito mais, utilizando a API do The Movie Database (TMDb).

## Funcionalidades 📱

- Exibir filmes em alta, lançamentos e próximos lançamentos.
- Pesquisar filmes por título.
- Visualizar detalhes de filmes, incluindo sinopse, avaliação, gênero e data de lançamento.
- Ler reviews e ver os créditos do filme (elenco e equipe).
- Obter recomendações e filmes similares com base em gêneros e palavras-chave.

## Tecnologias Utilizadas 🛠️
- Flutter - Framework para desenvolvimento mobile.
- Dart - Linguagem de programação.
- TMDb API - API para buscar informações de filmes.

## Instalação 🚀
1. Clone este repositório:
```git clone https://github.com/BernardoAssad/movie_app.git```

2. Acesse o diretório do projeto:
```cd movie_app```

3. Instale as dependências:
```flutter pub get```

 Configure sua API Key do The Movie Database (TMDb):

- Crie uma conta no TMDb.
- Gere uma chave de API.
- Insira sua chave em lib/common/utils.dart:
```const String apiKey = 'SUA_API_KEY_AQUI';```

5. Execute o aplicativo:
```flutter run```

## Como Usar 📖

- Na tela inicial, você verá uma lista de filmes populares, filmes em alta e filmes que estão por vir;
- No menu abaixo use a função de encontrar filmes específicos;
- Navegue até os filmes top hated e veja os que estão em alta;
- Clique em algum dos filmes e tenha acesso a detalhes como informações completas, incluindo reviews, filmes similares e outras recomendações.
