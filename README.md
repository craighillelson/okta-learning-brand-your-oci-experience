# Lab: Brand Your Okta Customer Identity Experience

In this  [Okta Learning](https://learning.okta.com) lab, you will configure a custom brand in the Okta Admin Console and apply it to the Okta-hosted Sign-in Widget and Okta error pages. You will then implement customizations for an email template using Okta Expression Language. Next, you will test the end-user sign-up and sign-in experience with a customer portal app. Last, you will use the Brands API to retrieve your custom branding settings.


## Create Required Free Accounts

1. A GitHub account with Codespaces access (you can use the free plan, which gives you 60 hours of use per month). Create a free account [here](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account) if you do not already have one.

    **⚠️ Note to internal Okta employees: Do NOT use your EMU (Enterprise-managed user) account since Codespaces are disabled.**

2. An Okta Integrator Free account: You should use a new account for our labs so that you have a fresh Okta Identity Engine (OIE) org. Register for one [here](https://developer.okta.com/signup/).

## Accessing and Working with Okta Customer Identity (OCI) Labs

1. **After logging into GitHub, open the lab repo in a Codespace:** From the *Code* dropdown menu of this branch, toggle to the *Codespaces* tab. Click the plus sign to create and open the lab in a Codespace. A new tab will open, and Codespaces will begin configuring the lab environment. Wait for the environment to finish building.
2. **Begin working with the lab:** Once the environment is ready you'll see a Codetour popup with lab instructions. This can take some time, as the environment is installing several extensions and libraries to facilitate the lab. Once it is complete, you can open the Codetour to view all steps using the panel in the lower right. At this point, you should follow the remainder of the instructions within Codetour!

### Notes:
- **If you'd like to save your work to your own fork:** You can commit and push your changes to a fork of this repo. (See: [Using Source Control in Your Codespace](https://docs.github.com/en/codespaces/developing-in-codespaces/using-source-control-in-your-codespace)).
- **Close the Codespace when you're finished with the lab:** Codespaces come with a set amount of free usage. To avoid using all of your free use allocation, be sure to return to the forked repo, select the "Code" dropdown, select the dots next to your open Codespace, and select "Delete." This will not delete your forked repository. You can keep that forever, and open a new Codespace whenever you like.

---

#### Disclaimer: The following is intended for educational purposes only. Not meant for production.

