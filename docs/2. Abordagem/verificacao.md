# 2.3 Verificação de Acessibilidade

A verificação é responsável pela garantia de que o que foi exigido na concepção
de um sistema será, de alguma forma, contemplado pelo que será entregue. Em relação a
possíveis pontos de verificação, a International Organization for Standardization
apresenta como possibilidade, além dos artefatos mais comuns como os requisitos especificados e as descrições do design, a utilização do próprio sistema e da descrição do projeto.
Quando a acessibilidade é mencionada como uma das características que descrevem o
produto, existem diversas maneiras de comprovar, por meio da verificação, a presença, ou
ausência, dessas práticas.

### Testes automatizados

A execução dos testes automatizados foi realizada com o auxílio do aplicativo Teste
de Acessibilidade, projetado especificamente para verificar a conformidade com os padrões
de acessibilidade em dispositivos Android. O aplicativo oferece uma interface simples e
intuitiva, identificando potenciais problemas de acessibilidade e fornecendo informações
detalhadas sobre sua localização na tela. Além disso, o Scanner sugere maneiras de resolver os problemas indicados, e alerta quando é apropriado realizar testes manuais para
complementar a verificação automatizada.

Para que o teste pudesse ser realizado em cada tela, o recurso foi ativado anteriormente nas configurações do smartphone. Dessa forma, um ícone de captura de tela fica
disponível para que a tela escolhida possa ser selecionada e avaliada. Após a captura de
tela, o relatório é exibido e fica arquivado no aplicativo, podendo também ser acessado
posteriormente. No relatório, os problemas são colocados em foco, enquanto o problema
detectado é exibido, juntamente com a sugestão de melhoria.

### Verificações Manuais

As ferramentas de verificação automatizada costumam ser eficientes para identificar problemas técnicos de acessibilidade em aplicativos. No entanto, tais
instrumentos nem sempre conseguem detectar todos os aspectos relacionados à acessibilidade, requerendo análise humana para exames mais eficazes. A realização
de verificações manuais de acessibilidade, por meio de inspeção, foi importante para garantir que o aplicativo atendesse aos padrões de acessibilidade descritos na abordagem.
A inspeção manual envolve a revisão detalhada do aplicativo por um avaliador que possua conhecimento dos critérios de acessibilidade determinados, devendo este responsável
examinar a interface; o conteúdo, e a interação para identificar possíveis problemas. As
inspeções foram realizadas utilizando checklists para apoio às checagens, através da ferramenta Notion. A
ideia foi utilizar esses recursos para planejamento da inspeção, acompanhamento de suas
etapas, bem como para a devida anotação e apresentação dos insumos gerados com checagens e listagens de itens.
As inspeções demandam etapas bem estabelecidas. No caso da presente abordagem, foram realizadas as seguintes fases: 

1. **Planejamento**: com a definição do contexto, processo de inspeção e
técnicas de detecção de problemas com base nos critérios avaliados; 
2. **Preparação**: Com a definição da ordem das inspeções e ajustes nas ferramentas que foram utilizadas, e 
3. **Execução**: Com as devidas marcações e anotações em relação aos critérios selecionados.

Com os fluxos já selecionados, iniciaram-se as inspeções analisando cada tela a
partir dos critérios de acessibilidade escolhidos. Para organizar a realização desse processo,
a plataforma Notion foi utilizada para criar uma página dedicada a cada um dos conceitos
estabelecidos pelo W3C, que compõem o conceito de acessibilidade. Dentro de cada página
foram criadas “checklists”contendo todas as telas dos fluxos escolhidos, categorizadas de
acordo com o critério a ser validado.

Durante as inspeções, foram utilizadas duas ferramentas essenciais: o Android
Talkback (leitor de tela para dispositivos Android) e a Calculadora de Contraste (criada por membros da UFRGS e disponibilizada online). Conforme cada tela foi avaliada, eram
realizadas marcações de acordo com a conformidade, onde as telas que satisfaziam o
critério eram marcadas com um “check”, enquanto aquelas que não atendiam ao critério
recebiam uma descrição detalhada do motivo pelo qual a validação tinha falhado.

*Todas as referências utlilizadas podem ser encontradas no artigo publicado.*
