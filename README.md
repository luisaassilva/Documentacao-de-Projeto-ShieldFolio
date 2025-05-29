# ShieldFolio

Link do pdf ()
## Documentação de Projeto

**Versão 1.0**      

Projeto de sistema elaborado pelo(s) aluno(s):
Alunas Participantes:
* Luisa Clara de Paula Lara Silva
* Maria Clara de Oliveira Silva
* Debora Campos Sigaud
Data da criação 20-05-2025

## Tabela de Conteúdo
1. [Introdução](#1-introdução)         
2. [Modelos de Usuário e Requisitos](#2-modelos-de-usuário-e-requisitos)             
   2.1 [Descrição de Atores](#21-descrição-de-atores)          
   2.2 [Modelo de Casos de Uso e Histórias de Usuários](#22-modelo-de-casos-de-uso-e-histórias-de-usuários)               
   2.3 [Diagrama de Sequência do Sistema e Contrato de Operações](#23-diagrama-de-sequência-do-sistema-e-contrato-de-operações)            
3. [Modelos de Projeto](#3-modelos-de-projeto)           
   3.1 [Arquitetura](#31-arquitetura)           
   3.2 [Diagrama de Componentes e Implantação](#32-diagrama-de-componentes-e-implantação)          
   3.3 [Diagrama de Classes](#33-diagrama-de-classes)           
   3.4 [Diagramas de Sequência](#34-diagramas-de-sequência)          
   3.5 [Diagramas de Comunicação](#35-diagramas-de-comunicação)           
   3.6 [Diagramas de Estados](#36-diagramas-de-estados)           
4. [Modelos de Dados](#4-modelos-de-dados)


## Histórico de Revisões

| Nome | Data | Razões para Mudança | Versão |
|---|---|---|---|
| Luisa Clara | 29/05/25 | Criação do documento e escrita do docs e md| 1.0 |
| Maria Clara | 29/05/25 | criação de diagramas casos de uso e sequencia| 1.0 |
| Debora | 29/05/25 | criação de diagramas comunicação e estado | 1.0 |

## 1. Introdução
Este documento agrega: 
1) a elaboração e revisão de modelos de domínio
2) 2) modelos de projeto para o sistema ShieldFolio.
   3) 
Atualmente, artistas digitais enfrentam desafios significativos ao compartilhar suas obras online, especialmente em relação à proteção contra o uso não autorizado por Inteligência Artificial. Muitos sistemas de portfólio não oferecem mecanismos eficazes de proteção ou controle de privacidade, deixando as imagens vulneráveis a uso indevido, cópia ou extração por modelos de IA generativa. O sistema proposto é uma plataforma web voltada à exposição e gerenciamento de portfólios artísticos, com foco em segurança de imagens, organização personalizada e integração social.


## 2. Modelos de Usuário e Requisitos              

### 2.1 Descrição de Atores

* Artistas: Usuário principal do sistema. Pode criar conta, enviar imagens com proteção anti-IA, organizá-las em pastas, aplicar tags, definir níveis de privacidade, e compartilhar em redes sociais. Marcar se gostaria de ver números de likes, salvos ou visualização.

* Administrador do Sistema: Responsável pela manutenção, moderação de conteúdo (como denúncias ou violação das políticas), gerenciamento de usuários e configurações do sistema.

* Visitante público (sem conta): Qualquer usuário não autenticado que acessa o site. Pode visualizar imagens públicas e navegar por portfólios (exceto os protegidos).

* Usuário logado: conseguem curtir obras, salvar obras, visualizar conteúdos privados que o artista tenha marcado.

### 2.2 Modelo de Casos de Uso e Histórias de Usuários  

#### Casos de Uso

* UC-01 -> Como usuário gostaria de me cadastrar para que tenha acesso a novas funcionalidades
* UC-02 -> Como artista gostaria de Adicionar tags às imagens para que facilite a pesquisa de minhas obras
* UC-03 -> Como artista gostaria de me criar pasta de portifólio para facilitar a organização de minha obras
* UC-04 -> Como artista gostaria de compartilhar em redes sociais para centralizar como poderia compartilhar minhas obras 
* UC-05 -> Como artista gostaria que minha obrar ao ser publicada já esteja com proteção Anti-Ia para que não seja necessário utilizar outro software que faça isso
* UC-06 -> Como artista gostaria de publicar imagens com senhas de privacidade para que consiga filtrar a visualização de certas obras através de apenas seguidores visualizarem ou apenas pessoas com senhas corretas
* UC-07 -> Como visitante gostaria de visualizar imagens públicas para que o artista não seja prejudicado de apenas usuários com senha possa visualiza-la
* UC-08 -> Como administrador gostaria gerenciar usuários para poder excluir contas
* UC-09 -> Como administrador gostaria de gerenciar denúncias para que seja possível verificar se a denúncia esta correta ou não.
* UC-10 -> Como administrador gostaria de remover conteúdos que infringem regras da comunidade para que a comunidade esteja sempre dentro das regras
* UC-11 -> Como usuário logado gostaria de favoritar uma imagem para salvá-la para que não precise procurar ela facilitando o acesso a obras que gostei
* UC-12 -> Como usuário logado gostaria de seguir meu artistas preferidos para que facilite minha busca pelos artistas que gosto
* UC-12 -> Como usuário logado dar likes em imagens para que o artista compreenda quando gosto de uma obra


