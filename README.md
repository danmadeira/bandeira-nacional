## Bandeira Nacional

Desenho da bandeira do Brasil regulamentado pela Lei n° 5.700, de 1° de setembro de 1971, incluindo a alteração dada pela Lei n° 8.421, de 11 de maio de 1992. As cores seguem a paleta prioritária de cores do sistema de identidade visual do Ministério da Defesa, que consta no Manual de Identidade Visual do Ministério da Defesa, na edição de janeiro de 2015.

### Medidas oficiais:

Art. 5° A feitura da Bandeira Nacional obedecerá às seguintes regras (Anexo nº 2):

I - Para cálculo das dimensões, tomar-se-á por base a largura desejada, dividindo-se esta em 14 (quatorze) partes iguais. Cada uma das partes será considerada uma medida ou módulo.

II - O comprimento será de vinte módulos (20M).

III - A distância dos vértices do losango amarelo ao quadro externo será de um módulo e sete décimos (1,7M).

IV - O círculo azul no meio do losango amarelo terá o raio de três módulos e meio (3,5M).

V - O centro dos arcos da faixa branca estará dois módulos (2M) à esquerda do ponto do encontro do prolongamento do diâmetro vertical do círculo com a base do quadro externo (ponto C indicado no Anexo no 2).

VI - O raio do arco inferior da faixa branca será de oito módulos (8M); o raio do arco superior da faixa branca será de oito módulos e meio (8,5M).

VII - A largura da faixa branca será de meio módulo (0,5M).

VIII - As letras da legenda Ordem e Progresso serão escritas em côr verde. Serão colocadas no meio da faixa branca, ficando, para cima e para baixo, um espaço igual em branco. A letra P ficará sôbre o diâmetro vertical do círculo. A distribuição das demais letras far-se-á conforme a indicação do Anexo no 2. As letras da palavra Ordem e da palavra Progresso terão um têrço de módulo (0,33M) de altura. A largura dessas letras será de três décimos de módulo (0,30M). A altura da letra da conjunção E será de três décimos de módulo (0,30M). A largura dessa letra será de um quarto de módulo (0,25M).

IX - As estrêlas serão de 5 (cinco) dimensões: de primeira, segunda, terceira, quarta e quinta grandezas. Devem ser traçadas dentro de círculos cujos diâmetros são: de três décimos de módulo (0,30M) para as de primeira grandeza; de um quarto de módulo (0,25M) para as de segunda grandeza; de um quinto de módulo (0,20M) para as de terceira grandeza; de um sétimo de módulo (0,14M) para as de quarta grandeza; e de um décimo de módulo (0,10M) para a de quinta grandeza.

X - As duas faces devem ser exatamente iguais, com a faixa branca inclinada da esquerda para a direita (do observador que olha a faixa de frente), sendo vedado fazer uma face como avêsso da outra.

### Observações:

A Lei que define a Bandeira Nacional não especifica as tonalidades das cores, a Lei apenas indica o verde, amarelo, azul e branco. Entretanto, o Manual de Identidade Visual (do Ministério da Defesa) possui valores RGB para cada cor da paleta prioritária de cores do sistema de identidade visual, que foi inspirado nas cores da Bandeira Nacional.

- Verde: rgb(0,112,36)
- Amarelo: rgb(247,198,0)
- Azul: rgb(33,42,116)

A Lei também não define a posição exata das estrelas no círculo azul, apenas diz que: "As constelações que figuram na Bandeira Nacional correspondem ao aspecto do céu, na cidade do Rio de Janeiro, às 8 horas e 30 minutos do dia 15 de novembro de 1889 (doze horas siderais) e devem ser consideradas como vistas por um observador situado fora da esfera celeste.". Porém, o arquivo anexo na Lei possui um desenho modular da Bandeira Nacional, com um quadriculado preenchendo o círculo. As posições das estrelas são estipuladas por este quadriculado.

#### Coordenadas das Estrelas:

A Bandeira Nacional utiliza estrelas de cinco pontas para representar os estados da federação. O presente arquivo SVG, constrói cada estrela a partir das coordenadas dos cinco vértices. Os pentagramas são dimensionados de acordo com os diâmetros dos círculos das cinco grandezas regulamentadas na Lei.

Uma estrela de cinco pontas traçada dentro de um círculo imaginário, tem seus vértices seccionando a circunferência em cinco partes iguais (2π/5 radianos ou 360°/5 = 72 graus). Para uma estrela "em pé", cada vértice está posicionado nos ângulos 54°, 126°, 198°, 270° e 342°, seguindo o sentido horário (característica da linguagem SVG) a partir do 0° na direita do círculo.

O arquivo [coordenadas.pdf](src/coordenadas.pdf) contém a imagem do círculo azul da Bandeira Nacional, fornecida pela Lei em seu anexo, e a planilha do cálculo das coordenadas dos cinco vértices, de cada uma das 27 estrelas. O quadriculado do círculo foi acrescido por réguas (em vermelho) para fracionar cada quadrícula e assim estipular as posições das estrelas, a partir do centro (ponto azul), com um pouco mais de precisão. Observa-se que, por causa da má qualidade da digitalização do documento anexo, o quadriculado apresenta-se bastante distorcido, assim, cada régua foi dimensionada de acordo com o tamanho da quadrícula.

Após a definição das posições x,y do centro das estrelas, os valores destas coordenadas no quadriculado do círculo azul são primeiramente corrigidos para o plano 2000x1400 da bandeira (cx,cy). Com estes novos valores, os cinco vértices de cada estrela são calculados, pela conversão de coordenadas polares para cartesianas, e somados pelos respectivos valores cx,cy.

#### Fonte das letras da legenda Ordem e Progresso:

Ainda não há um consenso sobre qual fonte tipográfica utilizar na legenda Ordem e Progresso. A Lei apenas regulamenta para que as letras tenham 0,33M de altura e 0,30M de largura (e 0,30M e 0,25M para a conjunção E). Então, a fonte "Verdana" está sendo adotada provisoriamente.

### A Bandeira Nacional:

![Bandeira Nacional](img/Bandeira_do_Brasil.svg?raw=true)

### Referências:

- Brasil, Presidência da República. Lei nº 5.700, de 1º de setembro de 1971. Seção II Art. 5º. Disponível em: <http://www.planalto.gov.br/ccivil_03/leis/l5700.htm>

- Brasil, Presidência da República. Decreto nº 70.274/1972, de 9 de março de 1972. Disponível em: <http://www.planalto.gov.br/ccivil_03/decreto/D70274.htm>

- Brasil, Presidência da República. Lei n° 8.421, de 11 de maio de 1992. Anexo nº 2. Disponível em: <http://www.planalto.gov.br/ccivil_03/leis/L8421.htm>

- Eisenberg, J. D.; Bellamy-Royds, A. SVG Essentials, Second Edition. O'Reilly, 2015.

- Ministério da Defesa. Manual de Identidade Visual. Janeiro, 2015. Disponível em: <https://www.defesa.gov.br/arquivos/lai/institucional/identidade_visual/defesa_manual_de_identidade_visual.pdf>

- Scalable Vector Graphics (SVG) 1.1 (Second Edition), W3C Recommendation 16 August 2011. Disponível em: <https://www.w3.org/TR/SVG11/>

- Stover, C.; Weisstein, E. W. Polar Coordinates. MathWorld, A Wolfram Web Resource. Disponível em: <https://mathworld.wolfram.com/PolarCoordinates.html>
