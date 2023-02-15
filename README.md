# Métricas para Times ágeis

O que é CFD? 
O Cumulative Flow Diagram, mais conhecido como CFD, é um diagrama de fluxo acumulado.

Isto significa que ele registra de forma cumulativa a quantidade de demandas que passam pelo fluxo de trabalho, distinguindo as etapas do fluxo (to do, doing, done) por cores.

A estrutura do diagrama é bastante simples. No eixo horizontal temos as medidas de tempo e na vertical o número de itens acumulados no fluxo.

![image](https://user-images.githubusercontent.com/52088444/219022105-1654726c-fe00-4fa0-84d4-63dc3b903dd8.png)

Identificando disfunções com CFD
A grande vantagem proporcionada pelo CFD é deixar visualmente expostas todas as disfunções do fluxo de trabalho. Com ele é possível melhorar a visualização de gargalos, desbalanceamento entre as etapas do fluxo e prever se o time está no caminho para a entrega dos itens do backlog.

Algumas situações comuns no CFD são:

Blocos do Waterfall
O modelo Waterfall é conhecido por entregar projetos de forma linear e sequencial. Nele uma etapa do fluxo não é iniciada até que a etapa anterior esteja completamente concluída.

Portanto é comum que o CFD deste tipo de modelo de projeto apresente linhas quase que totalmente verticais, visto que cada etapa do fluxo recebe “lotes completos” de trabalho a ser realizado.

![image](https://user-images.githubusercontent.com/52088444/219022310-33fa7d67-21bb-4094-a492-84b0a5534471.png)

Escadas do Scrum (Sprints)

O framework Scrum trabalha com sprints e portanto realiza entregas periódicas cuja cadência é pré-definida.

Métodos, metodologias e frameworks que trabalham desta forma, costumam apresentar no CFD uma espécie de “escada” na etapa que representa a entrega ou publicação. Os picos desta etapa se referem ao fim de cada sprint e as entregas realizadas em cada uma delas.

![image](https://user-images.githubusercontent.com/52088444/219022576-f3ad68a5-e6fc-4df2-9160-b8804d1c8692.png)

O fluxo contínuo do Kanban
O método Kanban segue o conceito de entrega contínua e portanto não apresenta “escadas” como no Scrum pois as entregas são realizadas constantemente.

Nele o CFD apresenta, desde que não hajam desequilíbrios no fluxo, linhas que crescem quase que de forma paralela.

![image](https://user-images.githubusercontent.com/52088444/219022703-4b70a137-9d47-4845-8c33-9c8ae5ec5080.png)

Alguns comportamentos do CFD podem ser bastante esclarecedores e revelar problemas não notados no dia-a-dia. Alguns exemplos:


Linhas retas
Linhas retas representam problemas de vazão em uma ou mais etapas do fluxo.

A linha de uma etapa do fluxo só fica reta caso seu valor não sofra alteração durante determinado período de tempo. Neste caso, linhas retas em excesso ou muito longas nos dão a informação de que algo está impedindo ou retardando a vasão das demandas.

Linhas para baixo
Linhas para baixo ressaltam um problema de manuseio do quadro pois indicam que existem tarefas voltando etapas no fluxo.

Voltar demandas nas etapas do quadro kanban não é considerada uma boa prática, pois perde-se o rastreio de em qual etapa do fluxo a demanda apresentou problemas que lhe impediram de seguir adiante.

Linhas que sobem vertiginosamente
Linhas que passam a subir vertiginosamente, principalmente quando próximas dos prazos de entrega, podem indicar que alguma política estabelecida não está sendo seguida ou está sendo flexibilizada para viabilizar a entrega de todos os itens.

Caso não tenha sido tomada nenhuma ação que justifique o ganho de performance repentino, é necessário entender o que pode estar causando está disfunção e tratar a causa raiz.

## Referencias

Todo o texto foi retirado do -> https://medium.com/@raphaelbatagini/o-que-%C3%A9-cfd-e-para-que-serve-89ae6dd20682


