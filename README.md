<img src="https://github.com/MEmilyGomes/BNN-em-Python-Puro/blob/main/Imagens/logo.png?raw=true" alt="Descrição da imagem" style="width: 1000px; height: auto; ">

<h1 align="center">Rede Neural Binária (BNN) 🗃️: </h1>

<h2 align="center">Predição da região do experimento de ressonância magnética funcional (fMRI)</h2>

<p align="center"><strong>Autores:</strong> Maria Emily Nayla Gomes da Silva e Thomas Wolff Hannemann</p>
<p align="center"><strong>Professor:</strong> Daniel R. Cassar</p>


## 📝 Introdução
<p align="justify">O trabalho apresenta a construção de uma <em>Rede Neural Binária</em> (BNN) com dados de fMRI, ressonância magnética funcional. Por meio da linguagem de programação Python, sem o uso de bibliotecas que treinam modelos de aprendizado de máquina, foi desenvolvido um modelo de rede neural capaz de realizar uma classificação binária para predizer a região cerebral onde ocorreu o experimento de neuroimagem como "parietal" ou "frontal". Dessa forma, nosso trabalho consistiu em modificar uma Rede Neural de regressão — algoritmo disponibilizado pelo Prof. Dr. Daniel Cassar — para um modelo de classificação binária. Para isso, alteramos a função de perda, <em>loss</em>, para <em>cross entropy</em> e adicionamos à classe Valor o método de logaritmo natural. Além disso, foram realizadas análises de dados específicas para o modelo de classificação binária.</p>

## 🗂️ Dataset seaborn fMRI
<p align="justify">O dataset utilizado para conseguir treinar a BNN foi o <strong>fmri</strong>, um dataset didático da biblioteca Seaborn. Os dados contidos nele são sobre um experimento de neuroimagem funcional (<strong>fMRI</strong>), e cada coluna nos indica:</p>

### Tabela de Features do Dataset `fmri`

| Features    | Descrição                                                                                                                                             |
|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| `subject`   | Código identificador do participante.                                                                                                                 |
| `timepoint` | Ponto no tempo em que a medição foi realizada – medida por TR (*repetition time*), que é o intervalo entre duas aquisições consecutivas de imagens do cérebro. |
| `event`     | Tipo de estímulo que o participante recebeu.                                                                                                          |
| `region`    | Região cerebral onde a medição foi feita.                                                                                                             |
| `signal`    | Valor do sinal fMRI medido na região – a atividade cerebral registrada.                                                                               |

<p align="justify">Com esses dados disponíveis, foram utilizadas como <em>features</em> as variáveis <em>timepoint</em>, <em>signal</em> e <em>event</em>; e como <em>target</em>, a variável <em>region</em>. Ou seja, a proposta é identificar se a medição foi realizada na região parietal ou frontal do cérebro.</p>


## 🏋️‍♀️ Construindo e Treinando a BNN


## 🔢 Resultados Obtidos
<div align="center">
  <img src="Imagens/matriz_confusao.jpg" alt="Descrição da imagem" width="400"/>
</div>


## 😁 Conclusão

## 🧠 Contribuições dos Colaboradores
| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/172424897?v=4" width=115><br><sub> Maria Emily Nayla</sub>](https://github.com/MEmilyGomes)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/9482558334105708)<br> |  [<img loading="lazy" src="https://avatars.githubusercontent.com/u/172425104?v=4" width=115><br><sub>Thomas Wolff Hannemann</sub>](https://github.com/ThomasHannemann)<br> <br> | 
| :---: | :---: | 

#### Para o Projeto:
* Emily Gomes: Atualizando, treinando e analisando dados da previsão de uma BNN utilizando Python puro.
* Thomas Wolff: Atualizando, treinando e analisando dados da previsão de uma BNN utilizando Python puro. 

#### Para o Repositório GitHub:
* Emily Gomes: README, upload de imagens.
* Thomas Wolff: Upload do notebook Jupyter referente a construção, treinamento e previsão da BNN.
  
