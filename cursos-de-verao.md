---
layout: default
title: Introdução ao Desenvolvimento de Sistemas Web com PHP
permalink: /curso-php/
---

# Curso de Verão 2017

## Introdução ao Desenvolvimento de Sistemas Web com PHP

O intuito deste curso é abordar o desenvolvimento de sistemas web utilizando a linguagem PHP. Inicialmente será abordado a linguagem PHP e os conceitos de Orientação a Objetos. Após a parte introdutória, será abordado banco de dados MySQL e como utilizá-lo em nossa aplicação PHP, a construção de páginas dinâmicas e o uso de frameworks MVC como Laravel para desenvolver um sistema web.

**Pré-Requisitos:** Conhecimento básico de Web e de programação.

**Público:** Profissionais da área de informática e interessados no desenvolvimento de sistemas Web e na linguagem PHP.

**Carga horária:** 40 horas

**Horário:** Segunda, Terça, Quarta, Quinta e Sexta das 19:00 às 23:00;

**Sala:** CEC-06

**Período Inicial:** 06/02/2017

**Período Final:** 17/02/2017

## Aulas

#### Aula 1
* [Exercícios de lógica](https://gist.github.com/mrezende/788289758ec5139d6300a77f21c3dcfe)

#### Aula 2

* [Exercícios de OO](https://gist.github.com/mrezende/0e766190493fd6bc0b8b7ffdd7e99300)

#### Aula 3
* [Exercícios de agregação, associação e composição](https://gist.github.com/mrezende/a8ca3c7ea47aba794cb25ce30f552566)
* [Exercícios de métodos](https://gist.github.com/mrezende/5ad5a4488b6b16f479114d0063366d51)
* [Exercícios de construtores](https://gist.github.com/mrezende/3b21b6ee2b34e3d12e0bacefc9314f44)

#### Aula 4
* [Exercícios de arrays](https://gist.github.com/mrezende/36ef5601db040e7c3fad1ec8113aa8ee)
* [Exercícios de atributos e métodos de classe](https://gist.github.com/mrezende/a81a3c7fdd2c7b9f76429871da692ce2)

#### Aula 5
* [Exercícios de herança](https://gist.github.com/mrezende/c2d6a2a873c6e0377c2fecc897521004)

#### Aula 6
* [Exercícios do primeiro projeto com Laravel](https://gist.github.com/mrezende/1c72b77db845696da8bce55aea00acc3)


#### Aula 7
* [Exercícios sobre views](https://gist.github.com/mrezende/59f78c082accf6ad57fcef8ded32fc28)
* [Exercícios sobre layout](https://gist.github.com/mrezende/e06fd1657954f8136210cf2464c690f6)


#### Aula 8
* [Exercícios sobre Eloquent](https://gist.github.com/mrezende/af431c5ce7380563968bda5e64c223e0)
* [Exercícios sobre controller](https://gist.github.com/mrezende/5ec5490ef8343634162d1d06389d515a)
* [Exercícios sobre validacao](https://gist.github.com/mrezende/fabfdb0d896899e3240768edab4c41c1)

## Alunos

Nome | Github profile
------------- | --------------
Airton Vilela | [vilela1966](https://github.com/vilela1966)
André César de Jesus Gaspar | [tonycasper](https://github.com/tonycasper)
António Martins Miranda | [mirstation](https://github.com/MirStation)
Bartira Kio Kamiya | [bkamiya](https://github.com/bkamiya)
Caio Augusto | [caionog1](https://github.com/Caionog1)
Eduardo Alencar Lino da Silva | (eduardoalencarlino)[https://github.com/eduardoalencarlino]
Ezequias Dos Reis da Silva | [ezequias-silva](https://github.com/ezequias-silva)
Fabio Frascino | [ffrascino](https://github.com/ffrascino)
Fabio Glock Bellegard | [fabiobellegard](https://github.com/fabiobellegard)
Felipe Fonseca Trindade | [felipeftrindade](https://github.com/felipeftrindade)
Gabriel Nunes da Silva | [gabrielns](https://github.com/gabrielns)
Henrique Ramos | [maza-php16](https://github.com/maza-php16)
Hercules Freitas | [hrvfreitas](https://github.com/hrvfreitas)
Luiz Antonio Campos | [luiz7686](https://github.com/luiz7686)
Luis Carlos de Souza | [luiscarlosdesouza](https://github.com/luiscarlosdesouza)
Luiz Destefano | [luizdestefano](https://github.com/luizdestefano)
Luiz Henrique | [luizhata](https://github.com/luizhata)
Marcelo Modesto | [marcelomodesto](https://github.com/marcelomodesto)
Raphael Monteiro da Silva Ettel | [raphaelettel](https://github.com/raphaelettel)
Renan Barbosa | [renan03barbosa](https://github.com/renan03barbosa)
Renato C. Mascheti | [Renat89](https://github.com/Renat89)
Ruan Silveira dos Santos | [ruansilveira](https://github.com/ruansilveira)
Vinicius de Athaydes Sanfilippo | [viniciussanfilippo](https://github.com/viniciussanfilippo)
Wagner de Oliveira Filho | [wagnerdeoliveira](https://github.com/wagnerdeoliveira)


## Projeto Final

### Projeto 1 - Curso de verão

Criar um sistema de cadastro de alunos nos cursos de verão. Basicamente as entidades são:

* Aluno
* Professor
* Curso
* Turma
* Inscricao

![Summer School Entity Relationship Diagram](http://www.k19.com.br/curso-verao.png)

##### Entrega

Para entrega do sistema foi provindenciado uma tarefa no Github Classroom. Basta clicar no link abaixo:

[Tarefa curso de verão](https://classroom.github.com/assignment-invitations/8fbdc51169d0002ad503d7883504261f)

Após clicar na tarefa, basta seguir os passos abaixo:

1 - Fazer o download do repositório criado:

```sh
git clone https://github.com/summer-school-ime-usp-2017/final-project-curso-verao-<USUARIO_GITHUB>.git

```

2 - Após o download, entre na pasta do projeto e execute o comando abaixo para instalar as bibliotecas:

```sh
composer install
```

3 - Copie o arquivo **.env.example** para um arquivo chamado **.env**.

```sh
# linux
cp .env.example .env

#windows
copy .env.example .env
```

4 - Gere a chave e limpe a configuração:

```sh
php artisan key:generate

php artisan config:clear
```

5 - Execute o servidor e verifique que está rodando normalmente:

```
php artisan serve
```

Acesse http://localhost:8000.

Após executar estes passos, basta desenvolver o projeto e enviar todas as alterações para o Github até dia 05 de Março de 2017.

### Projeto 2 - Laboratório

Criar um sistema de cadastro de pedidos de exames. Neste sistema, teremos basicamente 4 entidades:

* Paciente
* Médico
* Exame
* Pedido

![Laboratory Entity Relationship Diagram](http://www.k19.com.br/laboratorio.png)

##### Entrega

Para entrega do sistema foi provindenciado uma tarefa no Github Classroom. Basta clicar no link abaixo:

[Tarefa laboratório](https://classroom.github.com/assignment-invitations/a9ef6c927c5fac38672cb0d65fb801c4)

Após clicar na tarefa, basta seguir os passos abaixo:

1 - Fazer o download do repositório criado:

```sh
git clone https://github.com/summer-school-ime-usp-2017/final-project-laboratorio-<USUARIO_GITHUB>.git

```

2 - Após o download, entre na pasta do projeto e execute o comando abaixo para instalar as bibliotecas:

```sh
composer install
```

3 - Copie o arquivo **.env.example** para um arquivo chamado **.env**.

```sh
# linux
cp .env.example .env

#windows
copy .env.example .env
```

4 - Gere a chave e limpe a configuração:

```sh
php artisan key:generate

php artisan config:clear
```

5 - Execute o servidor e verifique que está rodando normalmente:

```
php artisan serve
```

Acesse http://localhost:8000.

Após executar estes passos, basta desenvolver o projeto e enviar todas as alterações para o Github até dia 05 de Março de 2017.

### Projeto 3 - Livre

Crie um sistema de cadastro utilizando o Laravel, o contexto da aplicação pode ser livre. O único requisito é ter no mínimo **4 (quatro) entidades** e pelo menos **2 (duas) entidades** devem relacionar-se entre si através de um relacionamento **1-1**, **1-N** ou **N-N**.

##### Entrega

Para entrega do sistema foi provindenciado uma tarefa no Github Classroom. Basta clicar no link abaixo:

[Tarefa projeto livre](https://classroom.github.com/assignment-invitations/f94b980a36bd4f44c41248ac93d7c889)

Após clicar na tarefa, basta seguir os passos abaixo:

1 - Fazer o download do repositório criado:

```sh
git clone https://github.com/summer-school-ime-usp-2017/final-project-projeto-livre-<USUARIO_GITHUB>.git
```

2 - Após o download, entre na pasta do projeto e execute o comando abaixo para instalar as bibliotecas:

```sh
composer install
```

3 - Copie o arquivo **.env.example** para um arquivo chamado **.env**.

```sh
# linux
cp .env.example .env

#windows
copy .env.example .env
```

4 - Gere a chave e limpe a configuração:

```sh
php artisan key:generate

php artisan config:clear
```

5 - Execute o servidor e verifique que está rodando normalmente:

```
php artisan serve
```

Acesse http://localhost:8000.


Após executar estes passos, basta desenvolver o projeto e enviar todas as alterações para o Github até dia 05 de Março de 2017.

**Prazo máximo para entrega:** 05/Março

**Divulgação das notas finais:** 10/Março

## Avaliação Final

```
NF: (N1 + 3 * N2)/4

NF >= 5 && FM >= 85% => aprovado

NF: Nota Final, [0, 10]
FM: Frequência mínima, [0, 100%]
N1: Nota dos exercícios vistos em aula, [0, 10]
N2: Nota do Projeto final, [0, 10]

```

# Instalação Laravel Linux

```sh
composer global require "laravel/installer"

echo 'export PATH="$PATH:$HOME/.config/composer/vendor/bin"' >> ~/.bashrc

```

# Instalação Laravel windows

By @maza-php16

Instalar o XAMPP. Basta acessar: https://www.apachefriends.org/pt_br/index.html

Instalar o composer a partir do site https://getcomposer.org/

Basta instalar o Laravel utilizando as dicas deste site:
http://guiferreiracode.com/2015/08/instalacao-do-laravel-5-no-windows-curso-gratis-laravel-de-a-a-z.html


## Referências

* [Conteúdo sobre OO e MVC, apostilas K11, K31 e K32](http://www.k19.com.br)
* [PHP](http://php.net/manual/en/langref.php)
* [Guia prático do GIT](http://rogerdudler.github.io/git-guide/index.pt_BR.html)
* [Bootstrap](http://getbootstrap.com/)
* [Laravel](https://laravel.com/docs/5.4/)
* [Sass Basic](http://sass-lang.com/guide)
