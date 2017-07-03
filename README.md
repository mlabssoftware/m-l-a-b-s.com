1 - Registre um dominio ".com" para que o facebook entenda nos comentários
 (exemplo: m-l-a-b-s.com)

2 - Crie uma aplicação no facebook para poder utilizar a API.


3 - As imagens que você deseja que apareçam nos comentários devem estar em um URL, pode ser no seu próprio site.

4 - Pegue o nosso código,(https://github.com/mlabssoftware/m-l-a-b-s.com/) atualize com a url de suas imagens.

5 - Atualize o arquivo refresh.php com o token de seu aplicativo.

6 - Atualize o arquivo script.sh, colocando a sua url.

7 - Adicione no seu CRON o codigo abaixo para executar o script de atualização da API do Facebook.
   - 7.1 - * * * * * bash <caminho_do_seu_arquivo_script.sh_no_seu_servidor>

8 - Aproveite.


Dicas:


- Tente colocar todas as imagens na mesma proporção.

- Quanto alterar alguma imagem, alterar também o nome dela.

- Coloque no ar com antecedencia e faça alguns testes para que o facebook entenda o mecanismo e pegue suas imagens.

- Por segurança, recomendamos criar um novo aplicativo no Facebook somente para esta dinâmica.

- Monitore o processo do CRON pois é ele quem garante o funcionamento da dinâmica e deve estar sempre rodando em seu servidor.
