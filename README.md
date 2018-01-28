# Angular
<p align="center"><img width="100px" height="100px" src="http://www.sumanastech.com/themes/st_theme/images/firebase.png"></p>
<br>
<p align="center"><img width="100px" height="100px" src="https://angular.io/assets/images/favicons/favicon-96x96.png"></p>
<br>

# Factory no Angular: Consumindo uma API

<p align="center">
Se você está construindo uma aplicação web, é quase certeza que vai precisar consumir uma API. 

As pessoas que estão iniciando com AngularJS acabam usando o controller para esse tipo de serviço, mas isso não é uma boa prática.

Então eu vou te apresentar a Factory, um tipo de serviço do Angular que vai ser uma mão na roda pra organizar a lógica da sua aplicação.

Você vai aprender nesse video como criar a sua própria factory e consumir uma API REST.

Video da aula:
http://blog.algaworks.com/angular-factory/
https://youtu.be/rzbrYgspVVw
Professor - Rodrigo Waltenberg

</p>

- Nodejs  instalado
- Detalhe, nem precisa do Node JS, pode rodar direto em um container web… tomcat, rodei com xamp
- Banco de dados usado foi o do google - firebase
- https://firebase.google.com
- https://www.goobec.com.br/blog/o-que-e-o-firebase-do-google/
<p align="center">
O Firebase é uma plataforma de desenvolvimento de aplicativos que fornece aos desenvolvedores diversas ferramentas e uma infraestrutura escalável, permitindo a criação de aplicativos de alta qualidade com rapidez.

Atenção especial a este nome: Firebase! Essa é a nova menina dos olhos do Google no que diz respeito às ferramentas mobile. Recentemente, o Firebase ganhou várias melhorias, todas realizadas pela mesma equipe que controla o Google Analytics. Saiba mais:

O Firebase é uma plataforma móvel do Google que ajuda uma agência digital a criar aplicativos e a expandir sua base de usuários. Segundo o Google, o coração do Firebase é o Firebase Analytics, uma solução de análise gratuita e ilimitada. No entanto, vale ressaltar que o Firebase não é totalmente gratuito. Ele oferece um pacote free, porém bem simples. Já outros dois pacotes pagos (a partir de 25 dólares ao mês) têm recursos avançados e bem mais turbinados.

Outra boa notícia é que Firebase pode ser integrado à plataforma do AdWords, o que vai facilitar a vida dos profissionais de mídia online.
</p>

- O Factory é sem dúvidas o tipo mais comum utilizado no mundo Angular e provavelmente o mais fácil e simples de entender.
Um Factory pode retornar qualquer tipo de dado, não existe uma maneira ou padrão explicito que você deva seguir para criar esses dados, você precisa somente retornar algo.


 ```sh
$ composer install
$ node -v
$ npm install
$ npm run serve
```
- https://firebase.google.com
- Criar novo projeto
- Database
- Database com nome de meus filmes
- regras

 ```sh
{
	"rules": {
		"read":true,
		"write":true
	}
 
}
```

- Autor: Renato de Oliveira Lucena
- Desenvolvedor web PHP- Freelance - UNIP system analysis and development , encaro desafios. Studying Laravel and Vue.js.
