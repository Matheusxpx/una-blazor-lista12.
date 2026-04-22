Matheus lucas de Souza Pereira 326142119 Interação Humano Computador e UX
Heurísticas de Nielsen:

1:Reconhecimento em vez de Memorização:
O usuário vê os pontos e informações na tela, sem precisar lembrar de nada.

2:Consistência e Padrões 
Todos os cards têm o mesmo formato e os botões funcionam da mesma forma

Instruções de como rodar o projeto via terminal:
Para rodar o projeto primeiro, é necessário abrir o terminal na pasta onde a aplicação foi desenvolvida.feito isso em seguida deve-se utilizar o comando dotnet run para iniciar o servidor da aplicação.
Feito isso o terminal exibirá uma mensagem indicando que o sistema está em funcionamento,
juntamente com um endereço local exemplo(:https://localhost:xxxx) com esse endereço basta copiar e colar no navegador para acessaar o site. 

Explicação Técnica:
No meu projeto usei o atributo [Parameter] para tornar o componente reutilizável, permitindo que ele receba valores externos de outros componentes ou da página principal.
No projeto, os parâmetros Titulo, Pontos e Valor são usados para personalizar o conteúdo de cada card, enquanto o EventCallback AoClicar permite que a ação do botão seja definida fora do componente.
Dessa forma, o mesmo componente pode ser reutilizado para diferentes tipos de atividades, apenas alterando os valores enviados, sem necessidade de duplicar o código.
