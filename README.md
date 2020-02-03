## Orientações 

### Desenvolvimento básico: 

- Crie projeto privado no GitLab, disponibilizando sua documentação (descrição,
configuração e execução), e conceda acesso desenvolvedor aos avaliadores;
- Configure um projeto de Teste em sua linguagem de preferência, com seu respectivo
gerenciador de projeto (Gradle, Maven, Bundler, NPM, VirtualEnv ou PipEnv, etc);
- Escolha uma API pública (sugestões: https://jsonplaceholder.typicode.com/,
https://pokeapi.co/, https://developer.marvel.com/) e realize ao menos um teste positivo
para cada método, sendo no mínimo 4;
- Crie, adicionalmente, ao menos dois testes para excessões;

### Desenvolvimento Extra:

- Alimentar para teste com DataProvider, sendo no mínimo 10 dados para cada;
- Configurar build personalizado para rodar testes (por exemplo: tasks específicas no
Gradle);
- Usar BDD;
- Gerar Relatório dos testes;

### Desenvolvimento Ideal:

- Criar sua própria API;
- Usar mocks para valida API;
- Criar Dockerfile para a API;
- Criar Jenkinsfile para rodar projeto no Jenkins CI;
- Integrar estrutura para armazenar dados dos testes para consulta e análise ulterior
(Mongo ou correlato, ElastichSearch).
