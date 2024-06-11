# DESENVOLVIMENTO - MINI TCA
  Uma versão "Mini" do TCA foi desenvolvida com o objetivo de testar se as travas para botões e outras peças de hardware, atigiriam o acabamento necessário após impressas
![MINI TCA - FOTO](https://github.com/ICEI-PUC-Minas-PPC-CC/ppc-cc-2024-1-ment2-noite1-TCA_ADEFIP/assets/20716371/c7091df4-9760-47cb-80aa-271e89b4e0b5)

## Programação
  A principio a programação não funcionou por diversos fatores envolvendo compilador desatualizado, falta de bibliotecas instaladas, ligação dos fios feita errada e etc, mas ao final de tudo, utilizamos o chat GPT para criar uma programação onde atenderia nossa necessidade e um resultado satisfatório foi alcançado onde conseguimos testar dois botões contendo um delay de 3 segundos (iremos diminuir esse tempo) para apertar outro botão. Isso foi feito para que o usuário não aperte mais de uma tecla ao mesmo tempo e cause um erro de aúdio.
  
[TCA - Funcionamento](https://github.com/ICEI-PUC-Minas-PPC-CC/ppc-cc-2024-1-ment2-noite1-TCA_ADEFIP/assets/20716371/f901f55a-fe88-49ee-864d-d7651b7a1f30)

## Impressão 3D
  Travas e entradas foram feitas para prender os botões, chips, baterias e outras peças de hardware, porém essa versão mini foi feita com o intuito de testar o acabamento da impressão 3D e ver se as travas tem o funcionamento esperado, porém problemas aconteceram na hora de imprimir o 3D devido a falta de ajuste no programa SketchUp (utilizado para projetar o 3D do equipamento), fazendo com que as peças ficassem invisiveis em algumas partes. O problema foi resolvido porém um outro apareceu e esta sendo corrigido onde um dos botões não esta sendo impresso e a base do mini prototipo não imprime corretamente no preview do programa Cliever PRO.

## Conclusão - Problemas e dificuldades
  Sabiamos que seria um projeto dificil de ser executado e inclusive, eu Giovani assumo que fiquei receoso e com um certo medo de não dar certo quando houve o problema com a impressão 3D e com a programação, incluido hoje 10/06 um problema que aconteceu onde foi feito aprimoramentos no código e na hora de mandar para o Arduino Uno fornecido pela professora Luciana, por algum motivo que não sabemos até agora, a compilação do código era feita normalmente porém o upload para o Arduino falhava...foram testados 3 computadores, cabos e diversos setups de montagem dos fios e nada funcionava até que milagrosamente voltou a funcionar e assim permaneceu.
  
  Ainda tem desafios pela frente com o Arduino Nano e a implementação do _Bluetooth_, porém ja caminhamos uma boa jornada e conseguimos excelentes resultados fazendo o basico e primordial do equipamento funcionar, que é apertar um botão e ele executar determinado audio, o som sair em dois alto falantes e ter uma logica responsiva por trás.
  
  Os proximos passos agora são:
#|Item|
|:----:|:----:|
1|Resolver o problema com o 3D Mini|
2|Testar qual modelo de botão é melhor para o 3D final|
3|Fazer o _Bluetooth_ funcionar|
4|Finalizar o 3D da versão final baseado no feedback do 3D Mini|
5|Revisar o código contra possiveis falhas e erros que possa ocorrer|
6|Montar todo o hardware no 3D final impresso|
7|Enviar para a ADEFIP testar|

