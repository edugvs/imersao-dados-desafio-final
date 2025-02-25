
# CLUSTERIZAÇÃO DE EXPRESSÃO GÊNICA - PROJETO FINAL 3º IMERSÃO DADOS DA ALURA

<p align="center">
  <img src="img/preview.png" />
</p>

## **Introdução**

<div align="justify"> Toda informação biológica dos seres vivos está armazenada em uma biomolécula chamada ácido desoxirribonucleico ou simplesmente DNA. O conjunto de todo material genético dentro de cada célula, de qualquer forma de vida, sejam bactérias, arqueas ou eucariotos, é denominado genoma. Nos organismos eucariotos, aqueles que possuem núcleo celular - estrutura que contém o genoma - e multicelulares, como nós humanos, todas as células possuem o genoma completo, com todas as características e "receitas" que ditam o que aquele ser vivo é, seu comportamento, suas estruturas histológicas e anatômicas e como se desenvolve.
  
<p>
</p>

Se todas as células do nosso corpo contêm todo o nosso genoma, como existem milhares de células altamente especializadas, com diferentes funções e estruturas totalmente divergentes espalhadas por aí? 

É nesse contexto que precisamos entender o conceito de expressão gênica e os mecanismos epigenéticos. A vida é algo extremamente complexo e tem um poder de organização incrível. Dependendo do tecido e função da célula, determinados genes são "ligados" ou "desligados" como se fossem interruptores, ou em termos técnicos, expressos ou não. A célula cardíaca sabe quais genes precisam ser expressos para que ela seja uma célula cardíaca, o mesmo acontece com os neurônios, células epiteliais, células que formam nossas mucosas, do nosso sangue e todas as outras que compõe nosso corpo. 

O termo expressão se refere ao processo de transcrição do DNA para outra molécula biológica chamada RNA e consequente tradução para uma proteína, de acordo com o código genético, os famosos códons - sequências de trincas de bases nitrogenadas, que explicarei logo o que são. Esse código é universal e todos os organismos vivos no planeta Terra o utilizam para formar suas proteínas. Muitas pessoas confundem o termo genoma com código genético.</div>

<p align="center">
  <img src="img/expressao-genica.png" />
</p>

REFERÊNCIA: O que é engenharia metabólica e como está transformando o mundo - Profissão Biotec <https://profissaobiotec.com.br/o-que-e-engenharia-metabolica-e-como-esta-transformando-o-mun/> Accessed: 2021-05-06</div>

<br>
<div align="justify"> O DNA que está sendo transcrito, ou expresso, é chamado de gene - ou em outras palavras, o pedacinho de DNA que vai gerar uma proteína com uma função no organismo, o resultado dessa transcrição é um tipo de RNA específico, o RNA mensageiro (RNAm). É o RNA que realiza todas as funções, de transcrever e traduzir o código presente no DNA em uma proteína, deixando o DNA com a função de um arquivo, onde a informação está escrita de acordo com um alfabeto de apenas 4 letras: A, T, C e G, que significam respectivamente: Adenina, Timina, Citosina e Guanina. Essas bases nitrogenadas são organizadas em pares - A com T e C com G. A ordem dos pares dessas unidades básicas da vida, dentro de cada gene, dita qual proteína será construída. 
 
<p>
</p>

Quase tudo nos sistemas biológicos funcionam com proteínas. Apenas como curiosidade, o genoma humano completo possui aproximadamente 3,2 bilhões de pares de bases. Em resumo, a expressão gênica se refere ao processo no qual um gene ou DNA codificante produz uma proteína, esse processo também é conhecido como Dogma Central da Biologia Molecular. A regulação da expressão gênica é algo extremamente importante para qualquer organismo vivo, pois modula os processos biológicos de acordo com eventos intracelulares e com o ambiente. Existem diversos mecanismos pelos quais os seres vivos controlam a expressão gênica, estudados a fundo no campo da epigenética (acima do gene) e que não serão discutidos aqui com profundidade.

<p>
</p>

## **Objetivos e Métodos**

<div align="justify">Nosso objetivo neste projeto é mergulhar no universo da biologia e da biotecnologia e explorar uma base de dados da área. Utilizando uma dataset disponibilizado pela Alura, baseado em um projeto das instituições Broad Institute of MIT, Harvard University, do Laboratory for Innovation Science de Harvard (LISH) e do NIH Common Funds Library of Integrated Network-Based Cellular Signatures (LINCS) que disponibilizaram os dados em uma competição do <a href="https://www.kaggle.com/c/lish-moa">Kaggle</a>. Vamos tentar compreender como esses dados estão organizados e utilizaremos um algorítmo de aprendizagem não supervisionada de clusterização. O principal objetivo da técnica da clusterização é encontrar grupos semelhantes ou homogêneos em dados, que são chamados clusters (ou grupos). Esse método é muito utilizado na simplificação de grandes conjuntos de dados agrupando características com valores semelhantes em um número menor de categorias homogêneas. Neste caso, usaremos a distância euclidiana para agrupar os dados, quanto menor for a distância entre um par de elementos, maior é a similaridade entre eles. A clusterização geralmente é um dos primeiros passos na análise de expressão gênica e é um método frequentemente usado por inúmeros pesquisadores da área. </div>

<p>
</p>

O dicionário de dados está disponível no início do notebook, lá é explicado como os dados estão organizados, quais são as variáveis e o que elas representam.</div>

<br>

<p align="center">
  <img src="img/clustering-example.png" />
</p>

 REFERÊNCIA: Um exemplo simples de agrupamento com 40 genes medidos em duas condições diferentes. D'haeseleer, P. How does gene expression clustering work?. Nat Biotechnol 23, 1499–1501 (2005). <https://doi.org/10.1038/nbt1205-1499>
 
 <br>
 
 
 
 ## Estrutura do repositório
 
- `Dados`: A pasta contém os arquivos em formato **CSV** utilizados.
- `Notebook`: Arquivo do jupyter notebook com o script completo do projeto. <a href="https://edugvs.github.io/imersao-dados-desafio-final/">Clique aqui</a> para acessar o script.
- `img`: Contém os arquivos de imagens utilizadas no projeto e na apresentação do projeto.

<p>
  </p>


## Links úteis:

- [Drug discovery: passado, presente e futuro](https://docs.google.com/document/d/10EhrQBChlyYIcff3to7PrCQi5HcNk2r-zd2ZCKPtcz8/edit?usp=sharing)
- [Expressão gênica: o caminho da informação biológica](https://docs.google.com/document/d/1TR-Q1cb2k_-S_MZC-60PMN2CbVGZbLMKT0Lr_didPY0/edit?usp=sharing)
- [How does gene expression clustering work? - NATURE](https://www.nature.com/articles/nbt1205-1499#:~:text=Clustering%20is%20often%20one%20of%20the%20first%20steps%20in%20gene%20expression%20analysis.&text=We%20can%20distill%20the%20data,is%20where%20clustering%20comes%20in.)




