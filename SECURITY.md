# 🛡️ Política de Segurança do PortfolioHUB

O PortfolioHUB é um projeto de portfólio digital que valoriza a segurança e a integridade do código e dos dados. Esta política documenta as práticas de segurança implementadas e os procedimentos para relatar vulnerabilidades.

## 1. Segurança da Conta (Gestão de Usuários)

A segurança do repositório começa com a proteção da conta do proprietário (`leib1`).

### 1.1. Autenticação de Dois Fatores (2FA)

A Autenticação de Dois Fatores (2FA) é **obrigatória** para o acesso à conta principal do GitHub associada a este repositório.

* **Objetivo:** Adicionar uma camada extra de segurança, exigindo uma segunda forma de verificação além da senha.
* **Implementação:** O 2FA é configurado via aplicação de autenticação (como Google Authenticator ou similar).
* **Referência (Entrega Final):** Esta prática cumpre o requisito de **Gestão de Usuários e Segurança** da entrega, garantindo que o controle de acesso seja robusto.

## 2. Segurança do Repositório (Controle de Versão)

O repositório `portfolioHUB` emprega regras de proteção de branch para evitar alterações diretas e não revisadas no código principal.

### 2.1. Regra de Branch Protection (Proteção da Branch Principal)

A branch principal (`main` ou `master`) está protegida com as seguintes regras:

* **Restrição de Push Direto:** É proibido enviar *commits* diretamente para a branch principal.
* **Revisão Obrigatória de Pull Request:** Toda e qualquer alteração no código deve ser proposta através de um **Pull Request (PR)** e requer, no mínimo, **uma aprovação de revisão de código** antes de ser mesclada (*merge*).
* **Testes (Opcional):** Em projetos futuros com testes automatizados, o status de verificação de testes será um requisito para o *merge*.
* **Benefício:** Esta política de *Branch Protection* garante que o código no ambiente de produção seja estável e revisado, fundamental para o controle de acesso e qualidade.

## 3. Relatório de Vulnerabilidades

Agradecemos a busca responsável por vulnerabilidades.

Se você encontrar qualquer falha de segurança neste projeto (configurações do GitHub, *links* quebrados, vazamento de dados acidental, etc.), siga estas diretrizes:

1.  **Não divulgue a vulnerabilidade publicamente.**
2.  **Entre em contato:** Envie um e-mail descrevendo a falha de forma clara e concisa para o contato principal (e-mail, em meu Perfil Pessoal).
3.  **Tempo de Resposta:** Uma resposta inicial será enviada em até 48 horas.
