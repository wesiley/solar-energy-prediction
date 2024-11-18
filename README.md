# Energias Renováveis ​​e Condições Climáticas
*Explorando o impacto do clima na geração de energia renovável.*

<img src= "https://images.pexels.com/photos/433308/pexels-photo-433308.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1">

Este conjunto de dados contém informações sobre consumo de energia e vários parâmetros climáticos, como radiação solar, temperatura, pressão, umidade, velocidade do vento e precipitação.

## Contexto do projeto

Em nosso projeto, nós, da equipe de cientistas de dados, temos o objetivo de construir um modelo preditivo que ajude a empresa de distribuição a antecipar as mudanças no consumo de energia ao longo do tempo. Para isso, utilizamos um conjunto de dados que contém informações detalhadas sobre variáveis climáticas, como a irradiância solar (a quantidade de radiação que atinge a superfície), temperatura, umidade, velocidade do vento e duração da luz solar. A ideia é entender de que forma essas variáveis impactam o consumo de energia e usar esse conhecimento para prever o consumo futuro, representado pela variável “Energy delta[Wh]”.

Esse modelo preditivo permitirá que a empresa ajuste suas operações e direcione os recursos energéticos de forma mais eficiente, maximizando o uso das fontes renováveis disponíveis de acordo com as condições climáticas de cada dia e época do ano. Em períodos de menor produção hidrelétrica, por exemplo, a empresa poderá otimizar a distribuição da energia renovável, de forma a reduzir a dependência de fontes de emergência, que costumam ser mais caras e menos sustentáveis. Dessa maneira, conseguimos não apenas reduzir os custos e aumentar a eficiência, mas também contribuir para a sustentabilidade da matriz energética, garantindo que o fornecimento seja confiável e resiliente, mesmo em tempos de crise hídrica.

Este projeto é uma oportunidade de aplicar a ciência de dados para resolver um problema real e urgente, ajudando a empresa a enfrentar os desafios de um cenário climático incerto e a fazer um uso mais inteligente das energias renováveis.

## Sobre o Dataset

| Coluna | Descrição |
|----------|----------|
| Time | O registro de data e hora dos dados registrados no formato AAAA-MM-DD HH:MM:SS |
| Energy delta[Wh] | A diferença no consumo de energia em Watt-hora (Wh) do registro de data e hora anterior para o registro de data e hora atual |
| GHI | Irradiância horizontal global em watts por metro quadrado (W/m²) medida por um piranômetro, que é a quantidade de radiação solar recebida por uma superfície horizontal |
| temp | A temperatura em graus Celsius (°C) medida na mesma altura do piranômetro |
| pressure | A pressão atmosférica em hectopascais (hPa) medida na mesma altura do piranômetro |
| humidity | A humidade relativa em percentagem (%) medida à mesma altura do piranómetro |
| wind_speed | A velocidade do vento em metros por segundo (m/s) medida na mesma altura do piranômetro |
| rain_1h | A quantidade de precipitação em milímetros (mm) medida na última hora |
| snow_1h | A quantidade de neve em milímetros |
| clouds_all | A situação da nuvem |
| isSun | Informa se no dia teve ou não incidência solar |
| sunlightTime | Informa o tempo em minutos que ouve incidência solar |
| dayLength | A quantidade de tempo em minutos que durou o dia |
| SunlightTime/daylength | A proporção de tempo de sol pela duração do dia |
| weather_type | informa o tempo que estava ocorrendo na hora  |
| hour | A hora que o dado foi coletado |
| month | o mês que o dado foi coletado |

## Link do dataset
O dataset está disponível em: <a href="https://www.kaggle.com/datasets/samanemami/renewable-energy-and-weather-conditions">Renewable Energy and Weather Conditions
</a>
