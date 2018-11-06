# workshop-nlu

### Serviços utilizados:
* [Watson Natural Language Understanding](https://www.ibm.com/watson/services/natural-language-understanding/)
* [Watson Knowledge Studio](https://www.ibm.com/watson/services/knowledge-studio/)
* Aplicação Node-Red

### Deploy da aplicação usando Node-Red
Nossa aplicação utiliza a plataforma Node-Red para orquestrar os serviços listados acima. Para realizar o deploy siga os passos:
#### 1.Criar serviços:
* Watson Natural Language Understanding -> [Crie aqui](https://console.bluemix.net/catalog/services/natural-language-understanding)
* Node-Red -> [Crie aqui](https://console.bluemix.net/catalog/starters/node-red-starter)

#### 2.Importar arquivo node-red.json na sua aplicação Node-Red:
Copie o código deste [link](https://raw.githubusercontent.com/pedrohlcastro/workshop-nlu/master/node-red.json) e cole:
[edit_alt](https://raw.githubusercontent.com/pedrohlcastro/workshop-nlu/master/img/editar-params.png)
<img src='https://raw.githubusercontent.com/pedrohlcastro/workshop-nlu/master/img/editar-params.png'/>

Após importar o `node-red.json` você ira ver o seguinte fluxo:
<img src='https://raw.githubusercontent.com/pedrohlcastro/workshop-nlu/master/img/img-fluxo.png'/>

#### 3.Colocar credenciais do serviço de Natural Language Understanding no Node-Red:
<img src='https://raw.githubusercontent.com/pedrohlcastro/workshop-nlu/master/img/editar-params.png'/>

#### 4. Use o link atual /nlu para realizar testes:
<img src='https://raw.githubusercontent.com/pedrohlcastro/workshop-nlu/master/img/pagina.png' />


### Aprendendo WKS e ligando com NLU
Você pode utilizar o seguinte link para aprender ou repetir o processo feito durante o workshop [Clique aqui](https://developer.ibm.com/tutorials/extracting-personal-data-from-unstructured-text-using-watson-knowledge-studio/).

Lembrando, que para acessar a lista de **serviços criados**, basta acessar a dashboard e localizar o serviço:
* Clique na Logo da IBM Cloud, no canto superior esquerdo.
* Selecione o serviço que deseja acessar.

