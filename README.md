# Padrões de Votação por Localidade em Recife-Pernambuco

- O objetivo deste projeto é estimar e permitir a visualização do padrão de votação por localidade no município de Recife, inicialmente na eleição de 2022.
- Será possível identificar, para cada cargo, a incidência e frequência de votos por candidato ou partido por localidade.
  - A incidência diz respeito à proporção dos votos do candidato ou partido obtidos naquela localidade em relação a todos os votos obtidos por este no município (X% dos votos do candidato Y ocorreram no local Z)
  - A frequência diz respeito à proporção dos votos obtidos pelo candidato ou partido naquela localidade em relação a todos os votos dados na mesma localidade (X% dos votos da localidade Z foram dados ao candidato Y)
- As localidades de referência serão os setores censitários do Censo de 2022
  - Partindo do pressuposto de que a maior parte dos eleitores vota no local de votação mais próximo do seu domicílio, os votos de cada local de votação serão integralmente atribuídos a todos os setores censitários que se encontrarem mais próximos deste local de votação do que de qualquer outro. 


# Datasets consultados
- Malha de setores censitários do município do Recife, extraída a partir do arquivo PE_Malha_Preliminar_2022, disponibilizado pelo IBGE: https://www.ibge.gov.br/estatisticas/downloads-estatisticas.html
- Resultados da eleição de 2022 do município do Recife por seção eleitoral, extraídos a partir do arquivo votacao_secao_2022_PE, disponibilizado pelo TSE: https://dadosabertos.tse.jus.br/dataset/resultados-2022/resource/f382f4e4-a794-430c-a035-d23730257995
- Malha dos bairros do município do Recife, disponibilizada pelo portal de Dados Abertos do mesmo município: http://dados.recife.pe.gov.br/dataset/c1f100f0-f56f-4dd4-9dcc-1aa4da28798a/resource/e43bee60-9448-4d3d-92ff-2378bc3b5b00
- Locais de votação do município do Recife, disponibilizado pelo Tribunal Regional Eleitoral de Pernambuco: https://www.tre-pe.jus.br/servicos-eleitorais/titulo-e-local-de-votacao/consulta-aos-locais-de-votacao-de-pernambuco