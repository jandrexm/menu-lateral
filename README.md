# menu-lateral
Uma empresa lançou um teste A/B para avaliar a usabilidade do menu lateral de sua plataforma. O teste compara duas configurações:
1. Acesso direto a uma página específica do site (Nível 0 do menu lateral).
2. Acesso à mesma página, mas sob uma aba mais geral (Nível 1 do menu lateral).

O objetivo do desafio a seguir foi determinar qual configuração do menu lateral leva a mais acessos e conversões para a página
específica da plataforma. Com a justificativa de que identificar a configuração mais eficaz ajudará a otimizar a navegação do site para aumentar o engajamento
dos usuários.


## Base de Dados

A base de dados ('ab_test_data.xlsx') anexada a este projeto inclui as seguintes colunas:
- `user_id`: identificador único do usuário
- `device`: dispositivo do qual o usuário acessou a plataforma
- `country`: país do qual o usuário acessou a plataforma
- `timestamp`: data e horário em que o usuário acessou a plataforma
- `group`: versão do menu lateral (Nível 0 ou Nível 1)
- `converted`: conversão do usuário para a página de interesse
- `session_duration`: tempo (s) em que o usuário permaneceu ativo na página de interesse