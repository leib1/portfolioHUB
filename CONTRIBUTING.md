# ✍️ Guia de Contribuição para o PortfolioHUB

Obrigado pelo seu interesse em contribuir para o PortfolioHUB, o portfólio digital de Gabriel Allemand. Este projeto é uma vitrine de aprendizado em Ciência da Computação e valorizamos qualquer contribuição que ajude a aprimorá-lo.

Este guia detalha as melhores práticas de colaboração, garantindo que o fluxo de trabalho seja organizado e eficiente.

## 1. Fluxo de Trabalho de Colaboração (Branching e PR)

Adotamos um fluxo de trabalho baseado em *Pull Requests (PR)* para garantir que todas as alterações sejam revisadas antes de serem mescladas na *branch* principal (`main` ou `master`).

1.  **Fork do Repositório:** Comece criando um *fork* (cópia) do repositório `portfolioHUB` para o seu próprio perfil no GitHub.
2.  **Criação de Branch:** Nunca trabalhe diretamente na *branch* principal (`main`). Crie uma nova *branch* para isolar suas alterações.
    * **Nomenclatura Sugerida:**
        * Para correção de erros: `bugfix/nome-do-erro`
        * Para novas funcionalidades: `feature/nova-funcionalidade`
        * Para documentação/texto: `docs/atualiza-readme`
3.  **Desenvolvimento e Commits:** Implemente suas alterações na nova *branch*.
4.  **Pull Request (PR):** Envie um *Pull Request* do seu *fork* para a *branch* principal do repositório original.

## 2. Padrão de Mensagens de Commit (Commit Messages)

Para manter o histórico de versão claro e conciso (um requisito de boa prática de Git), utilize o seguinte padrão para as mensagens de *commit*:

* **Formato:** `[TIPO]: Breve descrição da alteração`
* **Exemplos:**
    * `feat: Adiciona novo projeto de calculadora Python`
    * `fix: Corrige link quebrado na seção 'Projetos'`
    * `docs: Atualiza o arquivo SECURITY.md com nova política`
    * `style: Ajusta margens e cores da página inicial`
    * `refactor: Otimiza a estrutura do arquivo README.md`

## 3. Diretrizes de Documentação

A documentação é um componente chave deste portfólio.

* **`README.md`:** Qualquer novo projeto adicionado ao PortfolioHUB deve possuir um `README.md` detalhado, descrevendo a funcionalidade, tecnologias utilizadas e instruções de execução.
* **Melhorias na Documentação:** Contribuições para melhorar a clareza deste `CONTRIBUTING.md` ou do `SECURITY.md` são muito bem-vindas.

## 4. Práticas de Segurança

**Atenção:** Se você descobrir uma vulnerabilidade de segurança, **NÃO abra uma Issue pública nem um Pull Request**. Consulte o arquivo **`SECURITY.md`** na raiz do repositório para o procedimento de relatório privado e responsável.
