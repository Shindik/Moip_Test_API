# Moip_Test_API
Projeto Teste API - MOIP

Para os testes foi utilizado:
  Eclipse IDE for Java Developers
  Version: Oxygen Release (4.7.0)
  - Maven Dependencies
  - JRE System Library [J2SE - 1.5]
  - Rest Assured

---------------------------------------------------------------------------------------------------------------------

O Projeto de Teste está disponibilizado neste repositório 'MoipTestFinal.zip'.
  É necessário apenas descompacta-lo (Projeto Moip.Test.API) e importar para o Eclipse
  
Passos para importação:
  No Eclipse Clicar em ('File' > 'Import...')
    Selecionar ('General' > 'Existing Projects into Workspace') e clicar em <NEXT> 
    Selecionar o Diretorio  'Moip.Test.API'e clicar em <Abrir>
    Clicar em <Finish>

---------------------------------------------------------------------------------------------------------------------
 
Infomações adicionais:
  O CodeHash - BASE64 utilizado está no meu usuario Sandbox <Acesso.java>.
    Não é necessário alterar nada.

  Para iniciar os testes, executar (Run) o Script principal <Scheadule.java>.
    Não foi possível validar os scripts de Captura e Cancelamento de pagamento. Scripts Comentados.
  
  O Projeto possui Log para acompanhamento da execução.

---------------------------------------------------------------------------------------------------------------------

Os dados utilizados e o plano de teste/roteiro de teste estão disponiveis no arquivo 'PlanoDeTeste_API_Moip.xlsx' 
encontrado neste repositorio.

  Durante alguns testes manuais foi identificado uma inconsistencia (informado no arquivo'PlanoDeTeste_API_Moip.xlsx'):
    Funcionalidade Inclusão de Cliente - Erro previsto CUS-0007 - Data de Nascimento Invalido.
      - Data utilizada e permitida a inclusão '2018.01.01' (data superior a data vigente).
      
---------------------------------------------------------------------------------------------------------------------

Fico a disposição para quaiquer esclarecimentos.

Atenciosamente,
Stefano Henrique Shindi Kawato
 - email...: shindi.kawato0@gmail.com
 - celular.: +55 (11) 97695-7556
