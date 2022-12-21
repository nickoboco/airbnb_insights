## Projeto Airbnb - Exploração e análise de dados
Este projeto tem por objetivo auxiliar o time de negócio da empresa a tomar decisões embasadas em dados.

Os dados foram exportados de um repositório público, tratados com python e apresentados em um dashboard no Power BI.

Projeto publicado na URL: https://app.powerbi.com/view?r=eyJrIjoiNzJmNGFmMWQtYzY2ZC00ZDUzLWEyMWItOWJkMDIwYWI0YTg1IiwidCI6ImFjOGRkZTI1LWM1MDYtNDMyNy04OGIyLWMwOTNmZDM1NmRjZSJ9

## Questão de negócio
O investidor James Bauer gostaria de diversificar seus negócios e começar a investir em imóveis. Ele definiu que compraria imóveis na cidade de Nova York, nos Estados Unidos. Por ser um dos locais mais caros para se viver no País, ele acredita que obterá um retorno satisfatório de seus investimentos caso loque imóveis na cidade. Como todas as suas decisões são tomadas com base em dados, ele contratou você, cientista de dados, para ajudá-lo nessa empreitada.

James Bauer planeja inicialmente locar os imóveis adquiridos e por isso ele definiu que irá utilizar a plataforma Airbnb para esse fim. Para isso, ele lhe entregou uma base de dados públicos da empresa, contendo os dados do comportamento dos hosts e de seus imóveis.

## Insights
### 1 - A região de Manhattan possui os melhores imóveis em quesito rentabilidade
- Verdadeiro! O bairro de Roosevelt Island possui a melhor rentabilidade, superior a 100% comparado ao segundo colocado.

## Premissas do negócio
- Imóveis com 'Availability' igual a 0 (zero) foram considerados como 'Inativos'
- Para calcular a rentabilidade foi utilizado a fórmula: rentability = \frac{price * (minimoum\_nights + 1) * number\_of\_reviews}{\sqrt{availability\_365}} $$
- Para calcular o ROI foi utilizado a fórmula: return\_investment = \frac{investment}{price * (minimum\_nights + 1)} $$

## Conclusão
O objetivo desse projeto era prover insights valiosos ao time de negócio e auxiliá-los na tomada de decisão, portanto foi atingido.

## Próximos passos
Refinar o dashboard com mais insights e publicar as respostas do CEO em um aplicativo WEB como streamlit.
