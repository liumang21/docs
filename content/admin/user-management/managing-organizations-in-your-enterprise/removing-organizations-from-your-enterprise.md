---
title: Removing organizations from your enterprise
intro: 'If an organization should no longer be a part of your enterprise, you can remove the organization.'
permissions: Enterprise owners can remove any organization from their enterprise.
versions:
  ghec: '*'
type: how_to
topics:
  - Enterprise
shortTitle: Remove organizations
---

## About organization removal

You can remove an organization that is owned by your enterprise account, so the organization stands alone.

{% warning %}

**Warning**: When you remove an organization from your enterprise:
- Billing, identity management, 2FA requirements, and other policies for the organization will no longer be governed by your enterprise.
- The organization will be downgraded to the free plan.
- The organization will be governed by our standard Terms of Service.
- Any internal repositories within the organization will be converted to private repositories.

{% endwarning %}

## Removing an organization from your enterprise

{% data reusables.enterprise-accounts.access-enterprise %}
2. Under "Organizations", in the search bar, begin typing the organization's name until the organization appears in the search results.
3. To the right of the organization's name, select the {% octicon "gear" aria-label="Organization settings" %} dropdown menu and click **Remove organization**.

   ![Screenshot of a list of organizations in search results. To the right of the organization name, the dropdown menu labeled with a gear icon is expanded, and the "Remove organization" option is highlighted with an orange outline.](/assets/images/help/enterprises/remove-organization.png)
1. Review the warnings, then click **Remove organization**.

## Further reading

- "[AUTOTITLE](/admin/overview/about-enterprise-accounts)"
