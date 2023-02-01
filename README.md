# Automatizacao-de-analise-de-mensagens-de-um-grupo-do-whatsapp

Código feito para automatizar o processo de análise das mensagens de um grupo de whatsapp, destinado a estimular a prática de atividades físicas entre um grupo de amigos. 
Antes de explicar o intuito do código, vou passar uma introdução sobre as regras do grupo:
- Cada participante do grupo deve estabelecer uma meta de dias treinados por mês;
- Cada vez que realizar alguma atividade física o participante deve enviar uma foto no grupo para comprovar a prática;
- Ao final do mês é feita uma análise do grupo, quando são somados os dias treinados por cada membro, sendo a pontuação de cada usuário anotada em uma planilha disponível para todos checarem; 
- O usuário que não conseguir bater sua meta de dias treinados ao final do mês deve contribuir com uma "caixinha", a qual é usada para custear uma confraternização entre os participantes no final do ano;

A análise das mensagens para verificação do número de dias treinados de cada membro do grupo era feita manualmente por um administrador, que verificava cada foto enviada por cada um dos 30 membros ao longo de todo o mês, um processo demorado e sujeito à erros na contagem. Assim realizei este código com o intuito de automatizar o processo de verficação da pontuação, a partir da análise do arquivo txt gerado pelo whatsapp ao exportar uma conversa pelo aplicativo.
