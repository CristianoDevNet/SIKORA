# SIKORA :: Teams & Tasks Manager
Teste de sabedoria

Versão do Rails: 4.2.5.1
Versão do Ruby: 2.2.4

Gems adicionadas no .gemfile:

-Bootstrap
gem 'twitter-bootstrap-rails'

-Devise
gem 'devise'

-RSpec (testes)
gem 'rspec-rails'

Não foi utilizado o padrão (minitest) do Rails, em vez disso utilizei o RSPEC, com uma simples demonstração (model test)
Para usar os testes com RSPEC basta utilizar "rake spec"

O "U | D" na coluna "Actions?", ao visualizar o time é apensa uma sugestão de posíveis ações para as respectivas tasks e significam Update e delete, respectivamente.

Em alguns pontos foi demonstrado maneiras diferentes dde utilizar aciverecord.

Fugindo um pouco d padrão, preferi criar um método dentro d controller team para tratar das tasks dos usuários (em vez de usar controllers e vies específicas para tasks). Com isso quis demonstrar a flexibilidade do rails. Neste aplicativo, adicionar tasks é feito diretamente na view SHOW do team e o callback volta para a mesma página, permitindo inserções rápidas sem ter que ficar indo e voltando entre páginas diferentes.

# COMO USAR
Ao entrar deve-se cadastrar 2 usuários, criar seus respectivos times e um pedir autorização para o ouro
A interface, acrdito eu, está intuitiva o suficientepra desempenhar essas tarefas
O dono do time pode aprovar ou reprovar solictações de ingresso.
Se houver uma solicitação de ingresso um botão laranja aparecerá na sessão do criador do time.

No mais o código tem explicações complementares.

Qualquer duvida me contacte pelo telegram.

Um grnde araço.
