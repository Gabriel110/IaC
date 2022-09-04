<h1 align="center">Comandos interattivos kubectl</h1><br>
<b>kubectl get nodes</b> - Lista nossos nos .<br>
<b>kubectl run mongodb --image=mongo:latest --port=27017</b> - Inicia uma imagen na porta especificada.<br>
<b>kubectl get pods</b> - Lista nosso pods.<br>
<b>kubectl delete pod NAME-pod</b> - Deleta o pode com nome passado.<br>
<b>kubectl create -f ./.json OR ./.yml</b> - Cria um recurso com base em um arquivo json ou yaml.<br>
<b>kubectl apply -f ./ .json OR ./ ;yaml</b>  - Cria um recurso com base em um arquivo json ou yaml.<br>
<b>kubectl exec -it NAME-pod mongo Mongodb -- shell version v4.0.1 </b> - Execulta o shell do mongoDb em um pod no modo interativo.<br>
<b>kubectl get svc OR Service</b> - Lista os services<br>
<b>kubectl get nodes -o wide</b> - Mostra algumas informacao a respido do NodePort<br>
<b>kubectl exec -it NOME_POD --container NOME_CONTAINER_DO_POD -- bash</b> - Modo interativo k8s <br>

<h1 align="center">Comandos interattivos Docker</h1><br>
<b>Docker run</b> - Inicia uma imagen docker<br>
<b>Docker ps OR Docker container ls</b> - Mostra container em execusão<br>
<b>Docker ps -a OR Docler container ls -a</b> - Mostra todos os container criados, adicionano a flag -q so e listados os ids<br>
<b>Docker run IMAGE sleep 1d</b> - Faz um container rodar por um dia <br>
<b>Docker exec -it ID_CONTAINER bash</b> - Execulta o bash do ubunto em um pod no modo interativo.<br>
<b>Docker stop ID_CONTAINER -t 0</b> - Para um continer em 0 segundo<br>
<b>Docker start ID_CONTAINER<</b> - Inicia um container<br>
<b>Docker pause ID_CONTAINER</b> - Pausa um container<br>
<b>Docker unpause ID_CONTAINER</b> - Despausa um container<br>
<b>Docker rm ID_CONTAINER</b> - Remove um container<br>
<b>Dockrt run -it ubuntu bahs</b> - Inicia o bash do umbuntu<br>
<b>Docker run -d -p 8080:80 dockersample/static-site</b> - Execulta um container sem travar nosso terminal na porta 8080<br>
<b>Docker port ID_CONTAINER</b> - Mostra porta mapeado de um container<br>
<b>Docker rm ID_CONTAINER --force</b> - Força a remoção de um caontainer<br>
<b>Docker history ID_CONTAINER</b> - Visualizar as camadas de uma imagem <br>
<b>Docker inspect ID_CONTAINER</b> - Especiona uma imagen<br>
<b>Docker build -t nodeapi .</b> - Cria uma imagen a apartir do nosso arquivo com o nome nodeapi no diretorio atual<br>
<b>Docker images</b> - Lista todas as imagens<br>
<b>Docker stop $(docker container ls -q)</b> - Para todos os container <br>
<b>Docker netwoerk create --driver bridge NOMEDA_REDE</b> - Criar uma rede bridge com o nome escolhido<br>
<b>Dokcker run -it --name ubuntu --network NOME_REDE ubuntu bash</b> - execulta de modo interaritivo o bash de uma imagem do ubumtu criada na rede NOME_DAREDE<br>
<b>Docker-compose up -d</b> - Inicia um ou mais containers<br>
<b>Docker-compose down</b> - Para um ou mais containers<br>
