
# Exemplo de criacao de AWS Lambda usando Terraform

Este código é apenas um exemplo de criação de uma AWS Lambda e suas respectivas role e policy utilizando Terraform





## Autores

- [@gutrovalim](https://www.github.com/gutrovalim)


## Deploy

Para fazer o a aplicação do terraform execute para inicializar o Terraform

```bash
  terraform init
```

Depois execute o código abaixo para gerar o plano de execução do Terraform

```bash
  terraform plan -out tfplan
```

Por fim execute o código abaixo para aplicar o plano gerado no passo anterior

```bash
  terraform apply tfplan
```

## Limpeza

Para excluir os artefatos criados usando esse plano do Terraform execute o código abaixo:

```bash
  terraform destroy
```
