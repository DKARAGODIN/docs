{% cut "Resource" %}

| Parameter | Description | Data type |
-------- | -------- | ----------
| \<entity_type> | Entity type:<ul><li>Project for a project</li><li>Portfolio for a portfolio</li></ul> | String |
| \<entity_ID> | Entity ID. To get the ID, see the [entity list](../../../tracker/concepts/entities/search-entities.md). | String |
| \<project_or_portfolio_ID> | Project or portfolio ID (the `shortId` value). You can use it instead of the entity ID in the request. | String |
| \<file_ID\> | File's unique ID. | String or number |

{% note warning %}

Entity ID is not the same as project or portfolio ID.

{% endnote %}

{% endcut %}
