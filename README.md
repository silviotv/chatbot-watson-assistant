# chatbot-watson-assistant
Este aplicação é um demo de cliente de Chatbot em Node.js que utiliza Watson Assistant. Basta criar um Watson Assistant, colocar as credenciais neste app e fazer o deploy no Bluemix.

<p><a href="https://bluemix.net/deploy?repository=https://github.com/sergiogama/chatbot-watson-assistant" rel="nofollow"><img src="https://camo.githubusercontent.com/46f2f9aa54a26e36a277d9706cf9432297817d65/68747470733a2f2f626c75656d69782e6e65742f6465706c6f792f627574746f6e2e706e67" alt="Deploy to Bluemix" data-canonical-src="https://bluemix.net/deploy/button.png" style="max-width:100%;"></a></p>

# Para executar o app localmente
1º - [Instalar Node.js][]
<ul>
<li>cd no diretório raiz do projeto</li>
<li>Execute npm install para instalar as dependências do app</li>
<li>Altere o aquivo config/bot.js e coloque as credenciais e workspace_id do Watson Assistant nas lilnhas à seguir:     username = ""; password = ""; conversationWorkspace = "<workspace_id>";</li>
<li>Execute npm start para o iniciar o app</li>
<li>Acesse a aplicação no browser no link http://localhost:6001</li>  
</ul>







