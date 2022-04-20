# Projeto Integrador V - A

Bem vindos ao repositório que será utilizado no PI V-A.

Tendo por base os conceitos explorados nas disciplinas de “Redes Sem Fio e Comunicações Móveis” e “Roteamento”, bem como a partir da contextualização dos mesmos, feita na disciplina do Projeto Integrador V-A, os alunos irão individualmente sistematizar os conhecimentos e empregá-los de forma prática a fim de emular redes com e sem fio e seus protocolos de roteamento.

Neste **[link](https://docs.google.com/document/d/1gXFWOfzcvUY6TXPFpbDA4SVsfwe5ZKol7v9w8nf8ivg/edit?usp=sharing)** está disponível o seu Plano de Execução.

### Professores Responsáveis

* Adenauer Yamin - adenauer.yamin at ucpel.edu.br
* Victoria Souto - victoria.souto at ucpel.edu.br

### Material Encontros

* **[Slides Encontro 26/02](https://drive.google.com/file/d/1xeK9NlUdIgcdJCZnduJuT-v1HL8brV0g/view?usp=sharing)**
* **[Slides Web 11/04](https://docs.google.com/presentation/d/1IjiP7ROJc4lbp8I3zHwBDOXwwzGp_hNx/edit?usp=sharing&ouid=112819199735841573348&rtpof=true&sd=true)**

### Links Relacionados:

* **[Site Oficial do CORE](https://www.nrl.navy.mil/Our-Work/Areas-of-Research/Information-Technology/NCS/CORE/)**

* Materiais para download disponíveis na **[área da profa. Victoria](https://drive.google.com/drive/u/0/folders/1Br5WRXvqyvaAPmqad2RnRHZbGuk88Mtm)** no Google:
  * **[Máquina Virtual com o CORE instalado](https://drive.google.com/file/d/11VVABrhvjM7RNeLUvg92XlbPjTp0r_fj/view?usp=sharing)**
  * **[Instalador do VMWare para o MS-Windows - VMware-player-full-16.2.2-19200509.exe](https://drive.google.com/file/d/1PBE5Jm_TWVtyvRX8ZrJPMqYdbHbT51Ne/view?usp=sharing)**

* Abaixo dois tutoriais de como abrir arquivos VMDK (padrão VMWare) no VirtualBox:
  * **[Tutorial em Inglês](https://techathlon.com/how-to-run-a-vmdk-file-in-oracle-virtualbox/)**
  * **[Tutorial em Português](https://appleglitz.com/portuguese/como-abrir-um-arquivo-vmdk-no-virtualbox/)**

* Principais Protocolos de Roteamento:
  * [Roteamento: O que é Importante Saber - RNP](https://memoria.rnp.br/newsgen/9705/n1-1.html)
  * Pesquisa Google: principais protocolos roteamento
  * [Explicação dos 5 principais protocolos de roteamento de rede](https://fiodevida.com/explicacao-dos-5-principais-protocolos-de-roteamento-de-rede/)

### Entrega Final
A Entrega Final, que contempla 60% da nota do projeto integrador, irá consistir da entrega de um Relatório Final que descreva os procedimentos realizados na criação e análise de rotas na plataforma CORE. Também deverá ser incluída no Relatório Final a parte conceitual já tratada na Entrega Parcial. Juntamente com o Relatório Final deverá ser também disponibilizado acesso um vídeo que trate do apresentado tanto no Relatório Parcial, como no Final. No Relatório Final deverá ser incluído o link para acesso ao vídeo desenvolvido pelo grupo. O Relatório Final deverá ser entregue empregando a Plataforma A.

#### Procedimentos Práticos a Serem Registrados na Entrega (Relatório) Final

* Criar uma rede com no mínimo dois roteadores, dois switches e no mínimo um equipamento conectado em cada switch.
* Realizar a criação das rotas considerando o Roteamento Estático da rede, garantindo que todos os equipamentos da rede consigam se comunicar.
* Realizar um traceroute observando a presença dos roteadores na rota, bem como o não aparecimentos dos switchs
* Disparar um ping de longa duração entre os dois nodos.
* Utilizar o WireSharck para observar o tráfego em um dos roteadores que interliga os equipamentos particpantes do ping
* Medir a velocidade de comunicação utilizando o aplicativo iperf
   * No lado servidor utilizar: o comando iperf- c \<nodo que esteja executando o servidor do iperf\>
   * No lado cliente (outro nodo) utilizar: o comando iperf -s
   * Fazer uma medição com o iperf utilizando os links "originais" da rede.  Trocar a latência da rede incluindo um atraso (Delay no Core), por exemplo 10 ms, e medir novamente a velocidade após a inclusão do atraso. Ao invés do atraso, podem ser feitas medições utilizando o recurso de limitação da banda passante (Bandwidth no Core). 
 
