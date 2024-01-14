# Treinamento-do-Modelo-KNN
Análises para avaliar o desempenho do modelo KNN por meio do método back-mandante em apostas esportivas.
Back-mandante = "O time que joga no seu proprio estadio, o mandante da partida".
# Treinando a IA com as seguintes ODD's
* Odd do Mandante: ODD do time com o mando de campo;
* Odd do Visitante: ODD do time que não possui o mando de campo;
* Odd do Empate: ODD do placar igual;
* Odd do Over05: ODD do time mandante a fazer mais de 1 gol;
* Odd do Over15: ODD do time mandante a fazer mais de 2 gols;
* Odd do Over25: ODD do time mandante a fazer mais de 3 gols;
* Odd do BTTS: ODD de ambos os times marcarem independente do resultado.
# INSERINDO ODD's
1º Ao clicar no link disponibilizado, seguira para o colab desenvolvido;<br />
2º Ao clicar no link disponibilizado referente ao site de aposta, seguira para o site, onde coletara os dados necessarios;<br />
3º No colab aperta-se Ctrl+F9 para a execução do codigo e logo tera que inseir suas devidas odds;<br />
4º No BETFAIR escolha um jogo da premier league e permaneça no painel principal das ODD's;<br />
5º Insira no colab as ODD's necesarias de acordo com as do site de apostas, sendo: ();<br />
6º Tera o resultado calculado e treinado pela IA.
   
# COMPARANDO RESULTADOS
Haverá 2 tipos de resultados possiveis:
* Fazer Back Mandante: A IA analisou todos os possiveis dados do nosso DataFrame e utilizou o KNN para a comparação e concluiu que fazer back mandante é a melhor opção nesse treinamento.
* Ficar fora desse jogo: A IA analisou todos os possiveis dados do nosso DataFrame e utilizou o KNN para a comparação e concluiu que ficar fora desse jogo (não apostar no dono da casa) é a melhor opção nesse treinamento.
