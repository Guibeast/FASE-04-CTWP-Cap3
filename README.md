# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# FarmTech Solutions - Assistente Agrícola Inteligente

## Nome do grupo
Turma R - Grupo 36

## 👨‍🎓 Integrantes: 
- <a href="#">Guilherme da Nóbrega Gontijo - RM562211</a>
- <a href="#">Murilo Ferreira Borges - RM567738</a>
- <a href="#">Estevão Ferreira - RM567522</a> 
- <a href="#">Durval de O Dorta Jr - RM567007</a> 
- <a href="#">Guilherme Cury - RM564011</a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="#">Ana Cristina dos Santos</a>
### Coordenador(a)
- <a href="#">André Godoi Chiovato</a>


## 📜 Descrição

O projeto WheatML aplica técnicas de Inteligência Artificial voltadas à Agricultura de Precisão para automatizar a classificação de grãos de trigo. Utilizando o Seeds Dataset do UCI Machine Learning Repository, o trabalho segue a metodologia CRISP-DM para explorar, preparar, modelar e avaliar dados reais de três variedades de trigo.

A solução inclui:

- Análise Exploratória (EDA): Visualização das distribuições, correlações e padrões entre as características físicas dos grãos.

- Pré-processamento: Padronização, separação treino/teste e preparação das variáveis.

- Modelagem: Treinamento de diferentes algoritmos de classificação (KNN, SVM, Random Forest, entre outros).

- Avaliação e Otimização: Uso de métricas como acurácia, precisão e F1-score, além de Grid Search para ajuste de hiperparâmetros.

O resultado é um modelo capaz de classificar automaticamente diferentes tipos de grãos com alta precisão, contribuindo para processos agrícolas mais eficientes e tecnológicos.


## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>assets</b>: Armazena o arquivo logo-fiap.png, logo da FIAP e prints do projeto.

- <b>data</b>: Armazena o arquivo seeds_dataset.txt, que serve como base de dados para o treinamento do modelo.

- <b>docs</b>: Contém a documentação de dependências do projeto, incluindo o arquivo requirements.txt.

- <b>src</b>: Todo o código fonte da aplicação principal: AtividadeCap3Fase4.ipynb.

- <b>README.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

## 🔧 Como executar o código

Siga o passo a passo abaixo para configurar o ambiente e reproduzir o projeto.

### 🚀 Instalação e Execução

1.  **Instalação das Dependências**
 Abra o terminal na raiz do projeto e instale as bibliotecas necessárias:
    ```bash
    pip install -r docs/requirements.txt
    ```
    

2.  **Carregamento do Dataset**
    Certifique-se de que o arquivo seeds_dataset.txt esteja localizado na pasta "data":
 

3.  **Análise Exploratória**
    Rode o notebook ou script destinado à exploração inicial dos dados.


4.  **Treinamento do Modelo**
    Execute o script ou notebook responsável pelo treino e avaliação dos classificadores.
    

5.  **Otimização (Opcional)**
Utilize o Grid Search disponível no projeto para ajustar hiperparâmetros e melhorar o desempenho dos modelos.
    

---

🗃 Histórico de lançamentos

0.1.0 - 27/11/2025

Versão inicial da solução WheatML: EDA, pré-processamento e modelos de Machine Learning.


## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
