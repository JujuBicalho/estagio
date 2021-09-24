![ScreenShot](https://i.imgur.com/AdqZrsv.png)


## Modo de instalação

1. Clone o repositório.
1. Use o `composer install`.
1. Renomeie ou copie o arquivo `.env.example` para` .env`.
1. Defina seu `TMDB_TOKEN` em seu arquivo` .env`. Você pode obter uma chave de API [aqui] (https://www.themoviedb.org/documentation/api). Certifique-se de usar o "API Read Access Token (v4 auth)" do painel TMDb.
1. Use `php artisan key: generate`.
1. Use `php artisan serve`.
1. Entre `localhost: 8000` em seu navegador.
