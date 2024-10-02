# Padrões de Votação por Localidade em Recife-Pernambuco

- O objetivo deste projeto é estimar e permitir a visualização do padrão de votação por localidade no município de Recife, inicialmente na eleição de 2022.
- Será possível identificar, para cada cargo, a incidência e frequência de votos por candidato ou partido por localidade.
  - A incidência diz respeito à proporção dos votos do candidato ou partido obtidos naquela localidade em relação a todos os votos obtidos por este no município (X% dos votos do candidato Y ocorreram no local Z)
  - A frequência diz respeito à proporção dos votos obtidos pelo candidato ou partido naquela localidade em relação a todos os votos dados na mesma localidade (X% dos votos da localidade Z foram dados ao candidato Y)
- As localidades de referência serão os setores censitários do Censo de 2022
  - Partindo do pressuposto de que a maior parte dos eleitores vota no local de votação mais próximo do seu domicílio, os votos de cada local de votação serão integralmente atribuídos a todos os setores censitários que se encontrarem mais próximos deste local de votação do que de qualquer outro. 