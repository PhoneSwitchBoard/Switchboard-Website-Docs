---
title: Twilio Integration
permalink: /docs/twilio
layout: page
---

## Twilio


Once you have logged into your STARcloud account, go to the `Integrations` menu option and click `New Integration`.


![Screenshot: Integrations](./../images/integration.png)


In a new browser tab, sign in to your **Twilio** account. If you don't have an account yet, create a new one by following this [link](https://login.twilio.com/u/signup) and click `Sign Up`.

After completing the registration process, go to `Account` -> `API Keys & Tokens` -> `Create API Key`.

Set a **Friendly name**, choose a **Region** and a **Key Type**; then click `Create`. Here the application will display a **SID** and a **Secret**. Please note that the **secret** is only shown once. Make sure to store it in a safe location.


<p align="center">
  <img src="./../images/twilio_secret.png" />
</p>


- Copy the **SID** and paste it in the first tab you had, the **STARTcloud** one, under **Key Name**.
- Copy the **Secret** and paste it into the **Key Value**.

Then click `Done`.

Finally, to find the **Account Name**, go back to `Account` -> `API Keys & Tokens` and scroll to the bottom. Copy the Account SID in the **Live credentials** section.


<p align="center">
  <img src="./../images/twilio_account_name.png" />
</p>


Now that you have all the necessary values to create the integration in **STARTcloud**, press `Save` and the process is complete.


<p align="center">
  <img src="./../images/integration_save.png" />
</p>


You'll see the integration you just created in the list of integrations.


![Screenshot: Integration List](./../images/integration_list.png)
