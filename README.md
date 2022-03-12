# Socorro HTML !!!

* ## Historias e conceitos, e suas evoluções

  * apresentação das normas WWW

* ## Sobre HTMLl, semântica, significados hiper-textos.(curso em video Gustavo Guanabara)

  * HyperText Markup Language (HTML)"Linguagem de Marcação de Hipertexto" é uma linguagem de marcação  utilizada na construção de páginas na Web. Documentos HTML podem ser  interpretados por navegadores. A tecnologia é fruto da junção entre os  padrões HyTime e SGML. https://pt.wikipedia.org/wiki/HTML

* ## Apresentação das ferramentas

  * Visual Studio
  * Olá mundo... bla bla bla

* ## Imagens.

  * tipos e formatos
  * tamanho e peso
  * edição e preparação
  * orientação sobre peso da paginas e seus componentes.

* ## head abas.

  * PT-BR
  * meta charset UTF-8 ou hexas.
  * five icon, icones das abas
    * link rel="shortcut icon" href="imagens/favicon.ico" type="image/x-icon"
  * Title

* ## body ou corpo da página.(interminável)

  * títulos e hierarquias

    * H1
      * h2
        * ...	
          * h6

  * Parágrafos

    * p

  * Quebra de linha

    * br

  * Linha de separação

    * hr

  * símbolos emotion, sinais especiais: 

    * ® © ™ € £ ¥ ¢ Δ ↑🖖 🤓

  * explicações de tags que precisam de fechamentos e outras não.

  * como funciona o algoritmo de buscas e suas preferências orgânicas. 

  * exercícios de criar perfil de contato de redes sociais

    * Contate-me

      /Facebook:

      /Instagran: 

       /gmail:

      /Likedin:

      /Github:

      /Twitter

  * Diferença entre HTML anteriores e HTML5

    * semântica e atualização
    * Obsolescências de tag sem significado
    * interação ao CSS nas questões de designer
    * possibilidade ao JVscript e outras.
    * atualização semânticas 
      * itálico 
      * negrito
      * sublinhado
      * comentário
      * inclusivo e excluído
      * subrescrito o e sobrescrito

  * #  Outras formatações

    ## Código-fonte

    o comando `document.getElementbyId('')` é escrito em linguagem JavaScript.

    ## Código-fonte / pre formatado

    Use tag <pre > pre depois a tag <code > digite o codigoe depois feche as tags ok? 

    ```
        num int(imput('Digite um número'))
        if num % 2 == 0:
            print(f' O número {num} é PAR') I
        else:
            print(f 'o número {num} é Ímpar')
        print('Fim do programa')
           
       
    ```

    ##  Citações simples

    * Como dizia o pai de uma amigo: O computador é um burro muito rapido.

    ##  Citações completas

    ## listas e suas listagens

    * ol, ul, li

    * ordenadas, numeradas, alfabetizadas, e n numeradas

    * ```
      ul type="disc" 
      ol type="A"
      ol type="A" start="5
      ul type="square
      ```

    ## Download

    * Interno no servidor client (user)

    * ```
      <a href="Livro/01 - História da Internet.pdf">Baixando o livro PDF</a>
      ```

    * Externo, fora, ou na weeb

    * ```
      <a href="Livro/Livro.rar"download="livro.rar"type="application/rar">Pdf compactado em zip</a>
      ```

    * l

* ## Imagens em css

  * picture imagens ajustaveis

    * Aqui estudamos sobre imagens que se ajustam ao tamanho de acordo com a necessidade, para adequarem a smarts desktops.

    * ```
      <picture>
      	<source media="(max-width: 750px)" srcset="Imagens/foto-p.png" type="image/png">
      	<source media="(max-width: 1050px)" srcset="Imagens/foto-m.png" type="image/png">
      	<img src="Imagens/foto-g.png" alt="imagem flexivel">
      </picture>	
      ```

* ## Músicas na weeb

  * Dê preferencia para arquivos de midia em audio para "mpeg (mp3), ou ogg" 

  * ```
    <audio preload="metadata" autoplay controls loop> <!-- lopp fará ele repetir-->
            <source src="midia/03. Boom Boom Pow (RMX).mp3" type="audio/mpeg">
    ```

  * Não se esqueça de deixar um paragrafo, esboçando uma menssagem acaso o audio não executa. 

* ## Vídeos na weeb

  * 

  * ```
    <h1>Inserindo videos hospedados localmente</h1>
        <p> Este video está hosédado no meu próprio servidor</p>
        <video src="midia/meu-video.ogv" width="500" controls></video>
    
    ```

  * A orientação dada sobre videos hospedados em servidores como youtube ou vimeo, compartilhar/incorporar então copia e cola o codigo-diretório veja abaixo:

  * ```
    <iframe title="vimeo-player" src="https://player.vimeo.com/video/32296221?h=573acd6471" width="640" height="360" frameborder="0" allowfullscreen></iframe>	
    ```

* # Pausado 

* para estudos
