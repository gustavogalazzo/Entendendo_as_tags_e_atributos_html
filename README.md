<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Entendendo as tags HTML</title>
  </head>
  <body>
    <!--TITULO-->
    <h1 id="inicio">Entendendo as tags e os atributos do HTML</h1>
    <hr />
    <!--UTILIZANDO LINKS,LISTAS E ID -->
    <h2>Indice</h2>
    <ul>
      <li><a href="#h1-h6">Entendendo as tags &lt;h1&gt; até &lt;h6&gt;</a></li>
      <li><a href="#p">A tag &lt;p&gt;</a></li>
      <li><a href="#mark">A tag &lt;mark&gt; ou marcador</a></li>
      <li><a href="#small">Uma tag pequena (&lt;small&gt;)</a></li>
      <li><a href="#i">Tag de enfase</a></li>
      <li><a href="#u">Tag para marcar um erro ortografico</a></li>
      <li><a href="#strong">Como deixar o seu texto em negrito!</a></li>
      <li><a href="#ulol">Listas ordenadas e não ordenadas</a></li>
      <li><a href="#a">A tag de link</a></li>
      <li><a href="#hr">&lt;hr&gt; para que serve?</a></li>
      <li><a href="#supsub">Como utilizar as tags de sobrescrito e subescrito?</a></li>
      <li><a href="#block">Citações no HTML</a></li>
      <li><a href="#font">A tag &lt;font&gt; foi descontinuada?</a></li>
      <li><a href="#del">Um texto com uma parte excluída</a></li>
      <li><a href="#abbr">Tag de abreviação</a></li>
      <li><a href="#link">Links de referencia</a></li>
    </ul>
    <hr />
    <!--UTILIZANDO AS TAGS H1 AO H6-->
    <h2 id="h1-h6">Entendendo as tags &lt;h1&gt; até &lt;h6&gt;</h2>
    <small><a href="#inicio">(voltar)</a></small>
    <p>
      As tags <strong><i>&lt;h1&gt;</i></strong> até o
      <strong><i>&lt;h6&gt;</i></strong> são usadas para definir os titulos do
      HTML. Sendo <strong><i>&lt;h1&gt;</i></strong> que define o titulo mais
      importante de seu site e o <strong><i>&lt;h6&gt;</i></strong> o titulo
      menos importante! 
      <p><strong>Nota:</strong>Use apenas um <strong><i>&lt;h1&gt;</i></strong> por
      página, pois ele deve representar o título/assunto principal de toda a
      página. Além disso, não pule os níveis de título, comece com
      <strong><i>&lt;h1&gt;</i></strong
      >, depois use <strong><i>&lt;h2&gt;</i></strong> e assim por diante.</p>
    </p>
    <p>
      <strong><i>Exemplo no HTML:</i></strong><br><br>
      <strong><i>&lt;h1&gt;</i></strong>Titulo 1<strong><i>&lt;/h1&gt;</i></strong><br>
      <strong><i>&lt;h2&gt;</i></strong>Titulo 2<strong><i>&lt;/h2&gt;</i></strong><br>
      <strong><i>&lt;h3&gt;</i></strong>Titulo 3<strong><i>&lt;/h3&gt;</i></strong><br>
      <strong><i>&lt;h4&gt;</i></strong>Titulo 4<strong><i>&lt;/h4&gt;</i></strong><br>
      <strong><i>&lt;h5&gt;</i></strong>Titulo 5<strong><i>&lt;/h5&gt;</i></strong><br>
      <strong><i>&lt;h6&gt;</i></strong>Titulo 6<strong><i>&lt;/h6&gt;</i></strong><br>
      <p><strong><i>Resultado:</i></strong></p>
      <h1>Titulo 1</h1>
      <h2>Titulo 2</h2>
      <h3>Titulo 3</h3>
      <h4>Titulo 4</h4>
      <h5>Titulo 5</h5>
      <h6>Titulo 6</h6>
    </p>
    <hr>
    <!--UTILIZANDO A TAG P-->
    <h2 id="p">A tag &lt;p&gt;</h2>
    <small><a href="#inicio">(voltar)</a></small>
    <p>A tag <strong><i>&lt;p&gt;</i></strong> define um paragrafo. Os navegadores o adicionam automaticamente uma única linha em branco antes e depois de cada <strong><i>&lt;p&gt;</i></strong> elemento. </p>       <p><strong>Dica:</strong> Uitlize o CSS para estilizar os seus paragrafos!</p>
    <p><strong><i>Exemplo no HTML:</i></strong></p>
    <strong><i>&lt;p&gt;</i></strong>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum voluptatibus quos eum vitae debitis porro expedita placeat, nesciunt eius quisquam est officia esse tempore delectus eaque pariatur, ut quam iste. <strong><i>&lt;/p&gt;</i></strong>
    <p><strong><i>Resultado:</i></strong></p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Est ad atque harum, ipsum dolorem blanditiis sit veniam magnam porro voluptate quibusdam! Tenetur dolore ducimus accusamus accusantium, ipsum harum molestias consequuntur.</p>
    <hr>
    <!--UTILIZANDO MARCADOR-->
    <h2 id="mark">A tag &lt;mark&gt; ou marcador</h2>
    <small><a href="#inicio">(voltar)</a></small>
    <p>A tag <strong><i>&lt;mark&gt;</i></strong> define o texto no qual você quer marcar ou ser destaque dele.</p>
    <p><strong><i>Exemplo no HTML:</i></strong></p>
    <strong><i>&lt;p&gt;</i></strong>Não se esqueça de comprar o livro do <strong><i>&lt;mark&gt;</i></strong>Percy Jackson<strong><i>&lt;/mark&gt;</i></strong>hoje.<strong><i>&lt;/p&gt;</i></strong><br>
    <p><strong><i>Resultado:</i></strong></p>
    <p>Não se esqueça de comprar o livro do <mark>Percy Jackson</mark> hoje.</p>
    <hr>
    <!--UTILIZANDO A TAG SMALL-->
    <h2 id="small">Uma tag pequena (&lt;small&gt;)</h2>
    <small><a href="#inicio">(voltar)</a></small>
    <p>A tag <strong><i>&lt;small&gt;</i></strong> define textos menores (como direitos autorais e outros comentários secundários).</p>
    <p><strong>Dica:</strong> Esta tag não está obsoleta, mas é possível obter um efeito mais rico (ou igual) com CSS.</p>
    <p><strong><i>Exemplo no HTML:</i></strong></p>
    <strong><i>&lt;p&gt;</i></strong>Este é um texto normal<strong><i>&lt;/p&gt;</i></strong><br><br>
    <strong><i>&lt;p&gt;</i></strong><strong><i>&lt;small&gt;</i></strong> Este é um texto menor<strong><i>&lt;/small&gt;</i></strong><strong><i>&lt;/p&gt;</i></strong>
    <p><strong><i>Resultado:</i></strong></p>
    <p>Este é um texto normal</p>
    <p><small>Este é um texto menor.</small></p>
    <hr>
    <!--UTILIZANDO A TAG DE ENFASE-->
    <h2 id="i">Tag de enfase</h2>
    <small><a href="#inicio">(voltar)</a></small>
    <p>A tag <strong><i>&lt;i&gt;</i></strong> define uma parte do texto com uma voz ou humor alternativo. O conteúdo interno normalmente é exibido em itálico .</p>
    <p>A tag <strong><i>&lt;i&gt;</i></strong> é frequentemente usada para indicar um termo técnico, uma frase de outro idioma, um pensamento, o nome de um navio, etc.</p>
    <p>Utilize o <strong><i>&lt;i&gt;</i></strong> somente quando não houver um elemento semântico mais apropriado, como:</p>
    <ul>
      <li><strong><i>&lt;em&gt;</i></strong> (texto enfatizado)</li>
      <li><strong><i>&lt;strong&gt;</i></strong> (texto importante)</li>
      <li><strong><i>&lt;mark&gt;</i></strong> (texto marcado/destacado)</li>
      <li><strong><i>&lt;cite&gt;</i></strong> (o título de uma obra)</li>
      <li><strong><i>&lt;dfn&gt;</i></strong> (um termo de definição)</li>
    </ul>
    <p><strong><i>Exemplo no HTML:</i></strong></p>
    <strong><i>&lt;i&gt;</i></strong>Este texto está em italico!<strong><i>&lt;/i&gt;</i></strong>
    <p><strong><i>Resultado:</i></strong></p>
    <i>Este texto está em italico!</i>
    <hr>
    <!--UTILIZANDO A TAG U-->
    <h2 id="u">Tag para marcar um erro ortografico</h2>
    <small><a href="#inicio">(voltar)</a></small>
    <p>A tag <strong><i>&lt;u&gt;</i></strong> representa algum texto desarticulado e com estilo diferente do texto normal, como palavras com erros ortográficos ou nomes próprios em texto chinês. O conteúdo interno normalmente é exibido com um sublinhado. Você pode alterar isso com CSS.</p>
    <p><strong>Dica:</strong> Evite usar a tag <strong><i>&lt;u&gt;</i></strong> elemento onde possa ser confundido com um hiperlink!</p>
    <p><strong><i>Exemplo no HTML:</i></strong></p>
    <strong><i>&lt;u&gt;</i></strong>Este é um texto com erro de digiação<strong><i>&lt;/u&gt;</i></strong>
    <p><strong><i>Resultado:</i></strong></p>
    <p>Este é um texto <u>com erro de digiação</u>.</p>
    <hr>
    <!--UTILIZANDO A TAG STRONG-->
    <h2 id="strong">Como deixar o seu texto em negrito!</h2>
    <small><a href="#inicio">(voltar)</a></small>
    <p>A tag <strong><i>&lt;strong&gt;</i></strong> é usada para definir textos de grande importância. O conteúdo interno normalmente é exibido em <strong>negrito</strong>. </p>
    <p><strong>Dica:</strong> Use a tag <strong><i>&lt;b&gt;</i></strong> para especificar texto em negrito sem qualquer importância extra!</p>
    <p><strong><i>Exemplo no HTML:</i></strong></p>
    <strong><i>&lt;strong&gt;</i></strong>Este é um texto importante!<strong><i>&lt;/strong&gt;</i></strong>
    <p><strong><i>Resultado:</i></strong></p>
    <p><strong>Este é um texto importante!</strong></p>
    <hr>
    <!--UTILIZANDO LISTAS OL E UL-->
    <h2 id="ulol">Listas ordenadas e não ordenadas</h2>
    <small><a href="#inicio">(voltar)</a></small>
    <p>A tag <strong><i>&lt;ul&gt;</i></strong> define uma lista não ordenada (com marcadores). Já a A tag <strong><i>&lt;ol&gt;</i></strong> define uma lista ordenada. Uma lista ordenada pode ser numérica ou alfabética.</p>
    <p>Junto as tags <strong><i>&lt;ul&gt;</i></strong> e <strong><i>&lt;ol&gt;</i></strong> utlize a tag <strong><i>&lt;li&gt;</i></strong> para criar listas não ordenadas.</p>
    <p><strong><i>Exemplo no HTML:</i></strong></p>
    <strong><i>&lt;ul&gt;</i></strong><br>
    <strong><i>&lt;li&gt;</i></strong>Coffee<strong><i>&lt;/li&gt;</i></strong><br>
    <strong><i>&lt;li&gt;</i></strong>Tea<strong><i>&lt;/li&gt;</i></strong><br>
    <strong><i>&lt;li&gt;</i></strong>Milk<strong><i>&lt;/li&gt;</i></strong><br>
    <strong><i>&lt;/ul&gt;</i></strong><br>
    <p>É a mesma coisa para a lista ordenada!</p>
    <strong><i>&lt;ol&gt;</i></strong><br>
    <strong><i>&lt;li&gt;</i></strong>Coffee<strong><i>&lt;/li&gt;</i></strong><br>
    <strong><i>&lt;li&gt;</i></strong>Tea<strong><i>&lt;/li&gt;</i></strong><br>
    <strong><i>&lt;li&gt;</i></strong>Milk<strong><i>&lt;/li&gt;</i></strong><br>
    <strong><i>&lt;/ol&gt;</i></strong><br>
    <p><strong><i>Resultado com a lista não ordenada e ordenada:</i></strong></p>
    
    <ul>
      <li>Coffee</li>
      <li>Tea</li>
      <li>Milk</li>
    </ul>
    <ol>
      <li>Coffee</li>
      <li>Tea</li>
      <li>Milk</li>
    </ol>
    <hr>
    <!--UTILIZANDO A TAG DE HYPERLINK <A>-->
      <h2 id="a">A tag de link</h2>
      <small><a href="#inicio">(voltar)</a></small>
      <p>A tag <strong><i>&lt;a&gt;</i></strong> define um hiperlink, que é usado para vincular de uma página a outra. O atributo mais importante da tag <strong><i>&lt;a&gt;</i></strong> é o elemento <strong><i>" href "</i></strong> atributo, que indica o destino do link. Por padrão, os links aparecerão da seguinte forma em todos os navegadores:</p>
      <ul>
        <li>Um link não visitado está sublinhado e azul</li>
        <li>Um link visitado está sublinhado e roxo</li>
        <li>Um link ativo está sublinhado e vermelho</li>
      </ul>
      <strong>Dica:</strong>
      <p>Se a tag <strong><i>&lt;a&gt;</i></strong> não tiver nenhum <strong><i>" href "</i></strong> atributo, ela será apenas um espaço reservado para um hiperlink.</p>
      <p>Há tambem outros atributos que você pode usar dentro dessa tag! Recomendo visitar o seguinte link para mais informações:</p>
      <a href="https://www.w3schools.com/tags/tag_a.asp" target="_blank">https://www.w3schools.com/tags/tag_a.asp</a>
      <hr>
      <!--UTILIZANDO A TAG HR-->
      <h2 id="hr">&lt;hr&gt; para que serve</h2>
      <small><a href="#inicio">(voltar)</a></small>
      <p>A tag <strong><i>&lt;hr&gt;</i></strong> define uma quebra temática em uma página HTML (por exemplo, uma mudança de tópico). O <strong><i>&lt;hr&gt;</i></strong> é mais frequentemente exibido como uma regra horizontal usada para separar o conteúdo (ou definir uma alteração) em uma página HTML.</p>
      <hr>
      <!--UTILIZANDO AS TAGS DE SOBRESCRITO E SUBESCRITO-->
      <h2 id="supsub">Como utilizar as tags de sobrescrito e subescrito?</h2>
      <small><a href="#inicio">(voltar)</a></small>
      <p>A tag <strong><i>&lt;sup&gt;</i></strong> define texto sobrescrito. O texto sobrescrito aparece meio caractere acima da linha normal e às vezes é renderizado em uma fonte menor. Texto sobrescrito pode ser usado para notas de rodapé, como WWW <sup>[1]</sup> . Já a tag <strong><i>&lt;sup&gt;</i></strong> define o texto subscrito. O texto subscrito aparece meio caractere abaixo da linha normal e às vezes é renderizado em uma fonte menor. O texto subscrito pode ser usado para fórmulas químicas, como H <sub>2</sub> O.</p>
      <p><strong><i>Exemplo no HTML:</i></strong></p>
      Este texto contem um <strong><i>&lt;sup&gt;</i></strong>sobrescrito<strong><i>&lt;/sup&gt;</i></strong> nele. <br><br>
      Este texto contem um <strong><i>&lt;sub&gt;</i></strong>subrescrito<strong><i>&lt;/sub&gt;</i></strong> nele.
      <p><strong><i>Resultado no <strong><i>&lt;sup&gt;</i></strong> :</i></strong></p>
      <p>Este texto contem um <sup>sobrescrito</sup> nele.</p>
      <p><strong><i>Resultado no <strong><i>&lt;sub&gt;</i></strong> :</i></strong></p>
      <p>Este texto contem um <sub>subrescrito</sub> nele.</p>
      <hr>
      <!--UTILIZANDO CITAÇÕES NO HTML-->
      <h2 id="block">Citações no HTML</h2>
      <small><a href="#inicio">(voltar)</a></small>
      <p>A tag <strong><i>&lt;blockquote&gt;</i></strong> especifica uma seção citada de outra fonte. Os navegadores geralmente recuam <strong><i>&lt;blockquote&gt;</i></strong> elementos.</p>
      <p><strong>Dica:</strong></p>
      <p>Use o <strong><i>&lt;q&gt;</i></strong> para cotações inline (curtas).</p>
      <p><strong><i>Exemplo no HTML:</i></strong></p>
      <strong><i>&lt;blockquote&gt;</i></strong> Há 50 anos que a WWF protege o futuro da natureza. A principal organização de conservação do mundo, a WWF trabalha em 100 países e é apoiada por 1,2 milhões de membros nos Estados Unidos e perto de 5 milhões em todo o mundo.<strong><i>&lt;/blockquote&gt;</i></strong>
      <p><strong><i>Resultado:</i></strong></p>
      <blockquote>
        Há 50 anos que a WWF protege o futuro da natureza. A principal organização de conservação do mundo, a WWF trabalha em 100 países e é apoiada por 1,2 milhões de membros nos Estados Unidos e perto de 5 milhões em todo o mundo.
      </blockquote>
      <hr>
      <!--TAG FONT-->
      <h2 id="font">A tag &lt;font&gt; foi descontinuada?</h2>
      <small><a href="#inicio">(voltar)</a></small>
      <p>A tag <strong><i>&lt;font&gt;</i></strong> foi usada no HTML 4 para especificar o tipo da fonte, o tamanho da fonte e a cor do texto. Infelizmente não é compativel mais com o HTML5 versão atual que se encontra. Ao invez disso você pode usar a tag style no CSS para definir a cor do texto, o tamanho da fonte e a fonte que havera no seu texto!. Para mais informações visite este site! : </p>
      <a href="https://www.w3schools.com/tags/tag_font.asp">https://www.w3schools.com/tags/tag_font.asp</a>
      <hr>
      <!--UTILIZANDO A TAG DEL-->
      <h2 id="del">Um texto com uma parte excluida?</h2>
      <small><a href="#inicio">(voltar)</a></small>
      <p>A tag <strong><i>&lt;del&gt;</i></strong> define o texto que foi excluído de um documento. Os navegadores geralmente traçam uma linha no texto excluído.</p>
      <p><strong>Dica:</strong></p>
      observe também a tag <strong><i>&lt;ins&gt;</i></strong> para marcar o texto inserido.
      <p><strong><i>Exemplo no HTML:</i></strong></p>
      Minha cor favorita é <strong><i>&lt;del&gt;</i></strong>amarelo<strong><i>&lt;/del&gt;</i></strong> <strong><i>&lt;ins&gt;</i></strong>azul<strong><i>&lt;/ins&gt;</i></strong>!
      <p><strong><i>Resultado:</i></strong></p>
      <p>Minha cor favorita é <del>amarelo</del> <ins>azul</ins>!</p>
      <hr>
      <!--UTILIZANDO A TAG ABBR-->
      <h2 id="abbr">Um texto com abreviação</h2>
      <small><a href="#inicio">(voltar)</a></small>
      <p>A tag <strong><i>&lt;abbr&gt;</i></strong> define uma abreviatura ou um acrônimo, como "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".</p>
      <p><strong>Dica:</strong></p>
      Use o atributo global para mostrar a descrição da abreviatura/acrônimo ao passar o mouse sobre o elemento.<strong><i>&lt;title&gt;</i></strong>
      <p><strong><i>Exemplo no HTML:</i></strong></p>
      The <strong><i>&lt;abbr</i></strong> <i>title</i> = "World Health Organization"<strong><i>&gt;</i></strong>WHO<strong><i>&lt;/abbr&GT;</i></strong> was founded in 1948.
      <p><strong><i>Resultado:</i></strong></p>
      The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.
      <hr>
      <h2 id="link">Links de referencia</h2>
      <small><a href="#inicio">(voltar)</a></small>
      <ul>
        <li><a href="https://www.w3schools.com/" target="_blank">https://www.w3schools.com/</a></li>
        <li><a href="https://developer.mozilla.org/pt-BR/" target="_blank">https://developer.mozilla.org/pt-BR/</a></li>
        <li><a href="https://www.youtube.com/@CursoemVideo" target="_blank">https://www.youtube.com/@CursoemVideo</a></li>
      </ul>
      <br><br>
      <p style="text-align: center;">Todos os direitos reservados&copy;</p>
  </body>
</html>
