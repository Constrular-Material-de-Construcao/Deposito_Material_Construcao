# Requisitos Não Funcionais

Os requisitos não funcionais descrevem como o sistema deve se comportar.

---

## RNF01 – Desempenho
- O sistema deve responder requisições em até 2 segundos
- O sistema deve suportar múltiplos usuários simultâneos

---

## RNF02 – Segurança
- O sistema deve exigir autenticação para acesso
- As senhas devem ser armazenadas de forma criptografada
- O sistema deve restringir acesso com base no perfil do usuário

---

## RNF03 – Arquitetura
- O sistema deve ser desenvolvido utilizando Django com Python
- O sistema deve utilizar duas vertentes de banco de dados, relacional e não relacional
- O sistema deve seguir uma arquitetura modular (backend e frontend separados)

---

## RNF04 – Usabilidade
- O sistema deve possuir interface simples e intuitiva
- O sistema deve ser utilizável por usuários com baixo conhecimento técnico

---

## RNF05 – Escalabilidade
- O sistema deve permitir adição de novas lojas sem impacto significativo
- O sistema deve suportar crescimento de dados

---

## RNF06 – Implantação
- O sistema deve ser executado utilizando Docker
- O ambiente deve ser configurado com docker-compose

---

## RNF07 – Manutenibilidade
- O código deve ser organizado e documentado
- O sistema deve permitir fácil manutenção e evolução