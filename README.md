# IBMEC - Pós Graduação BI &amp; Data Science
### Data Science e Interconexão Digital - Nicolas Oliveira

------------

## Dataset - Empresas Inidôneas e Suspeitas
Fonte: Portal da Transparência (https://portaldatransparencia.gov.br/download-de-dados/ceis)

[Descrição do Dataset](https://www.portaldatransparencia.gov.br/pagina-interna/603412-dicionario-de-dados-sancoes-ceis "Descrição do Dataset")
| Tipo de pessoa  | CPF OU CNPJ DO SANCIONADO | NOME INFORMADO PELO ÓRGÃO SANCIONADOR | RAZÃO SOCIAL | NOME FANTASIA | NÚMERO DO PROCESSO | TIPO SANÇÃO | DATA INÍCIO SANÇÃO | DATA FINAL SANÇÃO | ÓRGÃO SANCIONADOR | UF ÓRGÃO SANCIONADOR | ORIGEM INFORMAÇÕES | DATA ORIGEM INFORMAÇÕES | DATA PUBLICAÇÃO | PUBLICAÇÃO | DETALHAMENTO | ABRAGÊNCIA DEFINIDA EM DECISÃO JUDICIAL | FUNDAMENTAÇÃO LEGAL | DESCRIÇÃO DA FUNDAMENTAÇÃO LEGAL | DATA DO TRÂNSITO EM JULGADO | COMPLEMENTO DO ÓRGÃO |
| ------- | -------- | ------- | -------- | ------- | -------- | ------- | -------- | ------- | -------- | ------- | -------- | ------- | -------- | ------- | -------- | ------- | -------- | ------- | -------- | ------- |
| Identifica se a penalidade foi aplicada a "pessoa física" ou "pessoa jurídica" | Número de cadastro do sancionado junto à Receita Federal: CPF para pessoas físicas e CNPJ para pessoas jurídicas | Conforme registrado pelo órgão sancionador no SIRCAD, ou conforme publicado no DOU | Campo extraído da base CNPJ ou da base CPF da Receita Federal (resultado da busca pelo valor do campo "CPF ou CNPJ do Sancionado") | Idem anterior. Vale registrar que as informações de identificação do sancionado (nome informado, razão social e nome fantasia) são mantidas no CEIS para facilitar a pesquisa e dar transparência às sanções quando ocorre mudança de algum destes dados do sancionado | Número do processo no âmbito do qual foi aplicada a sanção | Todas as sanções que impliquem em restrição ao direito de participar de licitações ou de celebrar contratos com a Administração Pública. O rol de sanções e respectivas fundamentações legais está disponível em http://www.portaldatransparencia.gov.br/ceis/saiba-mais | Considera-se a data da publicação da sanção, quando não houver menção expressa à data de início de vigência da penalidade | Considera-se o prazo estabelecido para o término de vigência da penalidade. No caso da declaração de inidoneidade, mesmo que conste um prazo de vigência este é considerado prazo mínimo da penalidade. Portanto a inidoneidade só é excluída do CEIS mediante informação da reabilitação do sancionado (publicação da reabilitação no DOU, registro no SIRCAD e demais bases ou apresentação da decisão pela reabilitação) | Órgão específico que aplicou a sanção | Unidade da Federação do órgão responsável pela aplicação da sanção | Órgão que informou a sanção. Há, por exemplo, Governos Estaduais que estabelecem um órgão como o responsável pelo registro das sanções aplicadas por todos os entes daquele Governo. Também é o caso do CNJ, que mantém cadastro das sanções aplicadas por todos os órgãos judiciários | Data de registro da sanção no CEIS | Data da publicação da sanção em veículo oficial de informação | Veículo oficial de informação onde a sanção foi publicada | Dados da publicação, como por exemplo a seção e a página do DOU | O campo só é preenchido quando há determinação pela justiça da abrangência da sanção. Nos demais casos, a interpretação quanto à abrangência da sanção é de responsabilidade do usuário do cadastro | Dispositivo legal que fundamenta a aplicação da sanção | Detalhamento da norma que fundamenta a aplicação da sanção | Campo opcional que indica a data em que a decisão judicial pela aplicação da sanção transitou em julgado, ou seja, quando não se pode mais recorrer judicialmente desta decisão | Campo opcional que detalha, quando pertinente, a unidade responsável pela aplicação da sanção. Trata-se de detalhamento da informação da coluna "Órgão Sancionador" |