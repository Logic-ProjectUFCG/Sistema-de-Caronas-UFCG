# Sistema de Caronas UFCG
### Projeto de Modelagem em Alloy para Lógica para Computação

Este repositório contém a modelagem formal de um **Sistema de Agendamento de Caronas para a UFCG**, desenvolvido como projeto para a disciplina de Lógica para Computação.

Para promover o transporte sustentável e otimizar a mobilidade na UFCG, este projeto utiliza a linguagem Alloy para criar um modelo lógico e seguro de um sistema de caronas. O foco é definir formalmente as regras do sistema — quem pode participar, como as viagens devem funcionar e como evitar conflitos — garantindo que a base do serviço seja robusta, confiável e segura para toda a comunidade acadêmica.

<br>

## 📜 Regras Fundamentais do Sistema

O modelo lógico garante que as seguintes regras sejam sempre verdadeiras:

* **Validação de Usuários:** Apenas alunos com frequência em aula certificada são considerados `Habilitados` para participar do sistema.
* **Logística dos Trajetos:** Toda carona deve ter como origem ou destino, obrigatoriamente, o campus da UFCG. Viagens entre bairros não são permitidas.
* **Capacidade da Carona:** Cada carona possui 1 motorista e uma capacidade de 1 a 4 passageiros.
* **Agendamento:** Um usuário não pode participar de múltiplas caronas (seja como motorista ou passageiro) que ocorram no mesmo intervalo de tempo.

<br>

## 🎯 Objetivos do Projeto

* **Modelar um sistema seguro:** Garantir que apenas membros verificados da comunidade acadêmica possam participar.
* **Definir a lógica dos trajetos:** Formalizar as regras de origem e destino das caronas, centralizadas no campus.
* **Analisar restrições:** Verificar a consistência de regras complexas, como limites de passageiros e conflitos de horário.
* **Validar propriedades desejáveis:** Usar asserções para testar se o sistema incentiva boas práticas, como o agrupamento de usuários por região.

<br>

## 🚀 Como Executar

1.  Baixe e instale o **[Alloy Analyzer](https://alloytools.org/download.html)**.
2.  Abra o arquivo `.als` contido neste repositório.
3.  Clique no botão **Execute** para que o Alloy encontre uma instância que satisfaça todas as regras do modelo.

<br>

## 👥 Equipe

| Nome do Integrante                                | Perfil no GitHub                                   |
| ------------------------------------------------- | -------------------------------------------------- |
| *<ins>Anne Grazieli Marques Silva</ins>* | *<ins>[@annegmsilva](https://github.com/annegmsilva)</ins>* |
| *<ins>Bianka Vitória Silva Lima</ins>* | *<ins>[bianka-lima](https://github.com/bianka-lima)</ins>* |
| *<ins>João Lima</ins>* | *<ins>[@limajoaohs](https://github.com/limajoaohs)</ins>* |
| *<ins>Joyce Vitória Nascimento Rodrigues</ins>* | *<ins>[@joycevnr](https://github.com/joycevnr)</ins>* |
| *<ins>Maria Eduarda Capela Cabral Pinheiro da Silva</ins>* | *<ins>[@Eduarda-Cabral](https://github.com/Eduarda-Cabral)</ins>* |

<br>

## 📘 Componente Curricular

* **Disciplina:** Lógica para Computação
* **Período:** 2025.1
* **Professor:** Tiago Lima Massoni
