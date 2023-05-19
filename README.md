# Tag iframe HTML
A tag iframe é um elemento HTML que permite incorporar conteúdo de outros documentos ou páginas da web em uma página. Essa tag é especialmente útil quando você deseja exibir um vídeo, um mapa interativo ou outro tipo de conteúdo externo em seu site.
## Como usar a tag iframe

Para usar a tag iframe, você precisa fornecer a URL do documento ou página que deseja incorporar. Aqui está um exemplo básico de como usar a tag iframe:


![Capturar_2023_05_18_16_51_51_831](https://github.com/andersoncode55/IFRAMES-HTML/assets/61977421/2896f3d3-2d40-42ed-99a2-e3f996e8c3d2)<br>



<iframe src="https://www.example.com"></iframe><br>


Neste exemplo, o atributo src define a URL do documento externo que você deseja incorporar. Quando a página é renderizada no navegador, o conteúdo do documento externo será exibido dentro da área definida pelo elemento iframe.
<hr>

## Atributos adicionais da tag iframe
A tag iframe suporta vários atributos adicionais que permitem personalizar e controlar o comportamento do conteúdo incorporado. Aqui estão alguns dos atributos mais comumente usados:<br>
<ul>
	<li>width e height: Especificam a largura e altura do <iframe>, respectivamente. Você pode definir valores em pixels ou porcentagem.</li>
  <li>frameborder: Define se uma borda deve ser exibida ao redor do <iframe>. Um valor de 0 significa que nenhuma borda será exibida.</li>
  <li>scrolling: Especifica se uma barra de rolagem deve ser exibida para permitir a navegação dentro do <iframe>. Os valores possíveis são yes, no ou auto.</li>
  <li>allowfullscreen: Permite que o conteúdo dentro do <iframe> seja exibido em tela cheia quando ativado.</li>
  <li>sandbox: Define um ambiente de execução restrito para o conteúdo do <iframe>, fornecendo uma camada adicional de segurança.</li>

</ul>
<hr>


# Considerações de segurança
É importante observar que o uso da tag iframe apresenta riscos potenciais de segurança, especialmente quando incorpora conteúdo de fontes externas. É recomendável verificar a origem e a segurança do conteúdo que você está incorporando, especialmente se for proveniente de fontes desconhecidas.

Também é importante observar que alguns sites podem bloquear a incorporação de seu conteúdo usando restrições de política de segurança, como o cabeçalho HTTP X-Frame-Options. Nesses casos, o conteúdo não será exibido corretamente dentro do iframe.
<hr>

# Conclusão
A tag iframe é uma ferramenta poderosa para incorporar conteúdo externo em suas páginas da web. Ela permite que você exiba documentos, páginas, vídeos e outros tipos de conteúdo de maneira conveniente. No entanto, é necessário ter cuidado ao usar a tag iframe e garantir que o conteúdo incorporado seja seguro e confiável. Ao considerar as considerações de segurança e usar os atributos adequados, você pode aproveitar ao máximo a tag iframe para fornecer uma experiência rica e interativa aos seus usuários.














