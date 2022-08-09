# Well-Being
Pages: https://well-being-app.github.io/well-being/

## Escopo
O Well-Being é um aplicativo que propõe facilitar uma vida mais saudável para as pessoas, retirando a dificuldade no planejamento das refeições e de lembretes importantes para a saúde. Para isso, o aplicativo utiliza os dados de anamnese do usuário para recomendar cardápios semanais, quantidade de água que deve ser consumida e lembretes para remédios.
As sugestões de alimentação semanal e lista de compra de mercado serão geradas com base na tabela [TACO](https://www.nepa.unicamp.br/taco/tabela.php?ativo=tabela), que fornece alimentos base e valr nutricional dos mesmos.

## Funcionalidades

- **Cadastro de alimentos** - os dados base de alimentos que serão utilizados estão na tabela TACO, mas o usuário administrador pode cadastrar outros alimentos no sistema, informando os dados necessários para a utilização nas funcionalidades;
- **Cadastro de usuário** - cadastro de usuário e senha;
- **Registro da anamnese do usuário** - deve ser feito após o cadastro, caso não feito, nenhuma das outras funcionalidades estará disponível;
- **Criação de cardápio por período** - o usuário pode solicitar um cardápio selecionando um período de dias incluindo cafá da manha, almoço, café da tarde e jantar para sua semana de acordo com a sua anamnese (por exemplos, para alergicos a glutem, alimentos com glutem não serão apresentados);
- **Solicitação da lista de compras semanal relacionada a cardápio** - pode ser feito após a solicitação do cardápio e será feita com base no mesmo;
- **Solicitar alternativa do dia cardápio** - selecionando um dia do cardápio, pode ser solicitada uma alteração no cardápio daquele dia;
- **Ver lembrete de hidratação** - após a anamsene, o sistemaé capaz de calcular a quantidade e os horários em que o usuário deve ingerir liquidos. Então, o usuário pode consultar esses lembretes gerados (que também virão como notificações nos horários pertinentes);
- **Configurar lembretes de medicamentos** - a pessoa que precisa de lembretes para seus remédios controlados, pode inserir os dados do medicamento no sistema e também os horários que devem ser tomados pra que o sistema gere notificações (lembretes);

