---
title: 'Alterando a visibilidade de {% data variables.product.prodname_project_v1 %}'
intro: 'Como proprietário da organização ou administrador de {% data variables.projects.projects_v1_board %}, você pode tornar um {% data variables.projects.projects_v1_board %} {% ifversion ghae %}interno{% else %}público{% endif %} ou privado.'
redirect_from:
  - /github/managing-your-work-on-github/managing-project-boards/changing-project-board-visibility
  - /articles/changing-project-board-visibility
  - /github/managing-your-work-on-github/changing-project-board-visibility
versions:
  feature: projects-v1
topics:
  - Pull requests
shortTitle: Alterar visibilidade
allowTitleToDifferFromFilename: true
---

{% data reusables.projects.project_boards_old %}

{% data reusables.project-management.project-board-visibility %}

{% note %}

**{% ifversion classic-project-visibility-permissions %}Observações{% else %}Observação{% endif %}:** {% ifversion classic-project-visibility-permissions %}

* {% data reusables.projects.owners-can-limit-visibility-permissions %}
* {% endif %}Ao se tornar o seu {% data variables.projects.projects_v1_board %} {% ifversion ghae %}interno{% else %}público{% endif %}, os integrantes da organização recebem acesso de leitura por padrão. Você pode dar permissões de gravação ou de administrador a certos integrantes da organização, dando acesso a equipes nas quais estão ou adicionando-os ao {% data variables.projects.projects_v1_board %} como colaborador. Para obter mais informações, consulte "[Permissões de {% data variables.product.prodname_project_v1_caps %} para uma organização](/articles/project-board-permissions-for-an-organization)".

{% endnote %}

1. Acesse o quadro de projeto que você deseja tornar {% ifversion ghae %}interno{% else %}público{% endif %} ou privado.
{% data reusables.project-management.click-menu %}
{% data reusables.project-management.access-collaboration-settings %}
{% data reusables.project-management.choose-visibility %}
1. Clique em **Salvar**.
