# Romani Lav - rekurso linguistiko ye rromanés
Léxico cigano da variedade linguística romani calón implementado em um sistema de busca com informações de classe gramatical, categoria morfossintática e contraparte em português brasileiro.

Inspirado em "Jakob Wiedner - Data base of Romani Dialects (2022)", o recurso linguístico Romani Lav foi desenvolvido pela linguista cigano-brasileira <a href="https://lisanju.github.io">Elisa Anju Lardapide</a> com o intuito de disponibilizar em português brasileiro um recurso acessível sobre a língua cigana romani calón.

## Índice

1. [Sobre o database](https://github.com/Lisanju/romani-lav/tree/main#sobre-o-database);
2. [Metodologia para o desenvolvimento do Romani Lav](https://github.com/Lisanju/romani-lav/tree/main#metodologia-para-o-desenvolvimento-do-romani-lav);<br>
   2.1 [Tratamento do database](https://github.com/Lisanju/romani-lav/tree/main#tratamento-do-database);<br>
   2.2 [Implementação do site](https://github.com/Lisanju/romani-lav/tree/main#implementação-do-site);
4. [Classes gramaticais](https://github.com/Lisanju/romani-lav/tree/main#classes-gramaticais);
5. [Categorias morfossintáticas](https://github.com/Lisanju/romani-lav/tree/main#categorias-morfossintáticas);
6. [Alfabeto e sons](https://github.com/Lisanju/romani-lav/tree/main#alfabeto-e-sons).
7. [Fontes e referências](https://github.com/Lisanju/romani-lav/tree/main#fontes-e-referências)

## Sobre o database
Existem diversas línguas chamadas de romani. Apesar de suas diferenças estruturais, elas possuem em comum o fato de carregarem um valor simbólico-cultural da etnia rhomá, conhecida popularmente como etnia cigana.

Este recurso linguístico conta apenas com dados das línguas romani-ibéricas, também chamadas de romani calón. Tratam-se de variedades do romani influenciadas pelo espanhol e português europeus. Ainda assim, pelo fluxo migratório dos rhomá, é possível encontrar na língua romani calón influências do espanhol latino e do português brasileiro.

Na seção "Fontes e referências" deste repositório, é possível ver quais fontes foram utilizadas para a coleta dos dados da língua romani calón. Não foi feita nenhuma modificação sobre os dados coletados e, além disso, todos os dados derivam de fontes acadêmicas e/ou avaliadas por falantes nativos.

O database conta com os seguintes dados:
- Palavra em romani calón;
- Contraparte em português brasileiro da palavra em romani calón;
- Classe gramatical da palavra em romani calón;
- Informação morfossintática da palavra em romani calón.

## Metodologia para o desenvolvimento do Romani Lav

### Tratamento do database

### Implementação do site
Após o tratamento do database, iniciei a etapa de implementação do site. A ideia é que o Romani Lav possa ser facilmente acessado em qualquer dispositivo que esteja conectado na Internet. Por isso, um website me pareceu ser a melhor escolha de implementação. Trata-se de um site simples, em que as tecnologias utilizadas foram: HTML, CSS, JavaScript, JSON, Bootstrap e GitHub Pages.

O site é composto por uma única página (index.html) de estrutura simples, que contém blocos para o logo do site, para a barra de pesquisa e para o rodapé. O arquivo do site, além da página "index.html", é subdividido em outras 4 pastas: data, styles, scripts e imgs:

- A pasta data contém o database "r_data.json" traduzido com os dados da língua okinawana;
- A pasta styles contém as folhas de estilo "style.css" e "bootstrap.min.css", em que "style.css" modifica diretamente o design da página "index.html" e "bootstrap.min.css" retorna um modelo de licença Bootstrap;
- A pasta scripts contém os scripts "script.js" e "bootstrap.bundle.min.js", em que "boostrap.bundle.min.js" retorna um modelo de script de licença Bootstrap e "script.js" possui a programação em JavaScript para interação do usuário com o site, gerenciamento da palavra digitada pelo usuário, busca pela palavra na base de dados "r_data.json" e modificação da página "index.html" para a exibição das informações sobre a palavra pesquisada;
- A pasta imgs contém todos os arquivos de imagens utilizados pelo site em formato .png.

Com a estruturação e programação do site finalizadas, hospedei o site através da plataforma GitHub Pages, que oferece um serviço de hosting gratuito e consideravelmente seguro quando em comparação com outros serviços.

Essa foi a metodologia utilizada para o desenvolvimento do Romani Lav. Note que o projeto ainda está em desenvolvimento. Aceito qualquer sugestão que puderem oferecer, mas peço que, por favor, enviem as sugestões pelo e-mail "lisanju.contato@gmail.com", escrevendo no título do e-mail "Romani Lav Sugestão". Evite utilizar os chats do Instagram, WhatsApp, Discord, Twitter ou qualquer outro serviço que não seja pelo e-mail. Trata-se de uma questão de conveniência e organização.

## Classes gramaticais

## Categorias morfossintáticas

## Alfabeto e sons
O sistema de escrita utilizado pelo Romani Lav é de base alfabética, no entanto, como todo sistema de escrita, sua grafia não captura com exatidão o modo de articulação e produção dos sons do romani calón. Por isso, a seguir disponibilizo tabelas com as grafias no alfabeto romani e suas pronúncias no alfabeto fonético internacional (IPA).

**Vogais do romani calón**
<table>
  <tr>
    <th>Grafia</th>
    <th>Pronúncia</th>
  </tr>
  <tr>
    <td>A a</td>
    <td>[a]</td>
  </tr>
  <tr>
    <td>E e</td>
    <td>[e̝/ə]</td>
  </tr>
  <tr>
    <td>I i</td>
    <td>[i/i̯]</td>
  </tr>
  <tr>
    <td>O o</td>
    <td>[o̞]</td>
  </tr>
  <tr>
    <td>U u</td>
    <td>[u/u̯]</td>
  </tr>
</table>

**Consoantes do romani calón**
<table>
  <tr>
    <th>Grafia</th>
    <th>Pronúncia</th>
  </tr>
  <tr>
    <td>B b</td>
    <td>[b]</td>
  </tr>
  <tr>
    <td>C c</td>
    <td>[k/ts]</td>
  </tr>
  <tr>
    <td>D d</td>
    <td>[d/dʒ]</td>
  </tr>
  <tr>
    <td>F f</td>
    <td>[f]</td>
  </tr>
  <tr>
    <td>G g</td>
    <td>[g/x]</td>
  </tr>
  <tr>
    <td>H h</td>
    <td>[h]</td>
  </tr>
  <tr>
    <td>J j</td>
    <td>[x]</td>
  </tr>
  <tr>
    <td>K k</td>
    <td>[k]</td>
  </tr>
  <tr>
    <td>L l</td>
    <td>[l]</td>
  </tr>
  <tr>
    <td>M m</td>
    <td>[m]</td>
  </tr>
  <tr>
    <td>N n</td>
    <td>[n]</td>
  </tr>
  <tr>
    <td>P p</td>
    <td>[p]</td>
  </tr>
  <tr>
    <td>Q q</td>
    <td>[k]</td>
  </tr>
  <tr>
    <td>R r</td>
    <td>[ɾ/r]</td>
  </tr>
  <tr>
    <td>S s</td>
    <td>[s]</td>
  </tr>
  <tr>
    <td>T t</td>
    <td>[t/tʃ]</td>
  </tr>
  <tr>
    <td>V v</td>
    <td>[v/b]</td>
  </tr>
  <tr>
    <td>Y y</td>
    <td>[j]</td>
  </tr>
  <tr>
    <td>Z z</td>
    <td>[dʒ]</td>
  </tr>
  <tr>
    <td>Ch ch</td>
    <td>[tʃ]</td>
  </tr>
  <tr>
    <td>Gu gu</td>
    <td>[g]</td>
  </tr>
  <tr>
    <td>Ll ll</td>
    <td>[ʎ/lj]</td>
  </tr>
  <tr>
    <td>Ñ ñ</td>
    <td>[ɲ/nj]</td>
  </tr>
  <tr>
    <td>Qu qu</td>
    <td>[k]</td>
  </tr>
  <tr>
    <td>Rr rr</td>
    <td>[r]</td>
  </tr>
  <tr>
    <td>Sh sh</td>
    <td>[ʃ]</td>
  </tr>
</table>

**Observações**
- Antes de "i" e "e", a pronúncia das seguintes letras são "c = [ʦ]", "d = [ʤ]", "g = [x]", e "t = [ʧ]";
- A letra "e" é pronunciada como [ə] em sílabas sem estresse;
- As consoantes "gu" e "qu" são usadas apenas antes de "i" ou "e";
- Em sílabas sem estresse ou antes de vogais, as letras "i" e "u" são pronunciadas como [i̯] e [u̯];
- A letra "k" é usada apenas em palavras emprestadas de outras línguas ou em nomes próprios.

## Fontes e referências

AYER, Simon. Omniglot: writing systems and languages of the world. 2023.

MAYO, Francisco. El Gitanismo: historia, costumbres y dialecto de los gitanos. Madrid: 1870.

QUINDALÉ, Francisco. Un Diccionario Caló-Castellano. Madrid: 1870.
