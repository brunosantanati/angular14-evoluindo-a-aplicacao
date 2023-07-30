# [Angular 14: evoluindo a aplicação](https://cursos.alura.com.br/course/angular-evoluindo-aplicacao)  

## Links

[GitHub repo](https://github.com/alura-cursos/2678-angular-curso2)   
[GitHub aula 1](https://github.com/alura-cursos/2678-angular-curso2/tree/aula-1)   
[GitHub aula 2](https://github.com/alura-cursos/2678-angular-curso2/tree/aula-2)  
[GitHub aula 3](https://github.com/alura-cursos/2678-angular-curso2/tree/aula-3)  
[GitHub aula 4](https://github.com/alura-cursos/2678-angular-curso2/tree/aula-4)  
[GitHub aula 5](https://github.com/alura-cursos/2678-angular-curso2/tree/aula-5)  
[Doc da classe Validators](https://angular.io/api/forms/Validators#description)  
[Como aplicar validação em formulários reativos no Angular?](https://www.alura.com.br/artigos/como-aplicar-validacao-formularios-reativos-angular)   

## Preparando o ambiente e rodando a aplicação

Para instalar o Angular CLI (versão do curso 14.0) é necessário ter o NodeJS (versão utilizada no curso 16.14.2) instalado e usaremos o VSCode como editor de código.  

Para instalar o Angular CLI, abra seu terminal e digite o seguinte comando:  

<code>npm install -g @angular/cli@14.0.0</code>  

Neste curso, vamos evoluir a aplicação Memoteca. Por isso, utilizaremos como base o projeto desenvolvido no curso [Angular 14: aplique os conceitos e desenvolva seu primeiro CRUD](https://cursos.alura.com.br/course/angular-explorando-framework). [Aqui você pode fazer o download do projeto final do curso pré-requisito](https://github.com/alura-cursos/2438-angular-memoteca/archive/refs/heads/aula-6.zip).     

Abra a pasta do projeto e, no terminal, utilize o comando `npm install` para instalar as dependências do projeto.  

Após instalar as dependências, dentro da pasta da aplicação, digite o comando `ng serve` no terminal para executar o projeto.  

Em outro terminal, entre na pasta backend com o comando `cd backend` e digite `npm start` para inicializar a API.  

Certifique-se de que os dois terminais permaneçam ativos durante todo o desenvolvimento para que tanto a aplicação Angular quanto a API estejam sendo executadas.  

Abra seu navegador e digite http://localhost:4200 para acessar a aplicação. Caso queira visualizar os dados da API, acesse no navegador http://localhost:3000.  

[Link do repositório Git](https://github.com/alura-cursos/2678-angular-curso2)  
[Imagens utilizadas no curso](https://caelum-online-public.s3.amazonaws.com/2678-angular-controle-fluxo-navegacao/01/imagens-do-curso.zip)  

## Comandos úteis
```
Comparar conteúdo de duas aulas no Linux (nesse caso entre o projeto inicial e a aula 1):
diff -r 2438-angular-memoteca-aula-6/ 2678-angular-curso2-aula-1/
```
