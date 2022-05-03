# Aspects-Extraction-in-Portuguese

> Trabalho de conclusão de curso apresentado ao Curso de Ciência da Computação, como requisito parcial para a obtenção do Título de Bacharel em Ciência da Computação, Centro de Informática da Universidade Federal de Pernambuco.

A solução proposta trata do desenvolvimento de um modelo não supervisonado de extração de aspectos, para que a extração seja realizada basta apenas o conjunto de sentenças para que a extração seja realizada.

A arquitetura do sistema é dada da seguinte forma:

![](/content/Diagrama.png)

Para testes com novos domínios é necessário algumas mudanças no Notebook CAt_Paper, como a importação do novo conjunto ao ambiente de desenvolvimento desejado e algumas mudanças no path do domínio.
Com as devidas tratativas realizadas, basta executar o notebook em cada célula e os resultados serão gerados ao final do processo.

Para utilizar o arquivo de vetores de cbow_s50 por gentileza baixa-lo através do [NILC](http://nilc.icmc.usp.br/nilc/index.php/repositorio-de-word-embeddings-do-nilc#) 


Para reprodução dos resultados encontrados pelo paper basta upar os arquivos necessários encontrados na pasta <b>content</b> para o ambiente de desenvolvimento desejado

Os resultados comparativos se encontram disponíveis no notebook Avaliacoes