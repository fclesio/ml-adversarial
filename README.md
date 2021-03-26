# Codecon Dev 2021 - Ataques Adversariais em Machine Learning

Esse repositório contém o código da palestra [Ataques Adversariais em Machine Learning](https://codecon.dev/palestras/ataques-adversariais-em-machine-learning).

Os [slides]() contém todas as referências e um material em anexo. 


## Demos

- [Ataque na cadeia de insumos](): _Devido aos grandes recursos (dados + computação) necessários para treinar algoritmos, a prática atual é reutilizar modelos treinados por grandes corporações e modificá-los ligeiramente para a tarefa em questão (por exemplo: ResNet é um modelo de reconhecimento de imagem popular da Microsoft). Esses modelos foram selecionados em um Model Zoo (o Caffe hospeda modelos populares de reconhecimento de imagem). Neste ataque, o adversário ataca os modelos hospedados no Caffe, envenenando os modelos que forem derivados a partir do modelo envenenado[1]._


- [Inferência de membros](): _O invasor pode determinar se um determinado registro de dados faz parte do conjunto de dados de treinamento do modelo ou não_ [1]


- [Backdoor em modelos de ML](): _Como no “Atacando na cadeia de insumos”, neste cenário de ataque, o processo de treinamento é total ou parcialmente terceirizado para uma parte mal-intencionada que deseja fornecer ao usuário um modelo treinado que contenha um backdoor. O modelo com o backdoor teria um bom desempenho na maioria das entradas (incluindo entradas que o usuário final pode ter em uma base de validação), mas causaria erros de classificação direcionados ou degradaria a precisão do modelo para entradas que satisfaçam alguma propriedade secreta escolhida pelo invasor, que será terá como gatilho um conjunto de dados específico_ [1]


- [Inversão de Modelo](): _Attacker recupera os recursos secretos usados no modelo por meio de consultas modificadas_ [1]


- [Envenenamento de modelos](): _O objetivo do atacante é contaminar o modelo de máquina gerado na fase de treinamento, para que as previsões sobre os novos dados sejam modificadas na fase de teste_ [1]


- [Roubo de modelo](): _Os atacantes recriam o modelo subjacente, consultando legitimamente o modelo. A funcionalidade do novo modelo é a mesma do modelo subjacente._ [1]



## Referências
[1] - [Kumar, Ram Shankar Siva, et al. "Failure modes in machine learning systems." arXiv preprint arXiv:1911.11034 (2019).](https://arxiv.org/abs/1911.11034). 

[2] - [Adversatial.io](https://adversarial.io/)

[3] - [AI Myths](https://www.aimyths.org/)

