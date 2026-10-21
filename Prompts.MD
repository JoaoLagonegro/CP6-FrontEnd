Prompt Incial:
Quero criar meu portfólio pessoal em uma landing page de uma página só, em HTML, CSS e JS num único arquivo, sem frameworks. É para um checkpoint da faculdade (FIAP, Engenharia de Software, 2º semestre). Meu objetivo é mostrar o que já aprendi e conseguir minha primeira experiência no mercado, então quero um visual moderno, ousado e tecnológico, mas com um tom acolhedor e direto, de quem está começando e quer aprender.

Referências de layout (me diga no final o que pegou de cada uma):

Nike: títulos gigantes em caixa alta e condensados, muito impacto.
Adidas: faixa de texto passando sem parar na horizontal e grade de cards.
Apple: menu fixo meio transparente com desfoque, bastante espaço entre seções e elementos que surgem suavemente quando dou scroll.
Spotify: fundo escuro com uma cor forte de destaque e botões arredondados que aumentam um pouco no hover.
Airbnb: cards com cantos bem arredondados que sobem um pouco quando passo o mouse.

Cores: fundo preto 
#0B0B0B, cards em 
#161616, títulos em 
#F5F5F0, textos corridos em 
#E4E4DE (bem claros, nada de cinza apagado sobre o fundo preto), textos de apoio em 
#8A8A85, e verde-limão neon 
#D7FF3A só para destaques (botões, números, faixa em movimento e detalhes).

Fontes: Anton nos títulos e Inter (sans-serif) no texto corrido, com peso 500 e tamanho confortável para ler. Os textos logo depois dos títulos grandes precisam ficar bem legíveis e destacados.

Seções, nesta ordem:

Menu fixo com meu nome (João Lagonegro) e links para as seções, com menu hambúrguer no celular.
Hero com o título “O que Busco.” (a palavra “Busco.” na cor neon), um parágrafo curto sobre mim e dois botões (“Ver projetos” e “Fale comigo”).
Faixa em movimento com as palavras Design, Front-end, UX, IA e Criatividade.
“Quem sou”: dois parágrafos sobre mim e quatro quadrados com números (checkpoints, projetos, eventos e cursos), cada um com uma linha fina de 1px na cor neon em volta.
Skills: chips arredondados (HTML e CSS, JavaScript, Figma, UI Design, UX Research, Git e GitHub, Prompt Engineering, Vibecoding, Comunicação).
“Cursos Realizados”: três cards com número, o nome da plataforma (Alura) em negrito, um pouco maior e na cor neon, título do curso, descrição curta e botão “Ver mais”. Os cards também têm a linha fina de 1px na cor neon, igual à dos quadrados do “Quem sou”.
“Experiências e eventos”: linha do tempo com três itens.
Contato: título grande “Vamos conversar?” e botão com meu e-mail, com o link mailto: apontando para o mesmo endereço mostrado no botão.

Requisitos: funcionar bem no celular e no desktop, com todos os links do menu levando à seção correta e animações respeitando a preferência de movimento reduzido. Use textos de exemplo que eu vou trocar, e escreva sem erros de português. Mande o código completo em um único bloco, terminando em </html>, e se for muito longo me avise antes de dividir.

-----------------------------------------------------------------------

2 prompt: Para os textos das informações pessoais, logo apos os titulos grandes, use a fonte Sans Serif, e deixe as letras mais destacadas, estão muito apagadas

O que a IA entregou: uma cor de texto mais clara (--soft), peso 500 e tamanho maior nos parágrafos após os títulos grandes, com a fonte sans-serif definida explicitamente. Esse ajuste foi feito sobre o código que eu enviei, com os meus textos já preenchidos.

-----------------------------------------------------------------------

3 prompt: Altere os textos "Alura" para negrito tambem e um pouco maiores, para deixar destacado a plataforma que fiz os cursos, e os quadrados do Quem sou eu, coloque em volta de cada quadrado uma linha fina da cor preta, para dar destaque

