# Rest


- Representational State Transfer
- O Conceito REST foi abordado por Roy Fielding na sua tese de mestrado em 2000
- Originalmente se chamava HTTP Object model
- Stateless
  - Requisições indepentendes
- Requisições podem ser cacheadas
- Rest é baseada em recursos, todas as ações tem de ser realizadas baseadas nisto
- Granularidade
  - ex: ``` https://api.spotify.com/albums/12321```
  - O dentro da api vou buscar albuns e dentro dele uma faixa que seja sinalizado de acordo com essa identificação

| Taks             | Metodo | Path    |
| ---------------- | ------ | ------- |
| Criar nova faixa | POST   | /tracks |
| Deletar uma faixa| DELETE | /tracks/{id}|
| Listar uma faixa especifica | GET | /tracks/{id}|
| Atualizar uma faixa | PUT | /tracks/{id}|
| Pesquisar por faixas| GET | /tracks |

- Neste caso, o recurso é `track`
 
