# Terraform

## O que é Terraform?

Terraform é uma ferramenta de Infraestrutura como Código, conhecida como IaC, criada pela HashiCorp.

Ela permite criar, alterar e versionar recursos de infraestrutura por meio de arquivos de configuração.

## Infraestrutura como Código

Infraestrutura como Código é a prática de gerenciar infraestrutura usando código, em vez de processos manuais.

Com IaC, é possível versionar e automatizar recursos como:

- Máquinas virtuais
- Redes
- Sub-redes
- Firewalls
- Bancos de dados
- Load balancers
- Recursos em cloud

## Benefícios do Terraform

- Automação de infraestrutura
- Padronização de ambientes
- Redução de erros manuais
- Reutilização de configurações
- Versionamento da infraestrutura
- Facilidade para criar ambientes em cloud

## Exemplo básico de uso

```hcl
provider "aws" {
  region = "us-east-1"
}

resource "aws_instance" "servidor_exemplo" {
  ami           = "ami-123456"
  instance_type = "t2.micro"
}

Relação com DevOps

Terraform é muito utilizado em ambientes DevOps porque facilita a automação,
a padronização e o controle da infraestrutura usada pelas aplicações.