-----------------------------------------------------------------------

4 prompt: Coloque tambem a mesma linha preta em volta dos cards dos cursos realizados

-----------------------------------------------------------------------

Correção 1: texto apagado e fonte

Campo	Registro

Problema	Os textos logo depois dos títulos grandes (hero, Quem sou, cursos e trajetória) estavam em um cinza muito fraco sobre o fundo preto. Ficavam apagados e difíceis de ler.

Prompt de correção	“Para os textos das informações pessoais, logo apos os titulos grandes, use a fonte Sans Serif, e deixe as letras mais destacadas, estão muito apagadas”

Resultado	Resolveu totalmente. Os parágrafos passaram a usar uma cor mais clara, peso mais forte e tamanho maior. A fonte já era sans-serif (Inter), então a diferença visível veio da cor e do peso.

Aprendizado	No prompt inicial eu deveria ter pedido a legibilidade dos textos sobre fundo escuro e indicado a fonte do texto corrido. Também ajuda dizer o que “destacado” significa para mim (mais claro, mais grosso ou maior), para a IA não precisar adivinhar.

-----------------------------------------------------------------------

Correção 2: código com erro

Campo	Registro

Problema	O código copiado dava erro. Ele estava cortado no meio, terminando em font-size:4rem;lin, então faltavam o restante do CSS, o HTML e o JavaScript. A resposta anterior da IA tinha sido interrompida por ser muito longa.

Prompt de correção	“O CODIGO ESTA DANDO ERRO” (enviado junto com o código quebrado)

Resultado	Resolveu totalmente. A IA identificou que o código estava incompleto e enviou a versão completa.

Aprendizado	Mandar o código quebrado junto com o aviso de erro ajudou a IA a achar a causa rápido. Na próxima vez, vou conferir se o código termina em </html> antes de colar, e posso pedir já no início que, se o código for muito longo, seja enviado em partes.

-----------------------------------------------------------------------

Correção 3: destaque do “Alura” e dos quadrados do “Quem sou”

Campo	Registro

Problema	O nome da plataforma (Alura) nos cards de cursos estava pequeno e discreto, e os quadrados de números da seção “Quem sou” não tinham destaque em relação ao fundo.

Prompt de correção	“Altere os textos “Alura” para negrito tambem e um pouco maiores, para deixar destacado a plataforma que fiz os cursos, e os quadrados do Quem sou eu, coloque em volta de cada quadrado uma linha fina da cor neon, para dar destaque”

Resultado	Resolveu totalmente (confirme depois de testar). O “Alura” ficou em negrito e maior, e os quadrados ganharam uma linha fina de 1px na cor neon.

Aprendizado	Esse prompt juntou dois pedidos diferentes. Funcionou porque eram mudanças simples e independentes, mas o ideal é corrigir um problema por vez, como o enunciado recomenda, para o registro ficar mais claro e a IA não misturar as coisas. Também podia ter dito o tamanho desejado (“1rem”, por exemplo) em vez de “um pouco maiores”.

-----------------------------------------------------------------------

Correção 4: linha em volta dos cards de cursos

Campo	Registro

Problema	Depois de ver os quadrados do “Quem sou” com contorno, os cards dos cursos realizados ficaram sem o mesmo detalhe, e o visual ficou inconsistente entre as seções.

Prompt de correção	“Coloque tambem a mesma linha preta em volta dos cards dos cursos realizados”

Resultado	Resolveu em parte (confirme depois de testar). O prompt dizia “linha preta”, mas a linha dos quadrados é neon. A IA aplicou a mesma cor neon, para ficar igual à dos quadrados, e avisou da diferença. Se a ideia era mesmo preto, ainda falta ajustar.

Aprendizado	Eu errei a cor no prompt, então devo conferir o que escrevo, e ainda melhor é dar o código da cor (por exemplo, 
#D7FF3A). Referenciar “a mesma linha” funcionou bem para manter a consistência, mas só quando a descrição está certa.