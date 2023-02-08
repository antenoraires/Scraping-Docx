<h2>Scraping Docx</h2>
<p>Este projeto consiste em uma aplicação de exemplo que demonstra como extrair dados de arquivos ".docx" (formato de arquivo do Microsoft Word) utilizando Python.</p>
<h2>Requisitos</h2>
<ul>
  <li>python-docx</li>
  <li>lxml</li>
</ul>
<h2>Instalação</h2>
<ol>
  <li>Clone este repositório para sua máquina local
  <pre><code>git clone https://github.com/antenoraires/Scraping-Docx.git</code></pre>
  </li>
  <li>Instale as dependências necessárias
  <pre><code>pip install -r requirements.txt</code></pre>
  </li>
</ol>
<h2>Detalhes</h2>
<p>Para Salvar os dados de um arquivo ".docx", basta executar o seguinte código:</p>
<pre><code>for ato in atos_originarios:
    result_doc.add_heading("Ato Originário")
    result_doc.add_paragraph(ato["ato_originario"])
    result_doc.add_heading("O QUE RECOMENDA")
    result_doc.add_paragraph(ato["recomendacoes"])
result_doc.add_page_break()
result_doc.add_heading("Arquivos Analisados")</code></pre>
<h2>Detalhamento</h2>
<ul>
  <li>for ato in atos_originarios: - Este é um loop que percorre uma lista de objetos "ato_originario". Cada objeto é uma representação de um "ato originário" em questão.</li>
  <li>result_doc.add_heading("Ato Originário") - Adiciona um cabeçalho (título) ao documento de saída com o texto "Ato Originário".</li>
  <li>result_doc.add_paragraph(ato["ato_originario"]) - Adiciona um parágrafo ao documento de saída com o texto especificado na chave "ato_originario" do objeto "ato".</li>
  <li>result_doc.add_heading("O QUE A COAUD RECOMENDA") - Adiciona um cabeçalho (título) ao documento de saída com o texto "O QUE A COAUD RECOMENDA".</li>
  <li>result_doc.add_paragraph(ato["recomendacoes"]) - Adiciona um parágrafo ao documento de saída com o texto especificado na chave "recomendacoes" do objeto "ato".</li>
  <li>result_doc.add_page_break() - Adiciona uma quebra de página ao documento de saída.</li>
  <li>result_doc.add_heading("Arquivos Analisados") - Adiciona um cabeçalho (título) ao documento de saída com o texto "Arquivos Analisados".</li>
</ul>

<h2>Contribuição</h2>
<p>Se você deseja contribuir para este projeto, siga as seguintes etapas:</p>
<ol>
  <li>Fork este repositório</li>
  <li>Crie uma nova branch (`git checkout -b feature/nova-funcionalidade`)</li>
  <li>Adicione suas alterações (`git add .`)</li>
  <li>Comite suas alterações (`git commit -m "Adicionando nova funcionalidade"`)</li>
  <li>Faça o push para a branch (`git push origin feature/nova-funcionalidade`)</li>
  <li>Crie uma nova solicitação de pull</li>
</ol>
<h2>Licença</h2>
<p>Este projeto está licenciado sob a licença MIT. Veja o arquivo <a href="LICENSE">LICENSE</a> para mais informações.</p>
