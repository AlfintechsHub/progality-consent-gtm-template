# Progality Consent – Google Tag Manager template

Tag template for [Progality Consent](https://www.progality.com/consent), the consent management platform by Progality.

The tag:

1. Sets Google Consent Mode v2 to **denied** for every consent type (security storage granted), through Tag Manager's own consent API, before any other tag runs. Tags wait up to 500 ms for the visitor's stored choice.
2. Loads the Progality Consent banner for your website. The banner then sends the visitor's choice as an update.

## Setup

1. Add the template from the Community Template Gallery (or import `template.tpl`).
2. Create a tag of type **Progality Consent** and enter your Progality site ID (Progality panel > your website > Installation).
3. Trigger: **Consent Initialization - All Pages**.
4. Submit and publish the container. In the Progality panel press **Check installation** and run a live scan.

Step-by-step guide with screenshots: https://www.progality.com/consent/install/google-tag-manager

## Permissions

- Accesses consent state: writes the default for the consent types listed in the template.
- Injects scripts: `https://consent-cdn.progality.com/*` only.

## Support

Open an issue in this repository or write to info@progality.com.
