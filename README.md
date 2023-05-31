<!-- Saudação #include <stdio.h>
#include <stdlib.h>
#include <string.h>

struct Conta {
    int numero;
    char nome[50];
    float saldo;
};

void cadastrarContas(struct Conta contas[], int* numContas) {
    if (*numContas >= 15) {
        printf("Limite de contas atingido.\n");
        return;
    }

    struct Conta novaConta;

    printf("Digite o número da conta: ");
    scanf("%d", &novaConta.numero);

    for (int i = 0; i < *numContas; i++) {
        if (contas[i].numero == novaConta.numero) {
            printf("Já existe uma conta com esse número.\n");
            return;
        }
    }

    printf("Digite o nome do cliente: ");
    scanf(" %[^\n]", novaConta.nome);

    printf("Digite o saldo inicial: ");
    scanf("%f", &novaConta.saldo);

    contas[*numContas] = novaConta;
    (*numContas)++;

    printf("Conta cadastrada com sucesso.\n");
}

void visualizarContasCliente(struct Conta contas[], int numContas) {
    char nomeCliente[50];
    printf("Digite o nome do cliente: ");
    scanf(" %[^\n]", nomeCliente);

    int encontrou = 0;

    for (int i = 0; i < numContas; i++) {
        if (strcmp(contas[i].nome, nomeCliente) == 0) {
            printf("Conta: %d\n", contas[i].numero);
            printf("Nome: %s\n", contas[i].nome);
            printf("Saldo: %.2f\n", contas[i].saldo);
            encontrou = 1;
        }
    }

    if (!encontrou) {
        printf("Nenhuma conta encontrada para o cliente %s.\n", nomeCliente);
    }
}

void excluirContaMenorSaldo(struct Conta contas[], int* numContas) {
    if (*numContas == 0) {
        printf("Não há contas cadastradas.\n");
        return;
    }

    int indiceMenorSaldo = 0;

    for (int i = 1; i < *numContas; i++) {
        if (contas[i].saldo < contas[indiceMenorSaldo].saldo) {
            indiceMenorSaldo = i;
        }
    }

    printf("Conta excluída:\n");
    printf("Conta: %d\n", contas[indiceMenorSaldo].numero);
    printf("Nome: %s\n", contas[indiceMenorSaldo].nome);
    printf("Saldo: %.2f\n", contas[indiceMenorSaldo].saldo);

    for (int i = indiceMenorSaldo; i < (*numContas) - 1; i++) {
        contas[i] = contas[i + 1];
    }

    (*numContas)--;
}

int main() {
    struct Conta contas[15];
    int numContas = 0;
    int opcao;

    do {
        printf("\nMenu de opções:\n");
        printf("1. Cadastrar contas\n");
        printf("2. Visualizar todas as contas de determinado cliente\n");
        printf("3. Excluir a conta com menor saldo\n");
        printf("4. Sair\n");
        printf("Digite a opção desejada: ");
        scanf("%d", &opcao);

        switch (opcao) {
            case 1:
                cadastrarContas(contas, &numContas);
                break;
            case 2:
                visualizarContasCliente(contas, numContas);
                break;
            case 3:
                excluirContaMenorSaldo(contas, &numContas);
                break;
            case 4:
                printf("Saindo do programa...\n");
                break;
            default:
                printf("Opção inválida.\n");
        }
    } while (opcao != 4);

    return 0;
}
-->

<div>
    <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=39FF14&center=falso&vCenter=falso&repeat=verdadeiro&width=435&lines=Ol%C3%A1!+eu+sou+o+Arthur+Augostinho." alt="Typing SVG" /></a>
</div>

#
<!-- Redes Sociais -->

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/invites/contact/?i=1w5tbi5x9ej4s&utm_content=2wtxfzl )
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arthur-augustinho-46076522b)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arthuraugustinho35@gmail.com)
[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/#4533)

#
<!-- Status da conta Arthur Augustinho -->

<div>
  <a href="https://github.com/ArthurAugustinho">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=ArthurAugustinho&show_icons=true&theme=chartreuse-dark"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ArthurAugustinho&layout=compact&theme=chartreuse-dark"/>
</div>

#

## Tecnologias que utilizo

<div>

  #### Linguagens de Programação
  <img align="center" height="30" width="40" src="https://user-images.githubusercontent.com/84246094/134066180-d11880e0-f92f-47da-9f70-1b5d7c39934b.png">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt ="CSS3">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  
  #### Estruturas
  <img align="center" height="30" width="40" src="https://user-images.githubusercontent.com/84246094/180622105-6de2c096-27b5-4469-8189-7a0175a0a903.png">

  #### Bancos de dados
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg">
</div>

#
    

![snake gif](https://github.com/ArthurAugustinho/ArthurAugustinho/blob/output/github-contribution-grid-snake.svg)
    
<!-- 2CCA-000451-5766EBC3 -->
