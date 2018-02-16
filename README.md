# Quero um Café!

Dados Resultantes de Pesquisa sobre Consumo de Café

## Dados

Os dados estão disponíveis em formato cru e não tratados, conforme respostas
preenchidas pelos entrevistados em formulário específico, e armazenados em
arquivo no formato CSV, localizado em `data/results.csv`.

### Estrutura

| # | Nome               | Descrição                                                     |
| - | ------------------ | ------------------------------------------------------------- |
| 0 | Data e Hora        | Data e hora no formato `DD/MM/AAAA HH:MM:SS`                  |
| 1 | Gênero             | Gênero; enumerável em `Masculino` ou `Feminino`               |
| 2 | Idade              | Intervalo de idade, enumerável conforme `age`                 |
| 3 | Estado Civil       | Situação junto à sociedade, enumerável conforme `marital`     |
| 4 | Nível de Instrução | Nível de estudos, enumerável conforme `instruction`           |
| 5 | Área de Atuação    | Área de ofício; domínio de ocupação                           |
| 6 | Consumo Diário     | Consome café diariamente? _Booleano_ para `Sim` ou `Não`      |
| 7 | Tamanho da Xícara  | Tamanho da xícara durante consumo; enumerável conforme `size` |

## Licença

Os dados da pesquisa estão disponíveis sob a licença CC-BY-SA-4.0, descrita em
[LICENSE](https://github.com/quero-um-cafe/raw-data/blob/master/LICENSE).
