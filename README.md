# Desafios da "Jornada DevOps de Elite"

## Testing Terraform for Digital Ocean

Arquivos .tf criados para a estrutura de um cluster k8s em cloud provider (obs.: porém não utilizado a conta DigitalOcean, ausência de cartão de crédito internacional)

##
##

### Passos necessários:

- Copiar token e gerar SSH da DigitalOcean account;

- Substituir no arquivo 'terraform.tfvars'

- executar: `terraform init`

- executar: `terraform apply`

- opcional: copiar 'kube_config.yaml' para '/.kube/config' para usar kubectl


