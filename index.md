# Corpora em Língua Portuguesa

*Pedro Arthur Freitas Dias*

O projeto AC/DC (Acesso a Corpo/Disponibilização de Corpo) faz parte do grupo de recursos oferecidos na Linguateca. O projeto Linguateca é um conjunto de recursos distribuído para o processamento de língua portuguesa . Dentre seus objetivos está facilitar o acesso aos recursos linguísticos existentes e organizar a colaboração dos interessados. 

No seu catálogo de recursos é possível encontrar Corpora, Léxicos e Dicionários, Material Didática, Serviços para processamento da língua, etc). Além disso, é um bom local para entrar em contato com outros pesquisadores que trabalham na área.

Os seus princípais recursos são:

1. AC/DC: organização de diferentes corpora da língua portuguesa integrados com uma ferramenta de busca.
2. CETEMPúblico: corpus de aproximadamente 190 milhões de palavras em português criado em portugual financiado pelo Ministério de Ciência e Tecnologia do país. Acesso realizado pelo AC/DC
3. CETENFolha: corpus de cerca de 25 milhões de palavras de português brasileiro com textos extraídos do jornal Folha de S. Paulo.
4. COMPARA: textos paralelos em português e inglês com interface para pesquisa.
5. Corpógrafo: interface criada para facilitar a criação de corpora especializados. 
6. Esfinge: sistema de respostas automáticas de domínio geral em português.
7. Floresta sintá(c)tica: projeto para a obtencão de árvores sintáticas em português.


## AC/DC

O AC/DC possui atualmente uma coleção de 39 corpora extraídos de diferentes contextos. Os corpora são anotados - cada atributo pode ser marcado com POS, TEMCARGR, FUNC, etc. Todos os corpora possuem o mesmo funcionamento com pouco variação entre os marcadores. Cada corpus está devidamente documentado e uma descrição é encontrada[aqui](https://www.linguateca.pt/acesso/contabilizacao.php). 

A unidades dos corpora são palavras, sinais de pontuação, numerais e separas. A discriminação é feita pelo atomizador disponibilizado. 

Para realizar uma busca, basta selecionar um corpus e utilizar a sintáxe de busca. Se desejarmos encontrar as ocorrências de "mente" podemos usar:

* Para o verbo mente:
> [word="mente" & pos"V.*"]
* Para o substantivo mente:
> [word="mente" * pos"N"]

A anotação de busca completa pode ser encontrada [aqui](https://www.linguateca.pt/acesso/anotacao.html).


Alguns exemplos dos corpora disponíveis são:

1. [DHBB](https://www.linguateca.pt/acesso/desc_dhbb.html): 

    Este corpus linguístico contem verbetes sobre políticos brasileiros e produzido sob curadoria da Fundação Getúlio Vargas. O corpus Dicionários Históricos Brasileiros contém material de três obras: o Dicionário histórico-biográfico da Primeira República, o Dicionário Histórico-Biográfico Brasileiro e o Dicionário da política republicana do Rio de Janeiro.

2. [C-ORAL-BRASIL](http://www.c-oral-brasil.org):
    corpus criado que reúne textos com a fala espontânea em português brasileiro. Foi criado a partir de materiais gravados em CD-ROM. Neste corpus, repetições e pausas longas foram removidas e convertidas para a devida pontuação. Podemos encontrar no documento a fala e uma identificação do falante. Também é dividido por frases **s**. A descrição no AC/DC pode ser encontrada [aqui](https://www.linguateca.pt/acesso/desc_corpus.php?corpus=CORALBRASIL#extracto)
   
3. [CORDIAL-SIN](http://clul.ulisboa.pt/recurso/cordial-sin-syntax-oriented-corpus-portuguese-dialects): 

    corpus anotado constituído de transcrições de discurso oral com dialetos europeus. O documento foi extraído de arquivos de aúdio e foi obtido em 42 pontos diferentes de locais com língua portuguesa.Informações disponíveis [aqui](https://www.linguateca.pt/acesso/contabilizacao.php#cordial-sin).



## Referência

AC/DC. Acesso a Corpora/Disponibilização de Corpora. Disponível em: <https://www.linguateca.pt/ACDC/>. Acesso em: 21 de jun. de 2021.

Diana Santos & Eckhard Bick (2000). Providing [Internet access to Portuguese corpora: the AC/DC project](http://comum.rcaap.pt/bitstream/10400.26/406/2/SantosBickLREC2000.pdf). Proceedings of the Second International Conference on Language Resources and Evaluation (Athens, 31 May-2 June 2000), vol. 1 pp. 205-210.

