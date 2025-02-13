---
title: Fechar um quadro de projeto
intro: 'Se você concluiu todas as tarefas em um quadro de projeto ou não precisa mais usar um quadro de projeto, é possível fechá-lo.'
redirect_from:
  - /github/managing-your-work-on-github/managing-project-boards/closing-a-project-board
  - /articles/closing-a-project
  - /articles/closing-a-project-board
  - /github/managing-your-work-on-github/closing-a-project-board
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Pull requests
---

{% data reusables.projects.project_boards_old %}

Quando você fecha um quadro de projeto, qualquer automação de fluxo de trabalho configurada é pausada por padrão.

Se você reabrir um quadro de projeto, existirá a opção de *sincronizar* a automação, o que atualiza a posição dos cartões no quadro de acordo com as configurações de automação definidas para o quadro. Para obter mais informações, consulte "[Reabrir um quadro de projeto fechado](/articles/reopening-a-closed-project-board)" ou "[Sobre automação para quadros de projeto](/articles/about-automation-for-project-boards)".

1. Navigate to the list of project boards in your repository or organization, or owned by your personal account.
2. Na lista de projetos, ao lado do quadro de projeto que deseja fechar, clique em {% octicon "chevron-down" aria-label="The chevron icon" %}. ![Ícone de divisa à direita do nome do quadro de projeto](/assets/images/help/projects/project-list-action-chevron.png)
3. Clique em **Fechar**. ![Menu suspenso para fechar item no quadro de projeto](/assets/images/help/projects/close-project.png)

## Leia mais

- "[Sobre quadros de projetos](/articles/about-project-boards)"
- "[Excluir um quadro de projeto](/articles/deleting-a-project-board)"
- "[Desabilitar quadros de projeto em um repositório](/articles/disabling-project-boards-in-a-repository)"
- "[Desabilitar quadros de projeto na sua organização](/articles/disabling-project-boards-in-your-organization)"
- "[Permissões de quadro de projeto para uma organização](/articles/project-board-permissions-for-an-organization)"
