**Como contribuir para o NumPy \- Texto**

**Página 1**

“Na universidade de Monty”

Alice: “Ufa, estou tão feliz que terminamos a aula de laboratório.”,  
(Alice está aliviada após uma bateria de aulas de laboratório.”

Bob: “Maaas não terminamos ainda.”  
(Bob lembra Alice que ainda tem mais trabalho para ser feito.)

Alice: “Precisamos analisar os dados de imagem das células, certo? Com NumPy?”  
(Alice está se referindo a analisar dados de uma imagem de células usando o NumPy, indicando que estão trabalhando em algum processamento de dados científicos.)

Alice: “Sim… E eu não faço a mínima ideia de como usar o NumPy. Então agradeço por virem depois da aula me ajudar.”,  
(Alice admite que não sabe usar o NumPy e expressa gratidão por virem ajudá-la.)

Chris:”Sem problemas\! A gente fica feliz em ajudar. Já mexi com o NumPy em uma aula de ciência da computação.”  
(Chris está confiante e tranquiliza Alice, mencionando experiência prévia com NumPy em outro contexto (ciência da computação).)

**Página 2**

Alice: “Você se lembra do que fizemos no laboratório certo ?”,

Bob: “Sim, nós terminamos de tingir as células.”,

Alice: “Então agora todas as informações das imagens das células estão compactadas em um arquivo zipado. Portanto, usamos o NumPy para extrair o arquivo.”,  
(Alice explica que as imagens das células estão comprimidas em um arquivo, e o NumPy vai ser usado para lidar com a extração.)  
\[Tingimento, escaneamento, Imagens, Compactação, arquivo npz, Descompactação\]

Bob: “Matrizes ? Como uma imagem pode ser um bando de números ?”  
(Bob está confuso em como uma imagem pode ser representada por uma matriz de números.)

Chris:” Nos não podemos abrir a imagem… como uma imagem? Ver com nossos olhos ?”,

(Chris pergunta por que não podem ver a imagem diretamente em vez de lidar com matrizes.)

Alice: “Bem, na pesquisa de microbiologia, estamos analisando muitas e muitas imagens de células. E com a matriz do NumPy(ndarray) nós podemos analisar e processar muito mais rapidamente do que fazendo manualmente, imagem por imagem.”  
(Alice esclarece que na pesquisa, muitas imagens precisam ser processadas, e usar os ndarrays do NumPy acelera este processo)

Bob: “Eu posso trabalhar com 3 imagens. ”,

Chris: “Mas 400 imagens? De apenas uma aula de laboratório ?”

Bob: “Hmm. Isso faz sentido, eu presumo.”,  
    
**Página 3**

Chris: “Ok\! Então por onde começamos ?”,

Alice: “Vamos começar criando um arquivo python.”,

Alice: “No arquivo, vou começar importando o NumPy.”,  
(Alice está explicando o passo inicial de iniciar um script Python importando a biblioteca NumPy.)

Alice: “Nosso professor deu as imagens das células em um arquivo .npz chamado cell\_images.npz.”   
((Alice explica que eles receberam as imagens das células em um arquivo compactado do NumPy (formato .npz).)

Alice: “Vamos combinar a função np.load() com cell\_images.npz.”,  
(Alice introduz o uso do NumPy para abrir um arquivo .npz)

Alice: “E este é nosso arquivo .npz aberto”  
(Alice aponta o conteúdo do arquivo após usar np.load().)

Bob: "Ótimo\! Mas... são muitos arquivos. Como vamos saber qual é o nosso?"  
(Bob está confuso com as várias entradas de dados no arquivo carregado e se pergunta como identificar a correta.)

Chris: “Você tem razão. Eu quero minhas imagens de células do laboratório das 10h.”

Bob: "'npzfile A' não me diz se isso é do laboratório das 10h ou das 15h."  
(Bob está frustrado porque o nome do arquivo não esclarece a qual sessão de laboratório os dados pertencem.)

Alice: “Isso parece um dicionário, vamos usar a função Keys.. ”  
(Alice propõe usar a estrutura semelhante a um dicionário do arquivo para inspecionar suas chaves e identificar os dados corretos.)

Chris: “Dicionário ? Chaves ?”,  
(Chris não tem certeza de como os dicionários funcionam nesse contexto.)

Bob: "Entendi. Como estou vendo keysview, isso é de fato um objeto semelhante a um dicionário.",  
(Bob confirma que o arquivo .npz carregado se comporta como um dicionário após inspecionar as chaves.)

Alice: "Os atributos do objeto 09-09-10AM..."

Bob: "Vamos mudar nossa abordagem. Vamos usar a função list() para transformar tudo isso em uma lista adequada.",  
(Bob sugere converter as chaves em uma lista para facilitar o manuseio dos dados.)

Bob: "Agora transformamos nossos arquivos .npz em uma lista de objetos\! A lista de objetos é uma lista de nossas sessões de laboratório."

Bob: "Cada sessão de laboratório é um objeto também. Eu quero ver as imagens do objeto 09-09-10AM."

Alice: "Vamos ver todos os nomes dos arquivos dos objetos 09-09-10AM... Pronto\! Agora temos as imagens das células capturadas durante nosso laboratório das 10h \!"  
(Alice encontra os dados relevantes após listar as chaves e identifica as imagens corretas.)

**Página 4**

Chris: "MAS—QUE—?\!"

Bob: "Por que você não consegue ver o nome do arquivo bem ali?"  
(Bob está frustrado porque os nomes dos arquivos não estão visíveis.)

Chris: "Você disse que o NumPy deveria ser mais rápido\! Melhor do que fazer manualmente\!"  
(Chris está chateado porque o NumPy não está facilitando a tarefa.)

Alice: "Quer dizer, eu esperava que o keysview me dissesse o nome do arquivo. Mas, na verdade, ele não diz."  
(Alice está explicando que o keysview não deu o resultado esperado.)

Bob: "Então você precisa contornar essa estranheza\!"  
(Bob incentiva Alice a encontrar uma solução para o problema.)

Alice: "Posso contornar isso, já que sei como inspecionar objetos..."

(Alice assegura que sabe como lidar com a situação, apesar do problema.)

Chris: "Mas ei, tudo bem desde que funcione."

(Chris tenta minimizar o problema, focando na funcionalidade.)

Bob: "Não acho que devamos aceitar 'desde que funcione\!' Isso torna nossas vidas mais difíceis\!"   
(Bob se opõe, afirmando que não devem se contentar com soluções subótimas.)

Chris: "Você está certo. É difícil, mas podemos mudar isso\!"  
(Chris concorda com a perspectiva de Bob e expressa esperança por melhorias.)

**Página 5**

Alice: “NumPy é um projeto de código aberto. Qualquer um pode contribuir ou mudar o código base. Mesmo como estudantes de pós-graduação, podemos fazer sugestões, como tornar mais fácil a abertura de arquivos .NPZ. E então, outras pessoas podem desenvolver essa sugestão e transformar essa funcionalidade em realidade\! ”  
(Alice explica que a natureza de código aberto do NumPy permite que os usuários aprimorem sua funcionalidade.)

Chris: “Dessa forma, nós podemos contribuir para a ciência aberta ”  
(Chris destaca a conexão entre contribuir para o NumPy e promover a ciência aberta.)

Bob: "Maaas\! O que é que nós realmente deveríamos fazer?"  
(Bob não tem certeza de como eles podem começar a contribuir para o NumPy.)

Alice: "Como o NumPy é uma ferramenta usada em microbiologia, estamos criando as ferramentas que tornam a pesquisa científica mais colaborativa e transparente\! Não é incrível?"

(Alice enfatiza que aprimorar o NumPy pode ter um impacto positivo na pesquisa científica, especialmente em áreas como a microbiologia.)

Chris: "Hum… Acho que devemos criar uma issue no GitHub.com, dizendo que temos um problema e sugerindo uma solução..."  
(Chris lembra que as contribuições para o NumPy começam com a criação de issues no GitHub para abordar problemas.)

Bob: "Certo, então eu nunca contribui ou fiz nada até agora, mas aprendi muito naquela palestra sobre ciência aberta no semestre passado\!"  
(Bob reflete sobre seu conhecimento em ciência aberta, mas admite que ainda não fez contribuições.)

Chris: “Eu tenho uma conta no GitHub. Podemos tentar com a minha\!”  
(Chris se oferece para usar sua conta do GitHub para começar.)

Alice: "Ótimo\! Vamos olhar o NumPy.org para encontrar a página deles no GitHub."  
(Alice sugere que eles visitem o site do NumPy para localizar o repositório deles no GitHub.)

**Página 6**

Alice: “No NumPy.org”  
(Alice está navegando pelo site do NumPy)

Chris: “Vamos clicar aqui\!”  
(Chris aponta para a seção no site para explorar mais a fundo.)

Alice: "Bem, estou olhando o NumPy.org e, hmmm..."  
(Alice parece incerta sobre para onde ir a seguir no site.)

Chris: "Não, tenho quase certeza de que podemos começar com o GitHub. Vamos clicar aqui."  
(Chris direciona Alice para visitar o repositório do GitHub do NumPy para começar a contribuir.)

Bob: "Isso parece complicado. Uma lista de discussão, Slack, chamadas da comunidade? Demais\!"  
(Bob se sente sobrecarregado pelas opções de comunidade disponíveis no site do NumPy.)

Alice: "Aí está\! Agora estamos na página do GitHub do NumPy, com uma lista de problemas."  
(Alice chega com sucesso à página do GitHub do NumPy, onde os problemas estão listados.)

Chris: "Vamos criar uma nova issue aqui. O que queremos é um pedido de recurso."  
(Chris explica que eles precisam criar uma nova issue para solicitar um recurso.)

Alice: "Vamos escrever um problema."  
(Alice se prepara para redigir o pedido de recurso.)

**Página 7**

Alice: (Escreve) "Mostrar nomes de arquivos no arquivo npz?"  
(Alice cria um pedido de recurso sobre a dificuldade em identificar nomes de arquivos dentro de arquivos .npz.)

Chris: "Oi, somos estudantes de microbiologia usando o NumPy para analisar nossas imagens celulares."  
(Chris explica o contexto do seu caso de uso com arquivos .npz.)

Bob: "Eu não sei como usar keys."  
(Bob expressa confusão em relação às keys no estilo dicionário nos objetos do NumPy.)

Chris: "Ah, sim\! Deixe-me adicionar essa parte..."  
(Chris se oferece para ajudar esclarecendo como as chaves funcionam nos objetos do NumPy.)

**Página 8**

Bob: "Agora diga a eles para resolverem isso."  
(Bob está ansioso por uma solução e quer uma ação imediata.)

Chris: "Eu não acho que devemos ser tão exigentes\!"  
(Chris sugere uma abordagem mais diplomática para o pedido de recurso deles.)

Alice: (Escreve) "Os nomes dos arquivos poderiam ser mais fáceis de ver? Como logo que você abre um .npz?"  
(Alice propõe uma solução potencial para melhorar a interação com arquivos .npz.)

Bob: "Uhul\! Enviado\! Para internet\!"  
(Bob celebra após o envio bem-sucedido do pedido de recurso.)

**Página 9**

Chris: "Depois de todo esse trabalho, eu preciso de uma pausa."

Bob: "Mas e a nossa tarefa?\!"

Chris: "Ainda podemos usar o NumPy, só que é... inconveniente."

Chris: "Bem, eu tenho as notificações do GitHub ativadas. Então não se preocupe, vamos receber uma resposta."

\[O tempo passa, ambos estão relaxando.\]

Bob: "Oh, alguém respondeu\!\!"

\[Eles correm animadamente para verificar a resposta.\]

Chris: "Ahhh, tá bom\! Vamos dar uma olhada."

**Página 10**

\[Olhando para a issue no GitHub feita para mostrar nomes de arquivos em arquivos npz\]

Alice: "Então, esta é a issue que criamos..."

Alice: "Uau, um mantenedor comentou, e outra pessoa....?"

Bob: "Quem são essas pessoas?"

Bob: “O que estão dizendo ?”

Bob: "Precisamos fazer algo agora?\!"

\[Alice explica quem é um mantenedor e um contribuinte, a imagem explica como a discussão e a contribuição acontecem\]

Alice: "A primeira pessoa é um mantenedor."

Alice: "O mantenedor lidera o NumPy, coordenando com muitas pessoas em direção ao grande objetivo."

Alice: "A segunda pessoa é um contribuinte."

Alice: "Eles querem ajudar\! Para resolver nossa issue fazendo um pull request\!" 

Alice: "Juntos, mantenedores e contribuidores implementam novos recursos, corrigem bugs e escrevem documentação para melhorar o NumPy."

**Página 11** 

Bob: "O contribuinte fez um pull request\! O que é isso?"

Alice: "Um pull request é um pedido para fazer alterações no código do NumPy. Este está mudando os arquivos npz."

\[Há um comentário no pull request de um contribuinte dizendo que eles podem ajudar, fornecendo uma solução de como isso pode ser corrigido, levantando um pull request.\]

Alice: "Podemos ver as mudanças que o contribuinte fez no código."

Bob: "Para ser honesto, eu não entendo completamente o que está sendo mudado..."

\[Alice aponta para o resumo do pull request levantado pelo contribuinte, indicando quais alterações de código estão sendo feitas.\]

Alice: "Tudo bem, aqui está um resumo do que foi alterado."

\[Bob dá uma olhada no pull request.\]

Bob: "Eu me pergunto o que o contribuinte está fazendo..."

Bob: "Eles devem saber tudo sobre o NumPy para fazer um pull request assim..."

**Página 12**

\[Na parte seguinte, vemos a perspectiva do contribuinte pensando\]

"Enquanto isso, muito longe, o criador daquele pull request pensa..."

Contribuinte: "Ah, eu não sei nada sobre o NumPy?"

Contribuinte: "Espera \- não se critique tanto. Você sabe sobre o NumPy."

\[Contribuinte olhando para seu pull request sendo revisado com sucesso\]

Contribuinte: "Estou feliz que um mantenedor revisou meu trabalho. Mas como eu respondo?"

Contribuinte: "A revisão disse que eu perdi o X. O que faz sentido."

Contribuinte: "A maior parte do meu pull request já funciona. Então estou 80% feito."

Contribuinte: "Só preciso reescrever algumas partes e terminar os últimos 20%\!"

\[Um contribuinte reflete um pouco sobre sua contribuição e verifica a revisão que recebeu do mantenedor. O contribuinte percebe que ainda há 20% de trabalho a ser concluído.\]

**Página 13**

\[Em algum lugar no laboratório, o contribuinte pensa sobre a experiência passada com a questão do arquivo npz\]

Contribuinte: "Esses estudantes... sinto uma conexão. Faz anos que estive em um laboratório."

Contribuinte: "Mas me lembro de ter trabalhado no mesmo problema com o tipo de arquivo npz."

Contribuinte: "Por que eu não submeti minha própria issue? Dizer que precisava dessa ajuda também?"

Contribuinte: "Acabei criando minhas próprias soluções alternativas."

Contribuinte: "Se eu tivesse submetido minhas próprias soluções como um pull request todos aqueles anos atrás..."

Contribuinte: "Talvez eu pudesse ter ajudado outros enfrentando o mesmo problema?"

Contribuinte: "Eh\! Eu provavelmente estava focado demais em terminar minha tese para submeter um pull request."

Contribuinte: "Estou feliz por poder retribuir agora."

Contribuinte: "Me pergunto como o mantenedor está indo."

Contribuinte: "Ele deve saber tudo sobre o NumPy... muito mais do que eu."

\[O contribuinte reflete sobre o passado, quando enfrentou um problema com o tipo de arquivo npz e pensa que uma issue poderia ter sido levantada antes.\]

**Página 14**

"Enquanto isso, muito longe, o mantenedor do NumPy pensa..."

Mantenedor: \[Bebendo um café\] "Posso ver que quem fez o PR atualizou seu pull request com base nos meus comentários."

Mantenedor: "Vou revisar o código novamente e verificar se está pronto para ser mesclado."

\[O mantenedor dá uma olhada nas mudanças revisadas e margeia o pull request.\]

Mantenedor: "Estou feliz por ter esses estudantes me informando sobre os problemas que estão enfrentando."

Mantenedor: "Não sou mais professor em laboratório há um ano, então não estou sempre ciente desses problemas."

Mantenedor: "Estou contente que futuros estudantes poderão navegar mais facilmente com arquivos npz."

\["O mantenedor revisa o pull request e se sente grato pelos estudantes que levantaram a questão sobre o problema que estão enfrentando."\]

**Pagina 15**

"2 meses depois"

Alice: "Confira este e-mail\!"

\[Todos os três verificam o e-mail que receberam, já que se inscreveram na lista de discussão do NumPy.\]

"É da lista de discussão do NumPy. Eu me inscrevi para acompanhar nossa issue."

Alice: "Agora nosso recurso solicitado está aqui, neste ciclo de lançamento

\[Um vislumbre do e-mail mostrando os recursos no lançamento.\]

Chris: "Isso soa legal... será que realmente funciona?"

\[Eles agora testam o código de exemplo para carregar o arquivo npz e verificar se o novo recurso foi atualizado ou não, e funciona\!\!\!\!\!\!\!\]

\[Todos, chocados e animados\]: "Uau\! É muito mais fácil ver se as imagens celulares vieram do laboratório das 10h ou das 14h."

**Página 16**

Chris: "Uau. Agora eu entendo."

Chris: "É tão legal saber que eu fiz a diferença para o NumPy\!"

\[Chris conta a história sobre como essas mudanças começaram com uma única issue.\]

\[O estudante escreve uma issue, o contribuinte escreve um pull request, o mantenedor revisa o pull request, o pull request é mesclado e o código adicionado ao código base do NumPy, a versão atualizada do NumPy é lançada em todo o mundo.\]

Chris: "Começou com uma pessoa e cresceu a partir daí\! O problema do arquivo npz e o NumPy foram construídos por muitas pessoas, todos colaborando e se apoiando."

\[A animação continua.\]

"Agora eu quero participar da próxima chamada da comunidade do NumPy."

"Eu quero entender o código base do NumPy também."

"Eu também quero fazer meu próprio pull request."

"Conhecer esses contribuintes que nos ajudaram."	

"Desmontá-lo, fazer perguntas."

"Uau, eles mudaram de serem os maiores céticos para os maiores fãs do NumPy\!"

"Vai em frente\!"

"O Fim."