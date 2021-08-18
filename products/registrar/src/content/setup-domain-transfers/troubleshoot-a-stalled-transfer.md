---
order:
pcx-content-type: reference
---

# Troubleshoot a stalled transfer

Your previous registrar has five days to release the domain after a successful transfer request. If your transfer has not completed within that time frame, something has likely gone wrong. To resolve the issue, we recommend you check the following settings and restart the transfer.

Most issues with a stalled transfer can be solved by checking these details and restarting the transfer from your Cloudflare dashboard.

<details>
<summary>Registrar lock reapplied</summary>
<div>

You have reapplied the registrar lock at your current registrar since requesting the transfer. You will need to remove it again to restart the transfer process.

</div>
</details>

<details>
<summary>Transfer rejected</summary>
<div>

Your transfer has been rejected by your previous registrar. There are several reasons for this to happen: 
* You actively rejected the transfer request in the email you received from your registrar or on your registrar’s interface.
* Your registrar determines the domain is not eligible for transfer.
* Some Registrars allow customers to enable a setting to reject all transfer requests.
* In some instances, Registrars may reject the transfer if they suspect malicious behavior.

You will need to restart the transfer and approve the request or contact your current registrar to solve this issue.

</div>
</details>

<details>
<summary>Auth code invalid</summary>
<div>

Your auth code has since changed or been deprecated, and we cannot complete the transfer. Please confirm the code with your current registrar again. We strongly recommend that you cut and paste the auth code provided by your current Registrar.

</div>
</details>

<details>
<summary>WHOIS Guard / privacy protection</summary>
<div>

Some registrars may prohibit transfer requests if you have WHOIS privacy services enabled. You need to first disable those services at your current registrar before you can proceed with the transfer process.

</div>
</details>

<details>
<summary>Restarting your transfer</summary>
<div>

In the Cloudflare Overview page for your domain, you can find the details of your registration in the column on the right side of the page. In the **Domain Registration** card, click **Cancel and Retry**. Once you initiate the retry, you will need to reenter your auth code and confirm your WHOIS information.

</div>
</details>