# Nome do Projeto

## Descrição

 Este projeto visa desenvolver um sistema de gerenciamento de acervo para
 bibliotecas, permitindo a catalogação, rastreamento e controle. Ideal para
 bibliotecas de todos os tamanhos, ele permite gerenciar empréstimos e
 estoque em tempo real, garantindo maior eficiência e organização. Utilizará a
 metodologia ágil e prática de DevOps integradas ao GitHub, a arquitetura do
 software seguirá o padrão Model-View-Controller (MVC) e incorporará o padrão
 de projeto Factory Method para garantir uma base de código robusta e
 escalável. O desenvolvimento será feito na linguagem C#.

## Índice

1. [Objetivos do Projeto](#objetivo)
2. [Requisitos](#requisitos)
   1. [Requisitos Funcionais](#rf)
   2. [Requisitos Não Funcionais](#rnf)
3. [Diagramas UML](#uml)
   1. [Diagrama de Casos de Uso](#uc)
   2. [Diagrama de Classe](#classe)
4. [Estrutura do Projeto](#estrutura)
5. [Contribuição](#contribuição)
6. [Licença](#licença)
7. [Contato](#contato)


## Requisitos ou História de Usuário

   ### Requisitos Funcionais
   
  1. Gerenciamento do Catálogo de Livros 
  Adicionar, editar e remover registros de livros.
  Permitir a listagem dos livros no acervo da biblioteca
  Registrar informações detalhadas dos livros, como título, autor, ano de
  publicação e localização física.
  2. Controle de Acervo
  Gerenciar movimentações de estoque, como aquisições de novos
  exemplares ou baixa de exemplares danificados ou perdidos.
  Gerar alertas para itens com estoque baixo ou esgotado.
  3. Empréstimos
  Registrar empréstimos de livros a usuários cadastrados.
  Controlar prazos de devolução e gerar notificações para devoluções
  atrasadas.
  4. Gestão de Usuários
  Cadastrar usuários para realizarem empréstimos de livros.
  5. Notificações e Alertas
  Enviar e-mails ou mensagens sobre devoluções pendentes, reservas
  disponíveis e alertas de estoque.
  Notificar administradores sobre eventos importantes, como livros
  danificados ou estoque esgotado.

   ### Requisitos Não Funcionais 
  1. Desempenho
 Osistema deve suportar a consulta de pelo menos 10.000 registros de
 livros em menos de 2 segundos.
 O tempo de resposta para operações comuns (como empréstimos ou
 devoluções) deve ser inferior a 1 segundo.
 2. Usabilidade
 Ainterface deve ser intuitiva e acessível, com opções claras para busca,
 cadastros e empréstimos.
 3. Confiabilidade
 Osistema deve ser capaz de operar 24/7, com disponibilidade mínima
 de 99,9% durante o horário de funcionamento da biblioteca.
 4. Segurança
 Osistema deve implementar autenticação para acesso.
 5. Escalabilidade
 Osistema deve ser capaz de lidar com o aumento do número de livros,
 usuários e transações sem comprometer o desempenho.
 Deve permitir integração futura com outros sistemas (ex.: sistemas de
 pagamento, bases de dados bibliográficas).
 6. Compatibilidade
 O software deve funcionar em sistemas operacionais populares, como
 Windows, macOS e Linux, para a versão desktop.
 7. Portabilidade
 Pode suportar integração com dispositivos móveis, como smartphones e
 tablets.
 8. Manutenibilidade
 O código deve ser modular e bem documentado para facilitar
 atualizações e correções.
 Deve haver um sistema de suporte para reportar e corrigir bugs em até
 48 horas.

## Diagramas UML
   
   ### Diagrama de Casos de Uso
    
   ![git casos](https://github.com/user-attachments/assets/f95f17a0-73c4-4827-a6d8-0a6f14f12b85)

   ### Diagrama de Classe

   ![uml](https://github.com/user-attachments/assets/a3cbee5c-4e11-4c9d-aeb2-02650c52102a)

## Estrutura do Projeto 

- `src/`: https://github.com/A3-Padrao-de-projetos/Sistema-de-biblioteca
  
## Tecnologias Utilizadas
- Visual Studio
- C#

## Instruções de Instalação
1. Clone o repositório:
   ```sh
   git clone https://github.com/A3-Padrao-de-projetos/Sistema-de-biblioteca.git
## Licença
 Licença MIT

## Contato

![arthur](https://github.com/user-attachments/assets/c7dfe362-194d-4e12-83f7-97f3493640cb)Arthur Veríssimo Gonçalves de Abreu - RA 4231924746 - arthurvga05@gmail.com
 <br>
![bryan caetano ft](https://github.com/user-attachments/assets/5b7ae0d5-e112-4585-bce6-706bfbb9503e) Bryan Caetano Sena Silva - RA 4231922321 - bryancaetano2010@gmail.com 
<br>
![hebert](https://github.com/user-attachments/assets/86ac5803-ff63-4eb5-b55f-c9c94a5fab34)Hebert Magalhães Soares - RA 4231925578 - hebertms2009@hotmail.com
<br>
![samuel](https://github.com/user-attachments/assets/4c2f97cc-8f71-4913-b225-71d1d1f5b3af) Samuel Silva Almeida - RA 4231922319 - smlsilvaalmeida@gmail.com





