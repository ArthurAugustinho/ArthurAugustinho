<!-- Saudação -->

<div>
    <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=39FF14&center=falso&vCenter=falso&repeat=verdadeiro&width=435&lines=Ol%C3%A1!+eu+sou+o+Arthur+Augustinho." alt="Typing SVG" /></a>
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
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=ArthurAugustinho&hide=contribs,prs&theme=chartreuse-dark"/>
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ArthurAugustinho&layout=compact&theme=chartreuse-dark"/>
</div>

#

## Tecnologias que utilizo

<div>

  #### Linguagens de Programação
  <img align="center" height="30" width="40" src="https://user-images.githubusercontent.com/84246094/134066180-d11880e0-f92f-47da-9f70-1b5d7c39934b.png">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt ="CSS3">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg">
  
  #### Estruturas
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-plain.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-original.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angularjs/angularjs-original.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original-wordmark.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg">

  #### Bancos de dados
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg">
  <img align="center" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg">
</div>

#
    
<!--[snake gif](https://github.com/ArthurAugustinho/ArthurAugustinho/blob/output/github-contribution-grid-snake.svg) -->
    
<!-- 2CCA-000451-5766EBC3 -->

<!-- #include<stdio.h>
#include<stdlib.h>
#include<locale.h>

// Criando uma estrutura de nó da lista
typedef struct Node {
    char data;
    struct Node* next;
} Node;

// Função para INCERIR um nó na lista em ordem alfabética
void insertInOrder(Node** head, char value) {
    Node* newNode = (Node*)malloc(sizeof(Node));
    newNode->data = value;
    newNode->next = NULL;

    if (*head == NULL || value <= (*head)->data) {
        newNode->next = *head;
        *head = newNode;
    } else {
        Node* current = *head;
        while (current->next != NULL && current->next->data < value) {
            current = current->next;
        }
        newNode->next = current->next;
        current->next = newNode;
    }
}

// Função para REMOVER o nó da lista
void removeNode(Node** head, char value) {
    if (*head == NULL) {
        return;
    }

    if ((*head)->data == value) {
        Node* temp = *head;
        *head = (*head)->next;
        free(temp);
        return;
    }

    Node* current = *head;
    while (current->next != NULL && current->next->data != value) {
        current = current->next;
    }

    if (current->next == NULL) {
        return;
    }

    Node* temp = current->next;
    current->next = current->next->next;
    free(temp);
}

// Função para IMPRIMIR a lista
void printList(Node* head) {
    printf("Lista: ");
    while (head != NULL) {
        printf("%c ", head->data);
        head = head->next;
    }
    printf("\n");
}

int main() {
    Node* head = NULL;
    char choice, value;

    do {
        printf("Escolha uma operação:\n");
        printf("1 -> Inserir letras na lista\n");
        printf("2 -> Remover letras da lista\n");
        printf("3 -> Imprimir os caracteres da lista\n");
        printf("4 -> Sair\n");
        scanf(" %c", &choice);

        switch (choice) {
            case '1':
                printf("Digite a letra a ser inserida: ");
                scanf(" %c", &value);
                insertInOrder(&head, value);
                break;
            case '2':
                printf("Digite a letra a ser removida: ");
                scanf(" %c", &value);
                removeNode(&head, value);
                break;
            case '3':
                printList(head);
                break;
            case '4':
                // Libera a memória alocada
                while (head != NULL) {
                    Node* temp = head;
                    head = head->next;
                    free(temp);
                }
                break;
            default:
                printf("Escolha inválida!\n");
        }
    } while (choice != '4');

    return 0;
}
 -->
