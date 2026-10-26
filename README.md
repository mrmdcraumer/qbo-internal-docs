# Integrate public policies

Public policy and support pages for Morgan Records Management LLC's private Integrate application. GitHub Pages serves `main` from the repository root over HTTPS. No build dependencies, scripts, trackers, forms or private application data belong here.

## URLs for Intuit production onboarding

| Field | Public URL |
| --- | --- |
| End-user license agreement | https://mrmdcraumer.github.io/qbo-internal-docs/eula.html |
| Privacy policy | https://mrmdcraumer.github.io/qbo-internal-docs/privacy.html |
| Support / overview | https://mrmdcraumer.github.io/qbo-internal-docs/ |
| Disconnect instructions | https://mrmdcraumer.github.io/qbo-internal-docs/disconnect.html |

The disconnect page contains instructions; loading it does **not** revoke tokens or confirm disconnection. It must not be represented as an automatic disconnect endpoint. The application launch URL remains `https://files.morganrecordsmanagement.com/internal/tools/console`; the OAuth callback is a separate, registered application endpoint, not one of these static pages.

Publishing policies does not list Integrate in the QuickBooks App Store, grant accounting access, authorize a production connection, or activate production cutover. Intuit's application assessment, production credentials and explicit company consent remain separate steps.

## October 26, 2026 update

- Replaced the retired Check → QBO / PayPal reconciliation description with Integrate's internal sales, project and accounting workflow.
- Updated EULA responsibilities and scope, retaining the internal-use license and qualified warranty disclaimer.
- Described customer, invoice, payment-reconciliation, connection and audit information, service providers, retention and data requests.
- Documented the Accounting API scope and the current absence of payment processing and refunds.
- Corrected disconnect instructions and clarified that retained records are not automatically deleted.
- Added consistent, responsive, keyboard-accessible static layouts and print styles; retained `noindex,nofollow` as a search preference, not access control.

## Review basis and maintenance

Reviewed against Integrate's QuickBooks OAuth, customer setup, deposit invoice and payment-reconciliation source on October 26, 2026. Customer setup is being completed in the application; the policies describe authorized capabilities when enabled and do not claim a deployment or launch date.

Primary references checked:

- [Intuit: Publish your app](https://developer.intuit.com/app/developer/qbo/docs/go-live/publish-app)
- [Intuit developer terms](https://static.developer.intuit.com/output_html/tos/docs/tos.html)
- [Intuit: Manage connected integrations](https://quickbooks.intuit.com/learn-support/en-us/help-article/mobile-apps/fix-connected-app-issues-quickbooks-online/L7At9OGp4_US_en_US)

These pages are application-specific policy text, not an Intuit certification or a legal-compliance opinion. Morgan remains responsible for the accuracy of its disclosures and applicable legal obligations. Recheck before materially changing data use, retention, service providers, external users, or adding Payments/refunds. Do not invent fixed retention periods or certifications.

Review the public pages without sign-in after deployment. Check links, keyboard focus, 320 CSS-pixel reflow, enlarged text and print layout. Keep the effective dates synchronized when changing policy terms. Historic wording is retained in Git history.
