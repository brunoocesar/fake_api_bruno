# API fake do Bruno — CineBrasil

API individual de **Bruno**, usuário GitHub **brunoocesar**, para a seção
**Escolhas da semana** da Home. Estrutura baseada na atividade:
https://github.com/tarsisms/fake_api.

## Publicação

1. Entre no GitHub com a conta `brunoocesar`.
2. Crie um repositório **público** chamado `fake_api_bruno`.
3. Envie **o conteúdo desta pasta**, colocando `db.json` na raiz do novo
   repositório (não dentro de uma pasta). O README pode acompanhar o JSON.
4. Confirme o commit na branch padrão `main`.
5. Abra este endereço e confirme que aparece a lista de recomendações:

   https://my-json-server.typicode.com/brunoocesar/fake_api_bruno/recomendacoes

Não é preciso instalar ou executar um servidor. Um erro 404 indica que o
repositório/arquivo ainda não está disponível publicamente no endereço esperado.
O serviço pode usar cache; alterações no JSON podem demorar a aparecer.

## Dados

Cada recomendação tem `id`, `titulo`, `imagem` e `descricao`. `imagem` identifica
um asset que já existe no aplicativo; os arquivos PNG não precisam ser copiados
para este repositório. Títulos, descrições, ordem e seleção vêm da requisição HTTP.

Para trocar os filmes, edite `db.json` e faça um novo commit no GitHub. Use os
caminhos exatos dos assets existentes. O My JSON Server simula escritas HTTP,
mas elas não persistem alterações no arquivo do GitHub.

Documentação do serviço: https://my-json-server.typicode.com/.
