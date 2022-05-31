[![Github Actions Status for
claudiahylario/calculadora](https://github.com/claudiahylario/calculadora/workflows/Integra%C3%A7%C3%A3o%20continua%2
0de%20Java%20com%20Maven/badge.svg)](https://github.com/claudiahylario/calculadora/actions)
[![Quality Gate
Status](https://sonarcloud.io/api/project_badges/measure?project=claudiahylario_calculadora&metric=alert_status)](https://son
arcloud.io/summary/new_code?id=claudiahylario_calculadora)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=claudiahylario_calculadora&metric=coverage)](https://s
onarcloud.io/component_measures?id=claudiahylario_alculadora&metric=coverage)

# Calculadora com CI.
Utiliza 3 ambientes:
- dev - Desenvolvimento
- hmg - Homologação
- prd - Produção
Pipeline
- dev - Compilação
- hmg - Compilação, Testes, Análise Código, Cobertura Código
- prd - Empacotamento
  <br>
- Utiliza o Apache Maven para a automatização da construção.<br>
- A pasta test contêm os testes unitários do projeto utilizando JUnit 4.<br>
- A cobertura do código é realizada através do JaCoCo.<br>