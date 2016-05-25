<h4>Passo a Passo Git</h4>

<h6>Submeter arquivos para um repositório, sem ter efetuado o clone</6>

<ol>
<li>Direcionar para a pasta do projeto</li>
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
<li>Se existir alguma coisa lá no repositório, será necessário fazer o merge antes:<br />
    <pre>git pull origin master</pre> </li>
<li>Em seguida, submeter as alterações:<br />
    <pre>git push origin master</pre></li>
  </ol>


