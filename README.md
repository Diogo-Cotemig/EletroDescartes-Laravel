# EletroDescartes-Laravel
Arquivo em laravel, empresa criada a partir de uma atividade do Cotemig - Escola de Tecnologia da Informação

### Eletro-Descarte

- [x] Tela Inicial completa
- [x] Tela de cadastro de usuários
- [x] Tela de login com autenticação (Cadastro e Logount de Usuarios)
- [x] Tela de esqueceu a senha
- [x] Busca eficiente (Metodo Post para facilitar na busca)
- [x] Pontos de descarte em formato de maps
- [x] Sistema de maps
- [x] Informações em dashBoards
- [x] Assistência tecnica
- [x] Tela de histórico do usuário

## Descrição
<!-- Eletro-Descarte é uma empresa com o intuito de combater a poluição da terra devido ao descarte indevido do Lixo eletrônico, nossa empresa acolhe, separa e entrega a matéria prima de volta á empresas que vão reutilizar-las, tudo isso afim de diminuir o consumo excessivo de matéria prima em mineradoras (Ferro, Litio, cobre, ouro) e incentivar ás pessoas a cuidar do futuro da geração, jogando o lixo no local correto -->

## Integrantes
<!-- Liste todos os integrantes do grupo no formato Nome - Matrícula -->
Diogo Rodriguês da Silva - Direção; BackEnd e FrontEnd  - 12302678  \
Marco Antônio Mendes Pines - Planejamento; BackEnd e Planilhas - 12302260  \
Pedro Henrique - Organização; Planilha e FrontEnd - 12303020  \
Gabriel Henrique - Controle de Qualidade; BackEnd e FrontEnd - 12302961 \

## Estrutura de Diretórios (é tipo um Docker: a grosso modo, funciona como Máquina virtual em um sistema, é um contêiner. Põe cada pedaço do sistema em uma máquina virtual diferente)

# 1. Pré-requisitos
Linguagem/Versão utilizada: Blade, php, Html, Css e JavaScript

# Rotas ---
Resources: armazenando os arquivos Blade, Css e Js
Routes.Web: um guia para determinadas paginas do site
public.img: armazena as imagens do site
Database.migrations: armazenando as tabelas
app.Models: cria os objetos da tabela
App.Http.controllers: controla os objetos da tabela

# 2. Instalação
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser  \
npm install  \
install composer  \
composer global require laravel/installer  \

## Clone o repositório
git clone https://diogo-cotemig.github.io/EletroDescarte/


Caso haja falhas, também tem esse repositorio:
https://github.com/Diogo-Cotemig/EletroDescartes-Laravel
## Instale as dependências (se houver)
php artisan config:clear

### Execute o projeto (usar esses codigos ao mesmo tempo)
npm run dev  \
php artisan serve

## Acesso
URL local: [http://localhost:3000](http://127.0.0.1:8000/)

