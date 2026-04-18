# Engenharia de Requisitos - Sistema Andreia (Sprint 2)

## 1. Requisitos Funcionais (RF)

*Ações que o sistema deve realizar.*

* **RF01 - Cálculo de Comissão:** O sistema deve calcular automaticamente a porcentagem de lucro baseada no faturamento inserido.
* **RF02 - Fechamento de Caixa:** O sistema deve registrar entradas de Moedas, Pix, Cartão e Fiado.
* **RF03 - Auditoria de Caixa:** O sistema deve subtrair o valor esperado do real e indicar sobras ou faltas.
* **RF04 - Relatório Semanal:** O sistema deve gerar gráficos de evolução de ganhos de segunda a sexta.
* **RF05 - Controle de Insumos:** O sistema deve registrar a contagem de cópias para controle de estoque de papel.
* **RF06 - Gestão de Alertas:** O sistema deve emitir lembretes de falta de papel e períodos de limpeza da impressora.
* **RF07 - Exportação de Dados:** O sistema deve permitir o backup dos dados diários em formato Excel (CSV).
* **RF08 - Mensagens Motivacionais:** O sistema deve exibir um "Versículo do Dia" ou frases motivacionais no painel principal.
* **RF09 - Tabela de Preços:** O sistema deve permitir a consulta e o cadastro de preços para serviços (Xerox, Faturas, etc.).
* **RF10 - Registro de Log:** O sistema deve gravar o horário de abertura/fechamento do caixa e o horário de cada venda realizada.
* **RF11 - Notas Rápidas:** O sistema deve possuir um campo de lembretes rápidos no topo da página.
* **RF12 - Gestão de Clientes:** O sistema deve permitir o cadastro de clientes "fiéis" para controle de débitos.

## 2. Requisitos Não Funcionais (RNF)

*Características e qualidades do sistema.*

* **RNF01 - Usabilidade Mobile:** O sistema deve ser totalmente funcional e responsivo para o telemóvel da Andreia.
* **RNF02 - Interface (Look & Feel):** O layout deve utilizar predominantemente a cor lilás, conforme preferência da cliente.
* **RNF03 - Segurança:** O sistema deve exigir login de utilizador para proteger os dados financeiros.
* **RNF04 - Confiabilidade:** O sistema deve garantir que nenhum dado de venda seja perdido durante o fecho do dia.

## 3. Regras de Negócio (RN)

*As "leis" e a lógica do negócio da Andreia.*

* **RN01 - Cálculo do Lucro Líquido:** O lucro da Andreia é calculado após a dedução do custo unitário de impressão/papel do valor total da venda.
* **RN02 - Validação de Fiado:** Uma venda a "fiado" só pode ser registada se estiver vinculada a um cliente previamente cadastrado.
* **RN03 - Periodicidade de Limpeza:** O alerta de limpeza da impressora deve aparecer a cada 15 dias ou após atingir um limite de impressões definido.
* **RN04 - Diferença de Caixa:** Qualquer diferença entre o valor real e o esperado acima de R$ 0,50 deve ser destacada no relatório de auditoria.
