# Parâmetros gerais -> Geral
Os parâmetros gerais do sistema permite fazer definições de regras gerais do sistema como obrigatoriedade de campos e habilitar novos campos em cadastros específicos.

Menu -> Configurações -> Configurações -> Parâmetros gerais

|Campo|Descrição |
|---|---|
|Adicionar documento após aprovação|Se habilitado os campos de centros de custos estão disponíveis nos documentos de compra e venda|
|Habilitar centro de custo|Se habilitado os campos de centros de custos estão disponíveis nos documentos de compra e venda|
|Habilitar utilização no documento de marketing|Se habilitado pode-se selecionar utilização nos documentos de marketing|
|Obrigar uso de projeto|Se habilitado o campo projeto se torna obrigatório nos documentos de marketing|
|Usuário deve ver apenas seus próprios documentos|Se habilitado o usuário logado não vê os documentos criados por outros usuários|
|Permitir compra de ativo fixo|Se habilitado permitirá ao usuário inserir documentos de compra com itens do ativo fixo|
|Permitir venda de ativo fixo|Se habilitado permitirá ao usuário inserir documentos de venda com itens do ativo fixo|
|Permitir selecionar conta contábil de despesa|Se habilitado o campo conta contábil ficará disponível para o usuário selecionar uma conta do razão|
|Exibir saldo disponível no orçamento ao selecionar conta contábil|Se habilitado o usuário poderá ver o saldo orçado para conta contábil no orçamento definido|
|Cenário de orçamento|Se habilitado o campo *Exibir saldo disponível no orçamento ao selecionar conta contábil* o usuário deverá informar nesse campo o orçamento, basta ele selecionar na listagem os orçamentos disponíveis|
|Permitir usuário SAP editar documento gerado após aprovação|Se habilitado permitirá ao usuário editar rascunhos já aprovados|
|Permitir fornecedor editar documento gerado após aprovação|Se habilitado, o usuário *fornecedor* poderá editar documentos de compra já aprovados|
|Entrega com base em data de processamento|Se habilitado o sistema irá bloquear o lançamento do documento caso o lead time *Tempo de produção/preparo* exceda a data de entrega informada no documento. Ex: Imagine que seja lançado um documento onde o item leva 2 dias para ficar pronto para envio, nesse caso o sistema não deixará inserir um documento caso a entrega ocorra em menos de 2 dias|
|Permitir escolher depósito|Se habilitado o campo *Depósito* ficará disponível para o usuário selecione o depósito no documento|
|Usar depósito padrão|Se habilitado permitirá ao usuário selecionar no campo *Depósito padrão* um depósito fixo, nesse o sistema sempre irá o depósito selecionar de uma lista nos documentos de compra e venda|
|Depósito padrão|Permite ao usuário selecionar um depósito em uma listagem como sendo o depósito padrão de entrada e saída. O campo *Usar depósito padrão* precisa estar habilitado para esse campo estar visível|
|Usar depósito padrão do item|Se habilitado o campo *Usar depósito padrão* é automaticamente desligado e o sistema passa a usar sempre o depósito padrão informado no cadastro do item|
|Usar depósito padrão da filial|Se habilitado o campo *Usar depósito padrão* é automaticamente desligado e o sistema passa a usar sempre o depósito padrão informado no cadastro de filial. **Esse campo só pode ser habilitado se o recurso de muiltifilial estiver habilitado no SAP Business One**|
|Número mínimo de dias para requisição|Se habilitado o sistema não permitirá que a data de entrega seja superior ao número de dias informado no campo nesse campo|
|Utilização padrão para fornecedor|Permite ao usuário selecionar a utilização padrão no documento de compra|
|Utilização padrão por cliente|Permite ao usuário selecionar a utilização padrão no documento de venda
|Habilitar anexos|Se habilitado permitirá ao usuário enviar arquivos como anexos em diversos documentos e cadastros|
|Diretório de anexos|Se o campo *Habilitar anexos* estiver habilitado é necessário informar o diretório no sistema operacional configurado no SAP Business One, ou seja, deve-se informar a pasta de arquivos|
|Habilitar diretório personalizado para pasta Temporária dos anexos|Se habilitado permite **forçar** o salvamento do anexo via escrita direta no diretório quando há erros de envio de arquivos usando a SAP Service Layer|
|Habilitar download direto|Se habilitado permite **forçar** o sistema a fazer o download do arquivo lendo o mesmo direto da pasta de arquivos e não usando a SAP Service Layer|
|Habilitar anexos na área do fornecedor|Se habilitado o usuário **Fornecedor** poderá enviar arquivos nos documentos de compra|
|Language|O campo permite ao usuário selecionar o idioma da aplicação|

[Próximo -> Configurações de relatório](4-general-settings-report.MD)