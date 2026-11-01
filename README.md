# ChupinVet – QA, Compliance & Tests (Sprint 4)

- **Azure Boards (testes manuais):** https://dev.azure.com/ChupinVet/ChupinVet
- **Vídeo da automação de testes:** https://www.youtube.com/watch?v=03_GnB1PsMU

## Testes automatizados (Postman)
Ferramenta: Postman. Alvo: https://javachallenge.onrender.com

| ID | Caso | Verificações |
|---|---|---|
| AT-01 | Cadastro de Responsável e login válido | 201 e id; 200, token JWT e papel Responsável |
| AT-02 | Login com senha incorreta | 401 e nenhum token |
| AT-03 | Cadastro e consulta de Pet | 201, dono correto; 200 com os dados do pet |
| AT-04 | Registro no Diário | 201 e id; 200 e lista com o registro |

## Arquivos
- `ChupinVet_Testes_Automatizados.postman_collection.json`: coleção com os 4 casos e as verificações
- `ChupinVet_Producao.postman_environment.json`: ambiente apontando para a API em produção

## Como executar
1. Importar no Postman os dois arquivos `.json` desta pasta.
2. Selecionar o environment "ChupinVet - Producao (Render)".
3. Abrir `https://javachallenge.onrender.com/swagger-ui/index.html` para acordar a API.
4. Botão direito na coleção > Run collection > Start run.

## Integrantes
Agatha Yie Won Yun, Ana Claudia Fernandes Martins, Samantha Faruolo Galdi, Vitor Fria Dalmagro
