# Triptease Bootstrap Tag for Google Tag Manager

This is an unofficial Google Tag Manager custom template that allows you to easily implement the **Triptease** onboarding bootstrap script on your website without hardcoding HTML.

It dynamically injects the `bootstrap.js` script by providing your unique Integration ID.

[![Community Template Gallery Status](https://img.shields.io/badge/Community%20Template%20Gallery%20Status-unpublished-red)](https://tagmanager.google.com/gallery/#/owners/mindbreaker/templates/triptease-tag)

## Setup

1. In Google Tag Manager, go to **Templates** and import the template or install it from the Community Template Gallery.
2. Create a new tag using the **Triptease Bootstrap (Unofficial)** template.
3. Enter your **Integration ID** (required).
4. Set your trigger (e.g. All Pages) and publish.

## Parameters

| Parameter | Required | Description |
| --- | --- | --- |
| Integration ID | Yes | Your unique Triptease integration identifier (e.g. `01KFDG8GYR8V0RYNA7E4H2Z0EB`). You can find this in your Triptease dashboard. |

## What it does

The tag injects the following script from Triptease:

```
https://onboard.triptease.io/bootstrap.js?integrationId=YOUR_INTEGRATION_ID
```

The script is loaded asynchronously. The tag reports success once the script has loaded successfully.

## Permissions

The template requests the following sandboxed permissions:

* `inject_script` for `https://onboard.triptease.io/bootstrap.js*`
* `logging` in debug mode

## Disclaimer

This template is not affiliated with, endorsed by, or officially supported by Triptease. Use at your own discretion.

## License

Apache 2.0 — see [LICENSE](LICENSE) for details.