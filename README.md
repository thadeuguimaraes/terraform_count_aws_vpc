# Count AWS VPC using Terraform

Este projeto utiliza o Terraform para criar e gerenciar uma VPC (Virtual Private Cloud) na AWS (Amazon Web Services) com 3 subnetes usando "count" que é uma variável que permite que você crie múltiplas instâncias de um recurso específico. Ele conta com os seguintes arquivos:

- main.tf: arquivo principal onde estão as configurações gerais do projeto.
- network.tf: arquivo onde estão as configurações específicas da VPC, como criação de sub-redes e configurações de rotas.
- outputs.tf: arquivo onde estão as saídas do projeto, como o endereço IP da VPC criada.

## Pré-requisitos

- Conta na AWS
- Acesso às credenciais de acesso à conta AWS (Access Key e Secret Key)
- Instalação do Terraform

## Como utilizar

1. Faça o clone deste repositório para sua máquina local.
2. Edite o arquivo main.tf e insira suas credenciais de acesso à conta AWS.
3. Execute o comando terraform init para baixar os módulos necessários.
4. Execute o comando terraform plan para verificar as alterações que serão realizadas.
5. Execute o comando terraform apply para aplicar as alterações.
6. Utilize o comando terraform output para visualizar as saídas do projeto, como o endereço IP da VPC criada.

## Observações

- Certifique-se de que suas credenciais de acesso possuem as permissões necessárias para criar e gerenciar recursos na AWS.
- Utilize o comando terraform destroy para deletar a VPC criada.
