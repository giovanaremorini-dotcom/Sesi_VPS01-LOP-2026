# VPS01
## Subtítulo descrição: Verificação Prática Somativa 01
Arquivos gerados durante a avaliação de lógica de programação, algoritimos e fluxogramas

## Tecnologias

|Tecnologia|Utilidade|
|:-:|-|
|Linguágem **C**|Desenvolvimento|
|IDE|Embarcadero **Dev C++**|
|[Draw.io](https://app.diagrams.net/)| Desenha os *fluxogramas*|
|Bloco de notas|*portugol* lógica|

## Como testar
- 1 clone este repositorio
- 2 abra os arquivos .c com o Dev C++
- 3 Precione F11 para compilar executar

## Exemplo de código
```c
#include<stdio.h>
#include<windows.h>
void main(){
	SetConsoleOutputCP(CP_UTF8);
	char nome[20], sexo;
	int idade;
	printf("Digite seu nome, sexo m/f e idade\n");
	scanf(" %s %c %d", &nome, &sexo, &idade);
	if(sexo == 'm'){
		if(idade > 65){
			printf("O atendimento do paciente %s é prioritário", nome);
  		}else{
		  	printf("O atendimento do paciente %s é normal", nome);
  		}
   }else{
      if(idade > 60){
	  	printf("O atendimento do paciente %s é prioritário", nome);
      }else{
      	printf("O atendimento do paciente %s é normal", nome);
	  }
    }
    getch();
}
```
