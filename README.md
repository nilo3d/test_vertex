#O que é preciso para testar?
É preciso ter o mysql e laravel isntalado. A aplicação foi feita no laravel na sua versão mais recente (5.7.7). 

#Executando o DUMP.
Para facilitar o teste execute o DUMP. O DUMP instala o banco de dados e as tabelas já populadas.

#Testando o projeto
Pelo prompt de comando acesse a pasta do projeto. Dentro da pasta digite o comando php artisan serve. A seguinte mensagem deve aparecer:
Laravel development server started: <http://127.0.0.1:8000>. Com isso basta acessar seu navegador e digitar a URL: http://localhost:8000 e se tudo ocorrer bem a aplicação irá abrir.

#Detalhes do projeto
O projeto foi feito para funcionar em qualquer tamanho de tela usando o framework Bootstrap (que já vem embutido no laravel). O projeto tem o objetivo de cadastrar endereços (com preenchimento automático a partir do CEP) no banco de dados. Os endereços salvos podem ser verificados tanto por uma listagem geral como usando o campo de busca.
