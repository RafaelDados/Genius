Documentação de Funcionalidades
Quem?

    Estamos desenvolvendo esse aplicativo para aqueles que sentem saudades e vivenciaram a época de ouro do game Genius.

O que?

    Um aplicativo terá por finalizade realizar o controle do jogo Genius.

Por que?

Funcionalidades
Cadastrar Usuário:

SENDO o botão cadastrar apertado
POSSO enviar dados para o firebase
PARA armazenar os usuários

Cenário 1: cadastro com sucesso (armazenou o Usuário)

Dado que a activity de cadastro de Usuário está aberta
E todos os campos obrigatorios foram preenchidos
Quando aperto o botão de cadastrar
Então o sistema transmite os dados ao firebase
E o cadastro é realizado

Cenário 2: falha no cadastro (usuário não armazenado)

Dado que a activity de cadastro está aberta
E e um ou mais campos obrigatórios não foram preenchidos
Quando aperto o botão de cadastrar
Então o sistema transmite os dados ao firebase
E o firebase não recebe as informações
E o sistema emite uma notificação de erro alertando que existem campos a serem preenchidos

Cadastrar tipo de Usuário:

SENDO o botão tipo de usuário apertado
POSSO enviar dados para o firebase
PARA armazenar o tipo de usuário

Cenário 1: atuar com sucesso (armazenou o tipo de usuário)

Dado que a activity de cadastro tipo de usuário está aberta
E todos os campos obrigatorios foram preenchidos
Quando aperto o botão de cadastrar
Então o sistema transmite os dados ao firebase
E o cadastro é realizado

Cenário 2: falha na atuação (não armazenou o tipo de usuário)

Dado que a activity de cadastro tipo de usuário está aberta
E e um ou mais campos obrigatórios não foram preenchidos
Quando aperto o botão de cadastrar
Então o sistema transmite os dados ao firebase
E o firebase não recebe as informações
E o sistema emite uma notificação de erro alertando que existem campos a serem preenchidos

Cenário 3: falha na comunicação

Dado que o dispositivo está desconectado da rede
Quando aperto o botão de cadastrar
E o firebase não recebe as informações
O sistema emite uma notificação alertando que não foi possivel estabelecer conecção com o banco de dados

Tela de Ranking:

SENDO o tela de ranking selecionada
POSSO receber dados doo firebase
PARA armazenar os usuários

