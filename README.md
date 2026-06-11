🌾 1. O Tema
O tema central do jogo é a Inovação Tecnológica no Campo (também conhecida como Agrotech ou Agricultura 4.0).

O foco é mostrar para os jovens e estudantes como o campo não vive apenas de ferramentas tradicionais. Hoje, a tecnologia de ponta é a maior aliada do produtor rural para produzir mais alimentos agredindo menos o meio ambiente.

🎯 2. O Objetivo
O objetivo principal do jogo é educativo e de conscientização.

Para quem joga: Ensinar de forma divertida (gamificação) como a tecnologia resolve problemas reais do campo, como a economia de água, o combate a pragas e o uso correto de recursos.

Para quem desenvolve (você): Demonstrar a habilidade de criar uma aplicação interativa do zero, utilizando lógica de programação para resolver um desafio pedagógico.

🛠️ 3. Os Recursos Técnicos
Os recursos técnicos são as funcionalidades e a lógica que fazem o jogo funcionar por trás dos panos. Nesse projeto, os principais recursos são:

Estrutura de Dados Dinâmica (Array de Objetos): As perguntas não estão "presas" no texto. Elas ficam guardadas em uma lista inteligente no JavaScript. Isso permite adicionar 10, 50 ou 100 perguntas sem precisar mexer no visual do código.

Manipulação do DOM (Document Object Model): É a capacidade que o JavaScript tem de mudar a página em tempo real. Quando o jogador clica em "Próxima", o código limpa a tela e desenha a nova pergunta sem precisar recarregar o navegador.

Controle de Estado: O jogo "lembra" em qual pergunta o jogador está (indicePerguntaAtual) e quantos pontos ele fez (pontuacao) para exibir o resultado correto no final.

Design Responsivo: O uso de porcentagens e flexbox no CSS garante que o jogo fique bonito e centralizado tanto na tela de um computador quanto na tela de um celular.

🚀 4. As Tecnologias Utilizadas
Para construir esse jogo, foi utilizada a tríade clássica do desenvolvimento web. Nenhuma biblioteca externa foi necessária, o que deixa o jogo super leve:

HTML5 (HyperText Markup Language): É o "esqueleto" do jogo. Ele define onde fica o título, a caixa de perguntas, a área dos botões e o espaço onde aparece o resultado.

CSS3 (Cascading Style Sheets): É a "roupa" e a maquiagem do jogo. Foi usado para criar o fundo degradê moderno, arredondar as bordas das caixas, colocar sombras para dar efeito de profundidade e fazer os botões mudarem de cor suavemente quando o mouse passa por cima (hover).

JavaScript (Vanilla JS): É o "cérebro" do jogo. Ele processa se o usuário acertou ou errou, bloqueia os botões para o usuário não clicar duas vezes na mesma resposta, soma os pontos e decide quando o jogo acabou para mostrar a tela de troféu.
