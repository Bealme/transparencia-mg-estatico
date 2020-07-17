# Contratações para enfrentamento do coronavírus (COVID-19)

Este conjunto de dados contém relação das contratações celebradas pelo Governo de Minas Gerais com fulcro na Lei Federal n. 13.979 de 06 de fevereiro de 2020 e Lei Estadual n. 23.640/2020 para enfrentamento da emergência de saúde pública de importância internacional decorrente do coronavírus.

A atualização desta relação se dará por intermédio da Diretoria Central de Transparência Ativa da Controladoria-Geral do Estado, após a remessa de informações por parte do órgão ou entidade responsável pela contratação.

As informações sobre as contratações e aquisições para enfrentar a emergência de saúde pública decorrente da pandemia da COVID-19 estão dispostas no Portal de Transparência de três formas, para conhecê-las [clique aqui](http://transparencia.mg.gov.br/perguntas-frequentes#todas-as-contrata%C3%A7%C3%B5es-ou-aquisi%C3%A7%C3%B5es-realizadas-para-o-combate-da-pandemia-da-covid-19-s%C3%A3o-contrata%C3%A7%C3%B5es-emergenciais).

#### Atualizações relevantes   
**10/06/2020**  
* Inserção de variáveis adicionais relativas ao processo de compra
  * DATA_CADASTRAMENTO_PROCESSO
  * URL_DOCUMENTOS_PROCESSO
  * SITUACAO_PROCESSO
  * PROCEDIMENTO_CONTRATACAO
  * CODIGO_ORGAO_CONTRATO
  * ORGAO_CONTRATO
  * DATA_PUBLICACAO
  * URL_PROCESSO_SEI

* Inserção de variáveis relacionadas ao(s) item(s) de material/serviço constantes do processo de compra:
  * CODIGO_ITEM_MATERIAL_SERVICO
  * ITEM_MATERIAL_SERVICO
  * CODIGO_UNIDADE_ORCAMENTARIA
  * UNIDADE_ORCAMENTARIA
  * LINHA_FORNECIMENTO
  * CIDADE_ENTREGA
  * QUANTIDADE_HOMOLOGADA
  * VALOR_REFERENCIA_UNITARIO
  * VALOR_HOMOLOGADO_UNITARIO
* Alteração do separador do csv para ","
* Divulgação dos dados como planilha eletrônica
* Exclusão das colunas ANO e SIGLA_ORGAO_ENTIDADE
* Alteração no arquivo csv do formato das colunas data de YYYYMMDD para YYYY-MM-DD
* Alteração dos nomes das colunas:
  * ODIGO_ORGAO_ENTIDADE -> CODIGO_ORGAO_CONTRATO
  * OBJETO -> OBJETO_PROCESSO
  * VALOR -> VALOR_HOMOLOGADO
  * LINK_SEI -> URL_PROCESSO_SEI -> NUMERO_PROCESSO_COMPRA
  * NUMERO_SIAFI -> NUMERO_CONTRATO
  * INTEGRA_CONTRATO -> URL_INTEGRA_CONTRATO
  * LINK_PORTAL -> URL_PORTAL_TRANSPARENCIA

**28/03/2020**
* Divulgação inicial
