# Resultado das eleições em São Paulo, SP
Visualização dos dados das eleições de 2020 em São Paulo
https://monimazz.github.io/sp_segundoturno_2020/

## Fontes

### Dados eleitorais
TSE - Respositório de dados eleitorais https://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais-1/repositorio-de-dados-eleitorais

### Shapefile
O Shapefile das zonas eleitorais da cidade de São foi obtida através do seguinte github: https://github.com/mapaslivres/zonas-eleitorais . Os dados segundo a fonte são do Estadão e está disponível no seguinte drive: https://drive.google.com/drive/u/1/folders/1qwTlkNnt5SEnzirhrXbSXGST6vNvUAVM

## Método para encontrar possíveis laranjas - Estado
A lógica foi analisar candidatos que não possuíram nenhum voto nominal, ou seja que a soma de todos os seus votos é igual a zero. Assim, fiz um filtro em todos os candidatos que possuíam essa condição. Para verificar quantos partidos e municípios estavam nessa condições foi feita uma contagem da planilha filtrada.
Para identificar o gênero dos candidatos utilizer o pacote genderBR (https://github.com/meirelesff/genderBR), assim com possíveis falhas no cálculo pois foi feito de forma não supervisionada.


## Autora
Mônica Rocabado Mazzolenis de Oliveira
para mais trabalhos ou me contatar: http://rdados.rbind.io/ ou https://rdados.netlify.app/
