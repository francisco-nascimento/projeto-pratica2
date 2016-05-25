<h4>Passo a Passo Git</h4>

<h6>Submeter arquivos para um repositório
<p><b>Caso 1: Não produziu nada, vai clonar o repositório para iniciar os trabalhos</b></p>
<ol>
<li>Direcionar para a pasta onde serão colocados os arquivos do repositório
<pre>cd nome-pasta</pre>
</li>
<li>Clonar o repositório remoto para a pasta local <br />
    <pre>git clone URL</pre></li>
<li>Configurar dados do usuário<br/>
<pre>git config --global user.name SeuNome<br/>
git config --global user.email seuemail-usado-no-github@abc.com <br /> </pre> 
     </li>
<li>Marcar os arquivos novos para commit<br />
    <pre>git add src/* </pre></li>
<li>Finalizar o pacote de envio dos arquivos marcados<br />
    <pre>git commit -m ‘Mensagem’ </pre></li>
<li>Se existir alguma alteração nova no repositório, será necessário fazer o merge antes:<br />
    <pre>git pull origin master</pre> </li>
<li>Por fim, submeter as suas alterações:<br />
    <pre>git push origin master</pre></li>
</ol>

<p><b>Caso 2: Já criou arquivos e quer submeter a um repositório existente</b></p>
<ol>
<li>Direcionar para a pasta do projeto
<pre>cd nome-pasta</pre>
</li>
<li>Inicializar o repositório local na pasta raiz do projeto <br />
    <pre>git init</pre></li>
<li>Configurar dados do usuário<br/>
<pre>git config --global user.name SeuNome<br/>
git config --global user.email seuemail-usado-no-github@abc.com <br /> </pre> 
     </li>
<li>Marcar os arquivos novos para commit<br />
    <pre>git add src/* </pre></li>
<li>Finalizar o pacote de envio dos arquivos marcados<br />
    <pre>git commit -m ‘Mensagem’ </pre></li>
<li>No início da página do seu GitHub, procure a URL do repositório <br />
    <pre>git remote add origin URL</pre> </li>
<li>Se existir alguma alteração nova no repositório, será necessário fazer o merge antes:<br />
    <pre>git pull origin master</pre> </li>
<li>Por fim, submeter as alterações:<br />
    <pre>git push origin master</pre></li>
  </ol>


