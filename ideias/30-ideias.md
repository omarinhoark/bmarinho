# Trinta ideias para um criador sozinho

Proposta para Bruno, com prazo até 29/04/2027. São 12 ideias que reforçam o Lobo Solar e 18 fora dele. Saíram de 70 candidatas, e a triagem completa, com o motivo de cada descarte, está em [`candidatas.md`](candidatas.md). As fontes estão em [`fontes.md`](fontes.md).

## Antes de ler

**Como os fatos foram conferidos.** Toda a pesquisa foi feita em 13/10/2026. O navegador de páginas não funcionou neste ambiente (falha de DNS e recusa do proxy), então os fatos de mercado e de concorrência vêm dos resultados e trechos indexados pelo buscador, e não da leitura integral de cada página. Quando um dado aparece em uma fonte só, ou em fonte secundária, isso vem escrito. O que não consegui confirmar está marcado como **hipótese**.

**O que as buscas não alcançam.** "Não encontrei nada parecido" quer dizer só isso. O buscador quase não indexa Instagram nem TikTok, então perfis pequenos podem existir sem aparecer. Antes de lançar qualquer uma, vale uma busca manual dentro do próprio Instagram.

**As marcações.**
- **[venda: depende da cláusula]**: a ideia tem uma versão paga, que só pode sair depois de liberar a cláusula do emprego. Todas funcionam sem ela.
- **[depois de janeiro]**: precisa de página nova de Instagram, que só pode ser criada depois de 13/01/2027.

**As notas.** Vão de 1 a 5, em quatro eixos: ousadia, encaixe nele, viabilidade com 10 a 15 horas por semana e circulação.

**Não é uma fila.** As horas de manutenção não se somam: ninguém faz as trinta ao mesmo tempo. Com 10 a 15 horas livres, cabem duas ou três ao lado do Lobo Solar, que já come boa parte desse tempo.

---

## Parte 1. Doze que fazem o Lobo Solar ser lembrado

### 1. Vale-Errata
**Quem achar um erro no Lobo Solar recebe pelo correio um certificado impresso e numerado, e o erro entra num livro público de ocorrências.**

**Mecanismo.** Toda correção confirmada gera duas coisas.
- Uma entrada no *Livro de Ocorrências*, que fica numa página fixa e num destaque. A entrada mostra a frase original com rasura, a correção, a fonte e o @ de quem achou.
- Um Vale-Errata físico em A6, com número de série, carimbo e a frase rasurada. Quem prefere não dar endereço recebe o PDF.

A página de curiosidades que paga para ser pega no erro inverte a lógica do gênero, e é isso que faz alguém mostrar para outra pessoa.

