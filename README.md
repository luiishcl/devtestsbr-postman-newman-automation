# devtestsbr-postman-newman-automation [WIP]
Arquivos da apresentação no DevTestsBR #31


Apŕesentação sob automação de testes no Postman utilizando newman CLI e gerando relatório.
# Pré requisitos:

## API: Star Wars Documentation
- https://swapi.dev/documentation

## Postman: 
- https://www.postman.com/

## Newman:
- https://www.npmjs.com/package/newman#using-newman-cli

## Newman Reporter HTML
- https://www.npmjs.com/package/newman-reporter-htmlextra


## Steps realizados na apresentação:

- Criar collection
- Exportar a collection em um diretório
  - Arquivo em formato .json
 
- Acessar diretório onde está o arquivo de collection

- Executar comando newman via terminal 

   ```newman run swapi-devtestsBR.postman_collection.json -r htmlextra``` 
 
- Verificar resultado no terminal ao final da execução

- Verificar arquivo gerado no diretório de execução.
