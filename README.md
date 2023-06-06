<!-- Saudação -#include <stdio.h>

typedef struct {
    char sexo;
    float altura;
    int idade;
    char corOlhos;
} Habitante;

int main() {
    Habitante habitantes[50];
    int i, qtdCastanhosAlturaMaior160 = 0;
    int maiorIdade = 0;
    int qtdFemininoIdade20a45OlhosVerdesAlturaMenor170 = 0;
    int qtdHomens = 0;
    float somaIdadeCastanhosAlturaMaior160 = 0.0;
    float mediaIdadeCastanhosAlturaMaior160 = 0.0;

    // Leitura dos dados
    for (i = 0; i < 50; i++) {
        printf("Habitante %d:\n", i+1);
        printf("Sexo (M/F): ");
        scanf(" %c", &habitantes[i].sexo);
        printf("Altura (em metros): ");
        scanf("%f", &habitantes[i].altura);
        printf("Idade: ");
        scanf("%d", &habitantes[i].idade);
        printf("Cor dos olhos (A - azuis, V - verdes, C - castanhos): ");
        scanf(" %c", &habitantes[i].corOlhos);
        printf("\n");

        // Cálculos das estatísticas
        if (habitantes[i].corOlhos == 'C' && habitantes[i].altura > 1.6) {
            somaIdadeCastanhosAlturaMaior160 += habitantes[i].idade;
            qtdCastanhosAlturaMaior160++;
        }

        if (habitantes[i].idade > maiorIdade) {
            maiorIdade = habitantes[i].idade;
        }

        if ((habitantes[i].sexo == 'F' && habitantes[i].idade >= 20 && habitantes[i].idade <= 45) ||
            (habitantes[i].corOlhos == 'V' && habitantes[i].altura < 1.7)) {
            qtdFemininoIdade20a45OlhosVerdesAlturaMenor170++;
        }

        if (habitantes[i].sexo == 'M') {
            qtdHomens++;
        }
    }

    // Cálculo da média de idade
    if (qtdCastanhosAlturaMaior160 > 0) {
        mediaIdadeCastanhosAlturaMaior160 = somaIdadeCastanhosAlturaMaior160 / qtdCastanhosAlturaMaior160;
    }

    // Cálculo do percentual de homens
    float percentualHomens = (float)qtdHomens / 50 * 100;

    // Impressão dos resultados
    printf("Média de idade das pessoas com olhos castanhos e altura superior a 1,60 m: %.2f\n",
           mediaIdadeCastanhosAlturaMaior160);
    printf("Maior idade entre os habitantes: %d\n", maiorIdade);
    printf("Quantidade de indivíduos do sexo feminino com idade entre 20 e 45 anos ou que tenham olhos verdes e altura inferior a 1,70 m: %d\n",
           qtdFemininoIdade20a45OlhosVerdesAlturaMenor170);
    printf("Percentual de homens: %.2f%%\n", percentualHomens);

    return 0;
}
->

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