**O que já existe.** O modelo vem de Donald Knuth, que manda cheques de 0x$1,00, um "dólar hexadecimal" que vale US$ 2,56, a quem acha erro nos livros dele. Desde outubro de 2008, por segurança bancária, os cheques são certificados de um banco fictício, o Bank of San Serriffe ([Knuth, news08](https://www-cs-faculty.stanford.edu/~knuth/news08.html); [divisbyzero, 01/11/2008](https://divisbyzero.com/2008/11/01/knuth-stops-writing-checks/)). A data em que os cheques começaram não foi confirmada. Registros públicos de correção existem em newsletters como a [Faked Up](https://fakedup.substack.com/p/corrections-policy), mas não encontrei nenhum perfil de curiosidades com um livro de erros. A diferença está na escala e no objeto: o vale é desenhado com os formatos do próprio Lobo, e o que se premia é o feed, não um livro técnico.

**Por que só ele faria.** Quem confere tudo em fonte primária pode se dar ao luxo de convidar a fiscalização. A rasura já é um formato visual dele, e o certificado é a rasura em papel.

**Primeira peça.** O desenho do Vale, a página do livro e uma primeira ocorrência honesta: a "Ocorrência nº 000", um erro que ele mesmo achou num rascunho antigo. Mais um story com a regra, publicado junto com a estreia.

**Custo.** Menos de 1 hora por semana, só quando chega erro. A carta básica de até 20 g custa R$ 2,65 desde o reajuste de abril de 2026 ([IstoÉ Dinheiro](https://istoedinheiro.com.br/reajuste-dos-correios-veja-novas-tarifas-para-carta-carta-comercial-e-telegrama); a tabela oficial apareceu truncada). Some cerca de R$ 1 de impressão. O remetente precisa ser um endereço que não seja o de casa, como uma caixa postal (não pesquisei preço nem regra).

**Com o Lobo Solar.** Alimenta direto e reforça a regra da fonte primária.

**O que pode dar errado.** Um erro grave achado na primeira semana vira constrangimento público, e é exatamente isso que o mecanismo promete encarar.

Notas: ousadia 4 · encaixe 5 · viabilidade 5 · circulação 4

---

### 2. Palpite Lacrado
**O Lobo publica as próprias previsões como um código lacrado e só abre o texto na data marcada, com acertos e erros contados em placar.**

**Mecanismo.**
- Ele escreve o palpite ("até 31/01/2027 o acumulado de chuva na estação do INMET em Brasília passa de tal valor"), calcula o hash SHA-256 do texto e publica só o hash, no formato placar de LED.
- Na data marcada, publica o texto original. Qualquer pessoa cola o texto numa página de verificação e vê que bate.
- O placar anual de acertos e erros fica público.

Os stories de palpite que já existem perguntam ao público. Aqui quem se arrisca é o próprio Lobo, sem poder editar depois.

**O que já existe.** Compromissos com hash aparecem na ciência, como as previsões de erupção do vulcão submarino Axial Seamount, lacradas com SHA-256 ([arXiv 2511.06128](https://arxiv.org/pdf/2511.06128)), em tutoriais de OpenTimestamps ([dev.to](https://dev.to/neuportal/how-to-prove-a-prediction-was-made-before-the-event-with-opentimestamps-4p5d)) e em discussões do LessWrong. Não encontrei ninguém fazendo isso em português, muito menos como ritual de perfil.

**Por que só ele faria.** Ele programa (a página de verificação é um fim de tarde), já tem o formato de placar e tem o rigor para errar em público sem constrangimento.

**Primeira peça.** Cinco palpites lacrados, com aberturas entre dezembro de 2026 e abril de 2027 (chuva em Brasília, fim do Brasileirão, um lançamento científico anunciado), e a página "Lacre" que confere o hash.

**Custo.** 1 hora por semana. Sem custo em dinheiro.

**Com o Lobo Solar.** Alimenta e cria um ritual anual: o dia da abertura dos lacres.

**O que pode dar errado.** Hash parece hermético, e se a lâmina não explicar em uma frase o que é um lacre digital, ninguém entende o que está vendo.

Notas: ousadia 5 · encaixe 4 · viabilidade 5 · circulação 3

---

### 3. Rodapé
**Cada carrossel ganha uma página pública com a apuração inteira: as fontes de cada afirmação, os becos sem saída e o que ficou sem confirmação.**

**Mecanismo.** A página `/rodape/047` tem as afirmações numeradas, cada uma com a fonte primária e a data de acesso. Tem também três seções que ninguém publica: "o que eu achava antes de apurar", "o que ficou de fora e por quê" e "o que não consegui confirmar". A última lâmina do carrossel traz só uma linha: "Rodapé 047: 12 fontes, 3 becos".

**O que já existe.** Projetos de dados como o Our World in Data mostram fontes, mas páginas de curiosidade no Instagram, em regra, não mostram nenhuma. Esta é uma afirmação de observação, não de censo. A novidade está nos becos e nas dúvidas, que fazem da apuração uma leitura.

**Por que só ele faria.** Ele já faz a apuração. Falta só torná-la visível, e um gerador de site estático resolve isso a partir das notas.

**Primeira peça.** Os rodapés dos dez primeiros carrosséis, publicados num site estático. O Cloudflare Pages tem plano gratuito ([limites](https://developers.cloudflare.com/pages/platform/limits)). O GitHub Pages também é gratuito para repositório público, mas o repositório ficaria exposto e precisaria de uma conta separada do pseudônimo ([limites](https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits)).

**Custo.** De 30 a 45 minutos por carrossel além da apuração que já existe, cerca de 1,5 hora por semana. Sem custo em dinheiro.

**Com o Lobo Solar.** Alimenta, e dá munição ao Vale-Errata: quem tem as fontes acha os erros.

**O que pode dar errado.** Pouca gente clica, e o rodapé torna auditável a promessa de que tudo é conferido, o que exige que tudo seja mesmo.

Notas: ousadia 3 · encaixe 5 · viabilidade 4 · circulação 3

---

### 4. Prazo de Validade
**Uma série sobre coisas que eram verdade pela melhor ciência da época e venceram, com data de fabricação, data de vencimento e o lote que ensinou.**

**Mecanismo.** É o contrário da Errata.
- A Errata trata de frase repetida sem base.
- O Prazo de Validade trata do que estava certo nos livros e foi revisto.

Cada carrossel abre com um rótulo de embalagem: fabricação (o ano em que entrou nos livros didáticos), vencimento (o artigo ou a decisão que revisou), lote (quem ensinava) e modo de conservação (o que sobrou de verdade). Exemplos a conferir em fonte primária: Plutão, descoberto em 1930 e reclassificado pela União Astronômica Internacional em 2006; e o Brontosaurus, que deixou de ser gênero válido e voltou num estudo de 2015. Saúde e nutrição ficam de fora, pela regra de saúde clínica.

**O que já existe.** O livro *The Half-Life of Facts*, de Samuel Arbesman (2012), mostra que o conhecimento tem meia-vida mensurável ([Penguin Random House](https://www.penguinrandomhouse.com/books/309825/the-half-life-of-facts-by-samuel-arbesman/)). Não encontrei edição em português nem série brasileira de "certezas vencidas".

**Por que só ele faria.** Junta ciência e rigor com dois formatos que ele já tem: o decalque (a página antiga do livro didático) e o varal do tempo (a vida útil do fato).

**Primeira peça.** Um carrossel sobre Plutão e o molde do rótulo, que vira cartaz A3 depois.

**Custo.** Cerca de 3 horas por carrossel, ocupando vagas do calendário de 150. Sem custo em dinheiro.

**Com o Lobo Solar.** Série nova, e o rótulo é um formato visual inédito no perfil.

**O que pode dar errado.** Escorregar para o discurso de que "a ciência erra"; o texto precisa deixar claro que vencer é sinal de que a ciência funciona.

Notas: ousadia 4 · encaixe 5 · viabilidade 4 · circulação 4

---

### 5. Classificados de Ontem
**Brasília contada só pelos anúncios classificados de 60 anos atrás, publicados na mesma semana do calendário, sem nenhuma notícia.**

**Mecanismo.**
- Toda semana, uma página de classificados de um jornal brasiliense de 1966 ou 1967, no formato decalque.
- O Lobo escolhe três anúncios e descobre o que aconteceu com eles: o endereço na superquadra, o produto, o preço convertido em salários mínimos da época.
- Classificado não tem tese nem partido, então a política fica de fora pela própria construção da série.

É o Reparei com sessenta anos de distância.

**O que já existe.** Em 2022 houve uma exposição de 62 capas do Correio Braziliense no CCBB ([CB](https://www.correiobraziliense.com.br/cidades-df/2022/04/amp/5003238-correio-abre-mostra-no-ccbb-que-traz-capas-historicas-do-jornal.html)). Não encontrei perfil que publique os classificados de Brasília, nem séries de "há N anos" com o jornal da cidade.

**A lacuna principal.** Não confirmei que o Correio Braziliense dos anos 1960 esteja digitalizado e aberto na Hemeroteca Digital. O Correio de 1808 é outro título, e aparece nas mesmas buscas. O próprio jornal diz ter mais de 20 mil edições no acervo ([CB, 2022](https://www.correiobraziliense.com.br/cidades-df/2022/04/5001310-juntos-desde-sempre.html)).

**Por que só ele faria.** Quem mora lá reconhece o endereço do anúncio, e o Eixo já existe como série.

**Primeira peça.** Antes de qualquer lâmina, confirmar o acervo: [Hemeroteca Digital](https://memoria.bn.gov.br/hdb/periodico.aspx), Arquivo Público do DF (hipótese) ou consulta presencial em Brasília. Com o acervo garantido, um carrossel com uma página de outubro de 1966. A reprodução de trechos com crédito parece caber no direito de citação do art. 46 da Lei 9.610/98, mas isso é hipótese a conferir.

**Custo.** De 2 a 3 horas por semana. Sem custo em dinheiro.

**Com o Lobo Solar.** Alimenta o Eixo.

**O que pode dar errado.** Se o acervo dos anos 1960 não estiver digitalizado, a série depende de idas ao arquivo e perde o ritmo semanal.

Notas: ousadia 4 · encaixe 5 · viabilidade 2 · circulação 4

---

### 6. Contagem
**O Lobo sai na rua e conta pessoalmente o que ninguém mediu em Brasília, e publica o número junto com o método e a planilha.**

**Mecanismo.** Uma pergunta por carrossel, e ninguém tem o número antes dele:
- quantos segundos de verde o pedestre tem em tal travessia da W3, medidos vinte vezes;
- quantos ipês tem uma superquadra;
- quantos pontos de ônibus de um trecho têm sombra às 15h.

As lâminas trazem a pergunta, o método, o número, a margem de erro honesta e o que a contagem não diz. A Sintonia usa números de terceiros; na Contagem, a fonte primária é ele.

**O que já existe.** Não encontrei nenhum perfil brasiliense que publique contagens próprias. Há um gancho histórico pronto: um estudo da CET-SP de 1982 registra que Brasília tinha metade dos semáforos de Juiz de Fora com o triplo da população ([CET-SP, NT 080](https://ssl.cetsp.com.br/media/20428/nt080.pdf)). Recontar hoje é um carrossel.

**Por que só ele faria.** Mora lá, treina (a contagem vira caminhada ou corrida) e programa (a planilha vira gráfico em dez minutos).

**Primeira peça.** Uma contagem que caiba numa manhã de sábado, com a planilha publicada no Rodapé.

**Custo.** De 2 a 3 horas por semana de campo, que contam também como treino. Sem custo em dinheiro.

**Com o Lobo Solar.** Alimenta o Eixo e a Sintonia, e dá ao perfil algo que nenhuma página de curiosidades tem: dado inédito.

**O que pode dar errado.** Uma contagem mal feita vira número falso com selo de verdade, por isso o método tem de ser público e modesto.

Notas: ousadia 5 · encaixe 5 · viabilidade 4 · circulação 4

---

### 7. Placar das Águas
**Um placar diário nos stories com a chuva de Brasília no período chuvoso e, a partir de maio, com a contagem de dias sem chuva, mais um pluviômetro caseiro medindo contra a estação oficial.**

**Mecanismo.** Brasília conta os dias de seca como quem conta jogo invicto. O placar de LED dos stories mostra:
- o acumulado na estação do INMET contra a média do mês;
- os dias desde a última chuva;
- a leitura do pluviômetro de garrafa PET do próprio Lobo, posicionado "em algum ponto do Plano", sem revelar onde mora.

O recorde histórico de seca era de 163 dias, em 1963, e foi superado em 04/10/2024, quando a cidade chegou a 164 dias ([SBT News](https://sbtnews.sbt.com.br/noticia/brasil/brasilia-chega-a-164-dias-sem-chuva-e-atinge-recorde-historico-de-seca); [INMET](https://portal.inmet.gov.br/noticias/distrito-federal-completa-150-dias-sem-chuvas)). A contagem final daquele ano não foi confirmada.

**O que já existe.** A imprensa local noticia os marcos, mas não encontrei nenhum contador permanente. A versão física é opcional: um ESP32 (cerca de R$ 50, [Marino Store](https://www.marinostore.com/wireless-iot/esp-wroom-32)) com um módulo de LED P10 (cerca de R$ 110, [Mercado Livre](https://produto.mercadolivre.com.br/MLB-3251490765-modulo-para-painel-led-p10-vermelho-32x16cm-hub12-interno-_JM)), os dois com data de preço incerta. Esse placar de mesa rende a imagem dos Reels. **[venda: depende da cláusula]**, se um dia virar kit.

**Por que só ele faria.** Um script pega o dado e desenha o story sozinho. É ciência do cotidiano, e é Brasília.

**Primeira peça.** O script que busca o dado do INMET e gera o story do dia. Se o INMET tem API pública estável é hipótese a conferir; a alternativa é baixar os dados da estação. Mais o pluviômetro de garrafa.

**Custo.** Depois de automatizado, cerca de 15 minutos por dia, ou 1,5 hora por semana. De R$ 0 a cerca de R$ 170 com o placar físico.

**Com o Lobo Solar.** Alimenta, e é o ritual diário que mantém os stories vivos entre um carrossel e outro.

**O que pode dar errado.** Se a fonte de dados mudar ou cair e o placar falhar três dias seguidos, o ritual morre.

Notas: ousadia 4 · encaixe 5 · viabilidade 4 · circulação 4

---

### 8. Notas de Atualização
**A história de regras, cidades e objetos contada como patch notes de videogame: versão, data, o que mudou e o bug que motivou a mudança.**

**Mecanismo.** "Futebol v1992.1. Corrigido: o goleiro podia pegar com as mãos a bola recuada com o pé por um companheiro. O recurso era explorado para gastar tempo (bug observado na Copa de 1990)." Cada lâmina é uma versão. A última sempre traz "Problemas conhecidos", com o que segue sem conserto. O formato serve às Regras do Jogo, à moeda brasileira, ao calendário gregoriano e à tabela de tipos de Pokémon.

**O que já existe.** Patch notes como sátira de notícias existem, como a conta [IRL Patch Notes](https://x.com/irl_patch_notes). Para história verificada, não encontrei. A fonte primária do futebol é oficial: a IFAB mantém todas as edições das Regras desde 1903/04 ([theifab.com](https://www.theifab.com/laws-of-the-game-documents/); [histórico](https://www.theifab.com/background/)). A data exata da regra do recuo (maio de 1992, vigente em julho) só apareceu em fonte secundária.

**Por que só ele faria.** Ele joga, programa e lê changelog todo dia. O formato é a língua materna de quem faz software.

**Primeira peça.** "Regras do Futebol: notas de atualização de 1863 a 2026", em oito lâminas, tudo tirado do acervo da IFAB.

**Custo.** Cerca de 3 horas por carrossel. Sem custo em dinheiro. Um cartaz A3 em formato de changelog fica **[venda: depende da cláusula]**.

**Com o Lobo Solar.** Série nova, e a que mais tem cara de ser compartilhada em grupo de futebol.

**O que pode dar errado.** A piada do formato cansa se virar fórmula; funciona melhor espaçada, um episódio por mês.

Notas: ousadia 4 · encaixe 5 · viabilidade 5 · circulação 5

---

### 9. Créditos Finais
**Reels sem voz em que um objeto comum ganha a rolagem de créditos de um filme: quem plantou, quem transportou, quem inventou cada peça.**

**Mecanismo.** "O Cafezinho da Rodoviária. Elenco: grão arábica (sul de Minas), açúcar (cana de São Paulo). Efeitos especiais: a máquina de espresso. Locação: Brasília." Cada crédito é conferido, e a lista completa vai para o Rodapé. A rolagem de créditos é nativa de vídeo e dispensa narração, justo o que o perfil precisa.

**O que já existe.** O ensaio "I, Pencil", de Leonard Read (1958), conta a cadeia de produção de um lápis; virou filme do CEI e ganhou variações, como "I, Chicken Sandwich", da Cato, no verão de 2026 ([Cato](https://www.cato.org/regulation/summer-2026/i-chicken-sandwich)). Esses textos defendem uma tese econômica. A versão do Lobo não defende nada: só mostra os créditos, como a série Reparei. Não encontrei o formato de créditos em perfis brasileiros.

**Por que só ele faria.** É o olhar do Bastidor aplicado ao cotidiano, e o perfil já tem a linha de Reels sem voz.

**Primeira peça.** Um Reel de 45 segundos com os créditos finais de um pão francês, e a versão em carrossel para o feed.

**Custo.** De 3 a 4 horas por peça. Sem custo em dinheiro.

**Com o Lobo Solar.** Alimenta os Reels e cria um formato visual novo.

**O que pode dar errado.** Cadeia produtiva é difícil de verificar em fonte primária, e um crédito genérico ("produtores do Paraná") esvazia o efeito.

Notas: ousadia 4 · encaixe 4 · viabilidade 4 · circulação 5

---

### 10. Encontro Marcado
**Carrosséis em parceria com outra página pequena: cada uma escreve sobre uma coisa sem ver o texto da outra, e o Lobo escreve a lâmina final que descobre o que uma sabe sobre a outra.**

**Mecanismo.** É a série "O que uma coisa sabe sobre a outra" com dois autores.
- O Lobo escolhe uma página parceira (astronomia, um esporte, cozinha).
- Cada lado escreve de três a quatro lâminas sobre a sua coisa.
- O Lobo amarra no fim.

Sai como post Collab, que aparece nos dois feeds. As regras valem para os dois lados: fonte primária e nada de página política.

**O que já existe.** O recurso Collab existe. Segundo fontes secundárias, aceita até 5 colaboradores convidados ([Buffer](https://buffer.com/resources/instagram-collab-post/); [Adobe Express, ago/2025](https://www.adobe.com/express/learn/blog/instagram-collab-posts)); a página oficial de ajuda não foi confirmada. Parceria entre perfis é comum. A cegueira mútua e a amarração final são o que torna esta diferente.

**Por que só ele faria.** A série é dele, e juntar duas coisas é o ofício que ela já exige.

**Primeira peça.** Um convite a uma página de tamanho parecido e um carrossel em parceria.

**Custo.** Cerca de 2 horas, mais a conversa com a parceira, por edição mensal. Sem custo em dinheiro.

**Com o Lobo Solar.** Divide e soma público, e é o jeito de crescer sem anúncio pago.

**O que pode dar errado.** O Lobo passa a depender da agenda e do rigor de outra pessoa, e uma parceira descuidada contamina a regra da fonte primária.

Notas: ousadia 3 · encaixe 4 · viabilidade 4 · circulação 5

---

### 11. Ponto Exato
**Carrosséis do Eixo cuja última parte só abre no lugar: uma página web libera o fato extra quando o leitor está a menos de 100 metros do ponto.**

**Mecanismo.**
- O carrossel conta algo sobre um ponto específico: um pilotis, uma tesourinha, uma banca.
- A última lâmina diz que "o resto está no ponto exato" e traz o link.
- A página usa a geolocalização do navegador e só mostra o texto perto dali.

Quem mora em Brasília vai até lá e posta o story do lugar. Quem não mora pede a um amigo. Depois de 30 dias, o texto abre para todo mundo, para não punir quem está longe. Não há placa física, porque publicidade em área pública no DF exige autorização da Administração Regional (Lei 3.035/2002, [manual da Seduh](https://www.seduh.df.gov.br/documents/8133848/9859577/manual_3035.pdf)).

**O que já existe.** Histórias com cerca geográfica existem em apps como [Echoes](https://docs.echoes.xyz/docs/creator/intro) e VoiceMap. Em Brasília, o mais próximo é o Mapa Afetivo de Brasília, que é curadoria de lugares e não abre nada ([Forbes, 2023](https://forbes.com.br/forbeslife/2023/05/tomada-por-politica-brasilia-se-mexe-para-oferecer-turismo-e-arte/)). Para não ficção dentro de um perfil, não encontrei nada.

**Por que só ele faria.** Faz páginas web, já tem o Mapa do Eixo para ligar os pontos e pode testar no local, porque mora lá.

**Primeira peça.** Um carrossel e uma página com cerca geográfica para um único ponto, testada no lugar.

**Custo.** De 1 a 2 horas por semana. Sem custo em dinheiro (página estática com JavaScript).

**Com o Lobo Solar.** Alimenta o Eixo e o Mapa do Eixo, e tira o perfil da tela.

**O que pode dar errado.** Pouca gente vai até o ponto, e quem está longe se frustra se a versão aberta depois de 30 dias não ficar clara desde a primeira lâmina.

Notas: ousadia 5 · encaixe 5 · viabilidade 4 · circulação 3

---

### 12. Frase Sem Dono
**Um buscador público de frases falsamente atribuídas em português, com veredito, fonte e o primeiro registro conhecido de cada uma.**

**Mecanismo.** Cada entrada traz:
- a frase;
- a quem atribuem (Clarice Lispector, Caio Fernando Abreu, Mario Quintana, o Einstein das correntes);
- o veredito: é dele, não é dele, é de outra pessoa ou não há registro;
- o primeiro registro encontrado e o link.

Uma caixa de busca permite colar a frase e ler o veredito. As Erratas sobre citações viram entradas, e a base cresce sozinha pelo buscador, sem anúncio.

**O que já existe.** Em inglês, o [Quote Investigator](https://en.wikipedia.org/wiki/Quote_Investigator) faz isso desde 2010, assinado com um pseudônimo, o que prova que o modelo funciona sem nome real. Em português há reportagens, como a do [Espaço do Conhecimento da UFMG](https://www.ufmg.br/espacodoconhecimento/blog-espaco/textos-apocrifos-autoria-errada-e-atribuicao-trocada/), e um selo de "autoria verificada" do Pensador ([Bem Paraná](https://www.bemparana.com.br/tecnologia/site-de-frases-em-lingua-portuguesa-aposta-em-checagem-e-lanca-selo-de-autoria-verificada/)). Não encontrei nenhum banco público dedicado.

**Por que só ele faria.** É a Errata virando ferramenta, e ele programa a busca.

**Primeira peça.** Quinze entradas, a página de busca e um carrossel sobre a frase de Clarice que não é de Clarice.

**Custo.** Cerca de 2 horas por semana, de duas a três entradas. Sem custo em dinheiro.

**Com o Lobo Solar.** Alimenta a Errata e traz público vindo de busca.

**O que pode dar errado.** Provar que alguém não disse algo é quase impossível, então o veredito "sem registro encontrado" precisa ser frequente e honesto.

Notas: ousadia 4 · encaixe 5 · viabilidade 4 · circulação 5

---

## Parte 2. Dezoito fora do Lobo Solar

### 13. Aires Diário
**O *Memorial de Aires*, de Machado de Assis, enviado por e-mail no dia exato de cada entrada do diário, a partir de 9 de janeiro de 2027.**

**Mecanismo.**
- O diário do Conselheiro Aires começa em "1888, 9 de janeiro" ([texto da obra completa, MEC](https://machado.mec.gov.br/obra-completa-lista/item/download/10_3b418d3289f560235fccf338378de5bf)) e vai até 1889.
- Cada entrada chega na caixa do leitor no mesmo dia e mês, 139 anos depois.
- O diário cobre o ano da abolição (1888) e termina em 1889, antes da Proclamação da República, segundo o estudo citado abaixo. As datas de 1888 chegam no calendário de 2027.
- Cada envio leva um rodapé curto e conferido sobre o que acontecia no Rio naquele dia.

O texto é de domínio público.

**O que já existe.** O [Dracula Daily](https://en.wikipedia.org/wiki/Dracula_Daily), de Matt Kirkland, começou em 03/05/2021 mandando o *Drácula* nas datas internas do romance. Passou de 230 mil assinantes, segundo a [Euronews de 13/02/2024](https://www.euronews.com/2024/02/13/meet-the-kirklands-the-creative-couple-getting-people-reading-classic-literature). Não encontrei nenhuma versão em português, nem ninguém mandando o *Memorial* nas datas. Em 2027 a ideia é plantar o mecanismo no último romance de Machado, o único em forma de diário.

**Por que só ele faria.** Leitor, rigoroso nas notas e capaz de automatizar o agendamento.

**Primeira peça.** A newsletter criada no Substack (gratuita, [FAQ](https://faq.substack.com/p/how-do-paid-subscriptions-on-substack)), as entradas de janeiro de 1888 agendadas com notas e um texto de apresentação.

**Ressalvas.**
- Não confirmei a data da última entrada; um estudo diz que a última anotação é "sem data" ([UFRJ](http://www.ciencialit.letras.ufrj.br/garrafa/garrafa18/memorialdeaires_marcelamedina.pdf)).
- Não confirmei se há entrada no 13 de maio. Isso se confere no texto integral antes do lançamento.

**Custo.** Cerca de 10 horas de preparação até dezembro (dividir o texto, agendar). Depois, 1 hora por semana de notas. Sem custo em dinheiro.

**Com o Lobo Solar.** Divide público leitor, e o Lobo pode anunciar. Como é texto alheio com nota própria, não fere o pseudônimo.

**O que pode dar errado.** As entradas são irregulares, com semanas sem nada, e o leitor esquece que assinou se as notas não preencherem esses vazios.

Notas: ousadia 4 · encaixe 4 · viabilidade 5 · circulação 4

---

### 14. Sinal Fraco
**Uma ficção em tempo real no Telegram: um personagem perdido no cerrado manda mensagens ao longo de dias, pede ao leitor que decida e, às vezes, que vá a um lugar real de Brasília.**

**Mecanismo.**
- As mensagens chegam em horários plausíveis: o personagem dorme, a bateria acaba, o sinal cai.
- As escolhas são feitas por botões.
- Em dois ou três momentos, ele pede ajuda presencial ("alguém consegue ir até a entrada do Parque da Cidade e me dizer o que está escrito na placa?"). Quem vai encontra a resposta numa página que só abre no local, a mesma técnica do Ponto Exato, sem mexer em nada do espaço público.

**O que já existe.** O jogo Lifeline (3 Minute Games, 2015) consagrou a ficção por mensagens com atraso real ([IF50](https://if50.substack.com/p/2015-lifeline)). O ARG brasileiro de referência é o Zona Incerta, de 2007 ([UFJF](https://www2.ufjf.br/facom/files/2013/03/Lumina16-17-LuizAdolfo.pdf)). Não encontrei ficção brasileira em tempo real por Telegram ou WhatsApp. O Telegram é a escolha certa porque a Bot API é gratuita ([core.telegram.org](https://core.telegram.org/bots/faq)), enquanto o WhatsApp cobra por mensagem de template desde 01/07/2025 ([Meta](https://developers.facebook.com/documentation/business-messaging/whatsapp/pricing)).

**Por que só ele faria.** Programa o bot, tem universos guardados de onde o personagem pode sair e conhece o cerrado.

**Primeira peça.** Uma história de três dias, com cerca de 60 mensagens e dois pontos de decisão, rodando para cinco amigos.

**Custo.**
- De 10 a 15 horas de escrita e programação por história.
- Depois, 1 hora por semana.
- Hospedar o bot num plano gratuito é hipótese a conferir.

**Com o Lobo Solar.** Nada, e é melhor assim: é ficção, com outro pseudônimo.

**O que pode dar errado.** O Telegram pode ter pouco uso no Brasil comparado ao WhatsApp (hipótese), e pedir para instalar um app novo derruba metade dos leitores.

Notas: ousadia 5 · encaixe 5 · viabilidade 3 · circulação 4

---

### 15. Conto de Cupom
**Microcontos impressos em papel térmico de cupom fiscal e mandados por carta para quem pedir. O conto desbota em alguns anos, e isso faz parte da peça.**

**Mecanismo.**
- Quem pede manda três palavras.
- Ele escreve um conto curto com elas e imprime no formato de cupom: "CUPOM NÃO FISCAL / ITEM 001 SAUDADE 1 UN / TOTAL: UMA TARDE".
- O cupom vai pelo correio.
- O papel térmico apaga com o tempo, então cada conto vem com prazo de leitura impresso no rodapé.

**O que já existe.** A Short Édition, de Grenoble, mantém mais de 650 máquinas de contos em papel térmico em 23 países ([Atlas Obscura](https://www.atlasobscura.com/articles/short-story-vending-machines)). Não encontrei presença no Brasil. A Máquina de Contos brasileira manda contos digitais, não impressos. A versão dele troca a máquina por uma pessoa: o conto é escrito para quem pediu, e não sorteado.

**Por que só ele faria.** Escreve, programa a impressora pelo computador e gosta de objetos.

**Primeira peça.** Uma impressora térmica de 58 mm (de R$ 90 a R$ 170 no [Mercado Livre](https://lista.mercadolivre.com.br/mini-impressora-portatil-bluetooth-termica-windows-58mm), preço variável), dez cupons escritos e enviados a dez conhecidos.

**Custo.** De 1 a 2 horas por semana. Cerca de R$ 120 uma vez, e R$ 2,65 mais o papel por envio. Uma assinatura mensal de cupons fica **[venda: depende da cláusula]**.

**Com o Lobo Solar.** Nada.

**O que pode dar errado.** Endereço de desconhecido e privacidade; comece só com conhecidos e sem remetente residencial.

Notas: ousadia 4 · encaixe 4 · viabilidade 5 · circulação 3

---

### 16. Clube do Volume 1
**Um encontro mensal em Brasília em que todo mundo lê o volume 1 do mesmo mangá, junto e em silêncio, e no fim vota se a série merece o volume 2.**

**Mecanismo.**
- Leitura silenciosa: 45 minutos.
- Conversa: 30 minutos.
- Voto: polegar para cima ou para baixo, e o placar acumulado vira uma tabela.

O formato resolve o problema de todo leitor de mangá, que é saber se vale começar uma série longa. E resolve o da convivência adulta: um encontro com hora para acabar e assunto garantido.

**O que já existe.** O Silent Book Club é o modelo de leitura silenciosa em grupo. Uma coluna de 16/10/2025 contou só capítulos em São Paulo, Boituva e Rio ([Tribuna de Minas](https://tribunademinas.com.br/colunas/alem-da-xicara/16-10-2025/clube-do-livro-silencioso-completa-10-anos-um-movimento-libertario-pela-leitura-livre.html?amp=1)). Não encontrei clube de mangá em Brasília. O lugar natural é a mangateca da Biblioteca Demonstrativa do Brasil, com cerca de 1,5 mil volumes doados pelo Japão em 2021 ([Jornal de Brasília](https://jornaldebrasilia.com.br/brasilia/brasilia-ganha-biblioteca-publica-de-mangas/)), o que dispensa compra.

**Por que só ele faria.** Junta mangá, Brasília e o eixo da convivência. Ele vai como pessoa, não como Lobo.

**Primeira peça.** Uma sessão com três a cinco amigos. Antes, confirmar se a biblioteca tem exemplares repetidos e se permite grupo (hipótese).

**Custo.** 3 horas por mês. Sem custo em dinheiro.

**Com o Lobo Solar.** Nada, e por escolha: é a parte da vida que não vira post.

**O que pode dar errado.** Sem vários exemplares do mesmo volume, cada um lê uma coisa e o formato desmonta.

Notas: ousadia 3 · encaixe 5 · viabilidade 5 · circulação 3

---

### 17. Candanga
**Uma fonte tipográfica gratuita desenhada a partir dos letreiros pintados à mão de Ceilândia, Taguatinga, Sobradinho e Planaltina.**

**Mecanismo.**
- Um levantamento fotográfico de letreiros de mercadinho, borracharia e lanchonete, sem gente nas fotos.
- O desenho de um alfabeto de título a partir deles.
- A publicação sob a SIL Open Font License, que permite usar, modificar e redistribuir, mas não vender a fonte sozinha ([OSI](https://opensource.org/license/ofl/)).
- Crédito aos pintores identificáveis e convite a pelo menos um deles para revisar.

A ideia é mostrar a Brasília que não é Niemeyer.

**O que já existe.** Há projetos de tipografia vernacular em vários lugares:
- Belém: o [Letras que Flutuam](https://www.brasildefato.com.br/2024/10/15/belem-tem-primeiro-espaco-de-promocao-e-preservacao-da-tipografia-de-barcos-da-amazonia), desde 2006.
- Salvador: a [Suburbana](https://cruatipos.gumroad.com/l/suburbana).
- Uberlândia: a Carretera.
- O app Edits, da Meta: a [BOTECO](https://about.fb.com/br/news/2026/09/edits-lanca-nova-tipografia-100-pintada-a-mao-por-artista-brasileiro/), de setembro de 2026.

Para Brasília e as regiões administrativas, não encontrei nada. Também não conferi se o nome "Candanga" já está em uso por outra fonte.

**Por que só ele faria.** Já desenhou um pacote de ícones, mora lá, e o levantamento vira passeio de sábado.

**Primeira peça.** Trinta letreiros fotografados numa região e as 26 maiúsculas esboçadas no FontForge, que é gratuito.

**Custo.** 3 horas por semana durante uns três meses. Sem custo em dinheiro.

**Com o Lobo Solar.** Alimenta: a fonte pode assinar as lâminas do Eixo, e o processo rende um Bastidor.

**O que pode dar errado.** Sem crédito e sem conversa com quem pinta, o projeto vira extração do trabalho alheio.

Notas: ousadia 4 · encaixe 4 · viabilidade 3 · circulação 4

---

### 18. Tesourinha
**Um jogo de quebra-cabeça de trânsito em que você atravessa o Plano Piloto sem nunca virar à esquerda, usando só tesourinhas e retornos.**

**Mecanismo.**
- Cada fase é uma viagem real ("da 308 Sul ao Conic, sem semáforo").
- A regra é a da cidade: a conversão à esquerda é substituída por laços.
- A dificuldade vem de combinar retornos, horários e mão única.

É um jogo curto, que dá para terminar num intervalo de almoço.

**O que já existe.** Não encontrei jogo sobre o trânsito de Brasília, só um jogo educativo de mobilidade do UniCEUB, de 2018 ([PDF](https://publicacoes.uniceub.br/pic/article/download/5808/4070)). Puzzles de trânsito genéricos existem aos montes. A graça aqui é a cidade real.

**Por que só ele faria.** Já fez cinco jogos curtos em Godot, e o Godot exporta para web sem royalty (licença MIT, [FAQ](https://docs.godotengine.org/en/stable/about/faq.html)).

**Primeira peça.** Cinco fases numa abstração da Asa Sul, publicadas como jogo de navegador no itch.io, onde publicar é gratuito ([itch.io](https://itch.io/docs/creators/faq)).

**Custo.** De 3 a 5 horas por semana durante um mês. Sem custo em dinheiro. A versão "pague quanto quiser" (o itch.io fica com 10% por padrão, [pagamentos](https://itch.io/docs/creators/payments)) é **[venda: depende da cláusula]**.

**Com o Lobo Solar.** Divide o público brasiliense e rende um carrossel do Eixo.

**O que pode dar errado.** É engraçado para quem mora lá e opaco para quem não mora, então as primeiras fases têm de ensinar a regra sem texto.

Notas: ousadia 4 · encaixe 5 · viabilidade 4 · circulação 4

---

### 19. Museu do Que Não Houve
**Um museu on-line de uma civilização inventada, montado com o acervo de imagens dele, em que cada peça tem ficha museológica, procedência e as dúvidas dos curadores.**

**Mecanismo.**
- Cada imagem é declarada gerada por IA e tratada como artefato: número de tombo, material, dimensões, procedência, "atribuição contestada".
- Há erratas dos curadores fictícios de uma edição do catálogo para a outra.
- O universo vem de um dos que ele guarda.

O texto da ficha carrega a peça, e a imagem é só a prova.

**O que já existe.** O [Museum of Imaginary Musical Instruments](https://imaginaryinstruments.org/about/) ganhou livro em abril de 2026. *Khazar Archeological Confabulations*, de Nimrod Astarhan, foi finalista do [Lumen Prize 2024](https://lumenprize.com/2024-finalists). *Babylonian Vision*, de Nora Al-Badri, usa IA treinada com artefatos reais. Não encontrei o acervo inteiro de uma civilização autoral com fichas. A diferença é que este museu é a porta de entrada para um universo que já é dele.

**Por que só ele faria.** Tem um acervo grande de imagens e universos guardados, escreve e monta a página.

**Primeira peça.** A "Sala 1", com 12 peças fichadas, um mapa e um catálogo em PDF.

**Custo.** 2 horas por semana, uma a duas peças. Sem custo em dinheiro. Impressões pela Colab55, onde o cadastro é gratuito e o artista define o preço ([Colab55](https://www.colab55.com/about)), ficam **[venda: depende da cláusula]**.

**Com o Lobo Solar.** Nada. A brincadeira com o rigor museológico é parente do método do Lobo, mas fica em outro pseudônimo.

**O que pode dar errado.** Imagem de IA tem cara de IA; a curadoria precisa ser dura e descartar nove de cada dez.

Notas: ousadia 4 · encaixe 5 · viabilidade 4 · circulação 3

---

### 20. Súmula
**Um gerador que faz da pelada da semana uma página de jornal esportivo: placar, escalação, gols e uma crônica curta escrita a partir dos dados.**

**Mecanismo.**
- Durante ou depois do jogo, alguém marca os gols e as assistências num formulário.
- O gerador devolve uma capa 1080x1350 no estilo dos jornais esportivos antigos, com manchete, seleção da rodada e uma crônica de três parágrafos que ele revisa.
- A capa vai para o grupo dos amigos toda semana.

Em um ano, o grupo tem o próprio almanaque.

**O que já existe.** Apps de pelada resolvem sorteio, presença, pagamento e estatística: [Futebol Society](https://mwm.ai/apps/futebol-society/6743960382), [Pelada+](https://apps.apple.com/BR/app/id1637292238), [Sorteio de Times](https://apps.apple.com/BR/app/id6478060840), e o Appito, com câmeras e estatística ([Baguete](https://www.baguete.com.br/noticias/appito-capta-r-27-milhoes)). Não encontrei nenhum que gere crônica ou página de jornal.

**Por que só ele faria.** Joga toda semana, desenvolve para Android, usa IA e faz design.

**Primeira peça.** Um formulário web e um modelo que gera a página da pelada desta semana.

**Custo.** Cerca de 10 horas de construção. Depois, 1 hora por semana. Sem custo em dinheiro. Um app público fica **[venda: depende da cláusula]**.

**Com o Lobo Solar.** Nada. É privado e serve à convivência.

**O que pode dar errado.** Tem amigo que não quer ser avaliado; a nota individual fica opcional e a crônica, gentil.

Notas: ousadia 4 · encaixe 5 · viabilidade 5 · circulação 3

---

### 21. Prancheta [depois de janeiro]
**Uma página de Instagram que explica o que não é futebol com prancheta tática: como formigas defendem o formigueiro, como um cardume faz pressão alta.**

**Mecanismo.**
- Setas, linhas de passe e numeração aplicadas a biologia, trânsito, física e cozinha.
- Toda peça tem a lâmina "onde a analogia quebra", que é onde mora o rigor.
- Os posts podem estrear em janeiro já com estoque.

**O que já existe.** A metáfora aparece de vez em quando em texto, como a "escalação" de um ministério ([IstoÉ](https://istoe.com.br/time-de-temer-ainda-esta-desentrosado)), e há ferramentas grátis de prancheta, como o [Renderfoot](https://www.renderfoot.com/pt/tactical-board). Não encontrei uma página dedicada.

**Por que só ele faria.** Joga, vê futebol, gosta de ciência e desenha.

**Primeira peça.** Três posts prontos, sobre formigas, abelhas e o voo em V das aves, guardados para a estreia em janeiro.

**Custo.** 3 horas por semana. Sem custo em dinheiro.

**Com o Lobo Solar.** Divide público e permite divulgação cruzada.

**O que pode dar errado.** A analogia força a ciência, e a lâmina "onde quebra" não pode faltar nunca.

Notas: ousadia 4 · encaixe 4 · viabilidade 4 · circulação 5

---

### 22. Dicionário de Barulhos
**Um dicionário das onomatopeias de mangá em português: o que ゴゴゴ quer dizer e como as edições brasileiras traduziram, adaptaram ou deixaram cada uma.**

**Mecanismo.** Cada verbete traz:
- o kana e a romanização;
- o sentido e a cena de origem;
- lado a lado, a escolha da edição brasileira: manteve em japonês com legenda, trocou por onomatopeia nossa ou apagou.

A busca é por som ("a do JoJo") ou por kana. Começa como site e, **[depois de janeiro]**, pode ganhar página própria.

**O que já existe.** Em inglês há o dicionário de SFX da JADED Network. Em português, só trabalhos acadêmicos isolados: um artigo da TradTerm/USP de 2010 ([USP](https://revistas.usp.br/tradterm/article/view/46322)) e monografias sobre a edição brasileira de One Piece e sobre Vagabond. Não encontrei nada que compare as editoras.

**Por que só ele faria.** Lê mangá, tem as edições em casa e programa a busca.

**Primeira peça.** Vinte verbetes de uma única série, com as comparações tiradas dos volumes que ele já tem.

**Custo.** 2 horas por semana. Sem custo em dinheiro. A reprodução de quadros para comentário parece caber no direito de citação, mas isso é hipótese a conferir.

**Com o Lobo Solar.** Vizinho do Bastidor; divide público.

**O que pode dar errado.** Exige japonês suficiente para não errar o sentido; comece pelas onomatopeias mais documentadas e marque o que for inferência.

Notas: ousadia 4 · encaixe 4 · viabilidade 4 · circulação 4

---

### 23. Ouvido Candango
**Um mapa sonoro do DF: gravações de um minuto em lugares de Brasília, sem voz em primeiro plano, cada uma com local, hora e clima.**

**Mecanismo.** O Eixão fechado no domingo, o vento na Esplanada, as cigarras de setembro, a Rodoviária às 6h, a primeira chuva no telhado. Um minuto por ponto, sempre com o mesmo protocolo. As gravações vão para uma página própria e para o [radio aporee ::: maps](https://aporee.org/mobile), um mapa sonoro mundial.

**O que já existe.** Há cartografias sonoras no Porto, em Dourados ([UFU](https://seer.ufu.br/index.php/olharesetrilhas/article/view/35045)) e no Recôncavo baiano (UFRB). Para Brasília, não encontrei nenhuma.

**Por que só ele faria.** A regra de não usar a própria voz vira linguagem: aqui ninguém fala. E as caminhadas de treino viram coleta.

**Primeira peça.** Dez gravações num domingo e uma página com o mapa.

**Custo.** 1 hora por semana. Celular basta; um protetor de vento barato ajuda (preço não pesquisado).

**Com o Lobo Solar.** Alimenta: as gravações viram trilha original dos Reels do Eixo.

**O que pode dar errado.** Celular com vento grava ruído, e a coleta exige paciência para voltar ao mesmo ponto em outro dia.

Notas: ousadia 3 · encaixe 4 · viabilidade 5 · circulação 2

---

### 24. Seca e Chuva
**Um brinquedo web de areia caindo em que o cerrado vive o ano: seca, fogo, primeira chuva, ipê florindo e o capim voltando depois da queimada.**

**Mecanismo.**
- É um simulador de partículas com regras do cerrado: plantas de raiz profunda sobrevivem ao fogo, o fogo corre mais com umidade baixa, a semente espera a chuva.
- Um controle de calendário passa os meses.
- Nada de pontuação: é para mexer e olhar.

**O que já existe.** Há brinquedos genéricos de areia caindo, como o [Sandboxels](https://w3id.org/r74n/sandboxels) e o [Sand Game JS](https://github.com/Hartrik/sand-game-js), de código aberto. Sobre o cerrado, só um simulador científico de fogo, o FISC ([Agência FAPESP](https://agencia.fapesp.br/novo-sistema-e-capaz-de-prever-incendios-no-cerrado-em-tempo-praticamente-real/41868)). Brinquedo, não encontrei.

**Por que só ele faria.** Programa, gosta de ciência e vive a seca de Brasília todo ano.

**Primeira peça.** Seis elementos (terra, capim, árvore, fogo, água e semente) numa página web.

**Custo.** 3 horas por semana durante umas seis semanas. Sem custo em dinheiro.

**Com o Lobo Solar.** Parente do Placar das Águas, e a captura de tela dá Reels sem voz.

**O que pode dar errado.** Uma simulação simplificada pode ensinar errado, então ela vem acompanhada de uma nota curta sobre o que é licença poética.

Notas: ousadia 4 · encaixe 4 · viabilidade 4 · circulação 3

---

### 25. Pictomangá
**Um mangá de luta contado só com pictogramas de sinalização pública: o bonequinho do banheiro contra o bonequinho da saída de emergência.**

**Mecanismo.**
- Segue os momentos clássicos do shonen: rival, treino, poder novo, sacrifício, revanche.
- Usa a composição de página de mangá e nenhum texto, só onomatopeias.
- Por construção, não tem cara de IA nem rosto de ninguém.

Sai como capítulos em carrossel, numa página própria **[depois de janeiro]**, ou antes disso no itch.io e na web.

**O que já existe.** *Book from the Ground*, de Xu Bing (MIT Press, 2018), conta o dia de um funcionário de escritório só com ícones ([Penguin Random House](https://www.penguinrandomhouse.com/books/658615/book-from-the-ground-by-bing-xu/)), e Austin Kleon escreveu sobre quadrinhos com as regras do Isotype ([2008](https://austinkleon.com/2008/02/14/making-signs-making-comics/)). Não encontrei um shonen. Os 50 símbolos AIGA/DOT são de uso livre ([AIGA](https://aiga.org/resources/symbol-signs)), mas o melhor é desenhar os próprios.

**Por que só ele faria.** Lê shonen e já desenhou 40 ícones. É a mesma mão.

**Primeira peça.** Um capítulo 1 de oito páginas.

**Custo.** 3 horas por semana. Sem custo em dinheiro.

**Com o Lobo Solar.** Nada. Pode render no máximo uma aparição no Peso.

**O que pode dar errado.** Sem rosto e sem texto, a emoção depende só da composição, e as primeiras páginas podem sair frias.

Notas: ousadia 5 · encaixe 4 · viabilidade 4 · circulação 4

---

### 26. Rasura
**Um editor de texto para Windows que nunca apaga: o que você corta fica riscado, e o texto sai como lâminas 1080x1350 ou como vídeo da escrita sendo feita.**

**Mecanismo.** O Backspace risca em vez de apagar. Há três exportações:
- o texto final;
- o manuscrito com as rasuras, na estética do Lobo;
- o replay da escrita, em vídeo, para Reels sem voz.

A primeira usuária é a produção dele mesmo.

**O que já existe.** O plugin [Permanent Ink](https://community.obsidian.md/plugins/permanent-ink), do Obsidian, risca em vez de apagar. O Draftback faz replay de Google Docs e pode ser descontinuado ([Originality.ai](https://originality.ai/blog/draftback-chrome-extension-alternatives)). Ferramentas como Typewriter geram vídeo de digitação, mas a partir de um texto colado, não do histórico real. Não encontrei nenhuma que exporte carrossel.

**Por que só ele faria.** Desenvolve para Windows, e a rasura é formato dele. A Microsoft Store passou a aceitar conta de desenvolvedor individual sem taxa em 10/09/2025 ([Windows Developer Blog](https://blogs.windows.com/windowsdeveloper/2025/09/10/free-developer-registration-for-individual-developers-on-microsoft-store/)).

**Primeira peça.** Um editor mínimo que risca e exporta PNG no tamanho do carrossel.

**Custo.** 2 horas por semana. Sem custo em dinheiro. A versão na loja fica **[venda: depende da cláusula]**.

**Com o Lobo Solar.** Alimenta: vira a ferramenta de produção e rende um Bastidor.

**O que pode dar errado.** Ficar como ferramenta só dele, sem uso fora; mesmo assim, já se paga no Lobo.

Notas: ousadia 3 · encaixe 5 · viabilidade 4 · circulação 3

---

### 27. No Prelo
**Um catálogo de editora com vinte lançamentos dele que ainda não existem, com capa, sinopse e ficha, e os leitores votam qual sai primeiro.**

**Mecanismo.**
- Os universos e as marcas guardados viram um catálogo impresso e on-line, no estilo dos catálogos de editora antigos.
- Cada título tem capa, sinopse de orelha, número de páginas previsto e um trecho de meia página.
- O mais votado até uma data marcada é feito de verdade.

O catálogo tira o acervo da gaveta sem obrigar a terminar tudo, e a votação é um jeito de conseguir público que ainda não existe.

**O que já existe.** *Rejected Books*, de Graham Johnson e Rob Hibbert, é um catálogo de capas de livros que nunca vão sair, mas é humor e não promete nada ([Avid Reader](https://avidreader.com.au/p/rejected-books-the-most-unpublishable-books-of-all-time)). A Invisible Library cataloga livros que só existem dentro de outros livros, e há o precedente borgiano das capas inventadas ([John Coulthart](https://johncoulthart.com/feuilleton/tag/mark-roberts)). Não encontrei um catálogo autoral com votação que obrigue o autor a cumprir.

**Por que só ele faria.** É o único que tem esses vinte universos, e o design de capa ele faz.

**Primeira peça.** Oito títulos com capa e sinopse num PDF de catálogo, mandados a vinte pessoas com a cédula de voto.

**Custo.** 2 horas por semana durante um mês. Sem custo em dinheiro.

**Com o Lobo Solar.** Nada, ou uma menção na newsletter.

**O que pode dar errado.** O título vencedor pode ser o que ele menos quer fazer, então só entra no catálogo o que ele aceitaria escrever.

Notas: ousadia 5 · encaixe 5 · viabilidade 4 · circulação 4

---

### 28. Protocolo
**Um romance contado só por documentos de uma repartição fantástica de Brasília, entregue como um processo em pasta de papel pardo, com carimbos, despachos e um anexo que não devia estar ali.**

**Mecanismo.**
- O leitor recebe o processo nº 0001 do Departamento de Nuvens: ofícios, despachos, um "cumpra-se", um memorando que contradiz o anterior.
- A trama se monta pela ordem dos carimbos, até que um pedido absurdo (fechar o céu para manutenção) começa a ser atendido.
- Há também uma versão em PDF.

Brasília é a capital do papel timbrado, e qualquer brasiliense reconhece o gênero.

**O que já existe.** Romances em documentos e objetos existem, como *S.*, de J. J. Abrams e Doug Dorst (2013), que vem com encartes; não pesquisei mais a fundo. Não encontrei um processo administrativo como forma de romance brasileiro.

**Por que só ele faria.** Constrói mundos, desenha documento e mora na cidade do protocolo.

**Primeira peça.** Doze documentos, um exemplar montado à mão e entregue a três amigos.

**Custo.** 3 horas por semana. De R$ 30 a R$ 60 por exemplar físico, entre cópias, pasta e carimbo (estimativa, hipótese). A tiragem paga fica **[venda: depende da cláusula]**.

**Com o Lobo Solar.** Nada.

**O que pode dar errado.** Se o emprego dele for num órgão público, a sátira burocrática pode encostar nele, então a repartição tem de ser claramente fantástica e sem semelhança com nenhuma real.

Notas: ousadia 5 · encaixe 4 · viabilidade 3 · circulação 4

---

### 29. Cemitério da Jump
**Um cemitério na web para as séries canceladas da Weekly Shonen Jump: cada lápide traz o número de capítulos, as semanas de vida e, de epitáfio, a última fala publicada.**

**Mecanismo.**
- As lápides ficam enfileiradas por ano.
- Há filtros como "morreu antes do capítulo 20".
- A busca é pelo nome do autor, para seguir quem voltou com outra série.

É o lado de baixo do sucesso no shonen, que quase ninguém olha.

**O que já existe.** Não encontrei uma base pública formal. Há listas de fãs no MyAnimeList, de [2012 a 2017](https://myanimelist.net/stacks/23420) e de [2018 a 2023](https://myanimelist.net/stacks/23421). Em 2025, a revista cancelou 9 séries e encerrou 3 naturalmente, segundo o [ComicBook.com](https://comicbook.com/anime/news/shonen-jump-cancels-yet-another-series-in-2025-nearing-double-digits-this-year/); uma matéria posterior do mesmo site fala em 10. O cancelamento mais rápido atribuído, *Chagecha* (2009, oito capítulos), só aparece em fórum e precisa ser conferido.

**Por que só ele faria.** Junta mangá, dado e web, e conversa direto com a tese da série Peso.

**Primeira peça.** As lápides de 2025, cada uma com fonte, numa página.

**Custo.** 2 horas por semana. Sem custo em dinheiro.

**Com o Lobo Solar.** Alimenta o Peso, que ganha um carrossel sobre o cemitério.

**O que pode dar errado.** Os dados de fã têm erro, então cada lápide precisa citar o índice da própria revista.

Notas: ousadia 4 · encaixe 5 · viabilidade 5 · circulação 4

---

### 30. Os Prédios Falam [depois de janeiro]
**Tirinhas de quatro quadros feitas com fotos dele, em que os prédios de Brasília conversam entre si e as pessoas nunca aparecem.**

**Mecanismo.**
- O formato é o yonkoma, com fotos de arquitetura e balões saindo dos edifícios.
- Cada prédio tem personalidade fixa: a Torre de TV é vaidosa (230 metros desde 1967, segundo o [Jornal de Brasília](https://jornaldebrasilia.com.br/brasilia/tbt-do-alto-da-torre-de-tv-uma-brasilia-monumental/)), a Rodoviária está sempre cansada, o bloco da superquadra é fofoqueiro.
- Os prédios do governo ficam de fora, para não abrir a porta da política.

**O que já existe.** A busca não achou nada parecido. Isso não descarta memes avulsos; não procurei dentro do Instagram.

**Por que só ele faria.** Fotografa Brasília, lê yonkoma e escreve humor sem tese.

**Primeira peça.** Seis tiras prontas para a estreia em janeiro.

**Custo.** 2 horas por semana. Sem custo em dinheiro.

**Com o Lobo Solar.** Divide o público brasiliense do Eixo.

**O que pode dar errado.** Depende de piada interna, e quem nunca esteve em Brasília pode não rir.

Notas: ousadia 4 · encaixe 4 · viabilidade 5 · circulação 4

---

## As cinco para fazer primeiro

1. **Vale-Errata (1).** O Lobo estreia em 15/10, e esta é a única ideia que rende mais se anunciada no primeiro dia. Custa uma noite de design e alguns selos, e coloca a regra da fonte primária à prova em público, que é o que vai fazer o perfil ser lembrado.
2. **Palpite Lacrado (2).** Custo zero, uma página de verificação que se programa num fim de tarde, e nada parecido em português. Os primeiros lacres abrem antes dos 30, então o ritual chega completo a abril.
3. **Aires Diário (13).** Tem data fixa: a primeira entrada é em 9 de janeiro, e a preparação precisa acontecer em novembro e dezembro. Depois roda quase sozinho e circula fora do Instagram, sem esperar janeiro.
4. **Contagem (6).** É a única ideia que dá ao Lobo dado inédito, e o trabalho de campo é também treino e cidade. Um carrossel dessa série vale por três de curiosidade.
5. **Notas de Atualização (8).** É a de maior circulação com o menor custo, e a fonte oficial já está organizada (o acervo da IFAB). É a que leva o Lobo para os grupos de futebol.

## Três mais bonitas do que úteis, e que valem mesmo assim

- **Conto de Cupom (15).** Um conto feito para uma pessoa, em papel que apaga. Não cresce, não escala e não precisa.
- **Ouvido Candango (23).** Um arquivo de como Brasília soava em 2026. Daqui a vinte anos vai valer mais do que hoje, e de quebra dá trilha aos Reels sem voz.
- **Seca e Chuva (24).** Um brinquedo para olhar o cerrado queimar e voltar. Ensina pouco e consola muito, e cabe no "direito ao que não serve para nada".

## As descartadas mais tentadoras

- **Superquadra.** Um construtor de cidade com as regras de tombamento do Plano Piloto: seis pavimentos sobre pilotis nas superquadras 100, 200 e 300 ([Portaria Iphan 166/2016](https://seduh.df.gov.br/documents/8133848/9916732/05Z_Portaria_n_166_de_11_de_maio_de_2016.pdf)). É lindo, mas o escopo não cabe em 10 a 15 horas, e o Tesourinha faz o mesmo truque menor.
- **Só Lá.** Ficção geolocalizada por Brasília. Perdeu para o Ponto Exato, que usa a mesma técnica dentro do Lobo, e apps como Echoes e VoiceMap já fazem a versão de ficção.
- **A Brasília que não foi.** Visualizar os 25 projetos derrotados do concurso de 1957. Já existem a exposição "Outra Brasília Nunca Mais", com 3D dos finalistas ([Agência Brasil, 2021](https://agenciabrasil.ebc.com.br/geral/noticia/2021-11/exposicao-mostra-como-seria-brasilia-desenhada-por-outros-arquitetos)), e o "Invisible Brasilias", no Google Arts & Culture.
- **Achômetro.** O chute dos seguidores contra o número real, desenhado na plateia de 100 cabeças. Fica perto demais dos stories de palpite que já existem e da pesquisa Perigos da Percepção, da Ipsos ([Ipsos](https://www.ipsos.com/pt-br/node/365081)).
- **Falta Um.** Um mapa dos campos públicos do DF com um mural de "falta um jogador". O Appito já deixa tornar o jogo público para completar vagas, e o mapa sozinho é útil, mas não é ousado.
- **Rodapé na Wikipédia.** Levar cada apuração para os artigos sobre Brasília. Esbarra na regra contra pesquisa inédita ([WP:NPI](https://pt.wikipedia.org/wiki/Wikip%C3%A9dia:Nada_de_pesquisa_in%C3%A9dita)) e no conflito de interesse, e não deixa marca do Lobo.
- **Contos de Miyazawa Kenji em português.** Domínio público e muito bonitos, mas sem japonês fluente seria tradução de tradução apoiada em IA, o que fere o rigor que sustenta todo o resto.
