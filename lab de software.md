### TRABALHO DE LABORATORIO DE SOFTWARE
---
## 1. Diferença entre VirtualBox e Docker

O VirtualBox cria máquinas virtuais completas (com sistema operacional próprio), enquanto o Docker usa containers que compartilham o sistema do host, sendo mais leve.

## 2. Tipo de hypervisor do VirtualBox

## É um hypervisor tipo 2 (hosted), pois roda sobre um sistema operacional.

## 3. Por que Docker inicia mais rápido?

Porque não precisa iniciar um sistema operacional completo, apenas o container.

## 4. O que é uma imagem ISO

É um arquivo que contém uma cópia completa de um sistema operacional ou disco, usado para instalação em máquinas virtuais.

## 5. Função do Snapshot

Permite salvar o estado da máquina virtual para voltar a ele depois.

## 6. O que é uma Docker Image

É um modelo pronto que contém tudo necessário para criar um container (app + dependências).

## 7. Quando VirtualBox é melhor que Docker

Quando é necessário rodar sistemas operacionais diferentes ou testar ambientes completos.

## 8. Dados sem volumes no Docker

São perdidos quando o container é deletado.

## 9. Diferença NAT vs Bridge
NAT: VM acessa internet, mas não é facilmente acessada externamente
Bridge: VM se comporta como um computador na rede, com IP próprio

## 10. Guest Additions

São ferramentas instaladas na VM para melhorar desempenho e integração (vídeo, mouse, tela cheia etc.).

## 11. Efemeridade no Docker (implicação prática)

Logs e bancos de dados não devem ficar dentro do container, pois podem ser perdidos. Devem ser armazenados fora (ex: volumes).

## 12. Uso de volumes no Docker

O administrador está garantindo a persistência dos dados, mesmo que o container seja removido.
