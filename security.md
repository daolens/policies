## DaoLens Security

We take security very seriously at DaoLens. We welcome any peer review of our 100% open source code to ensure nobody's data is ever compromised or hacked.

### Where should I report security issues?

In order to give the community time to respond and upgrade we strongly urge you report all security issues privately. Please use [this form](https://forms.clickup.com/37310575/f/13jm3f-4504/RBYP5VM5H9HR30TRA6) to provide details and repro steps and we will respond ASAP. If you are unable to use Hacker One, email us directly at `hello@daolens.com` with details and repro steps. Security issues *always* take precedence over bug fixes and feature work. We can and do mark releases as "urgent" if they contain serious security fixes.

**Please note:** Due to a significant number of low quality security reports sent via email, we are unlikely to act on security reports sent to us via email unless they come from a trusted source, and include details on the vulnerability and step by step instructions to reproduce it. Theoretical reports without a proof of concept are not accepted. We strongly recommend you follow the Hacker One submission protocols.

### Password Storage

DaoLens uses Discord and Metamask for login and signup. We follow the best practices as listed in the official Discord and Metamask developer docs [here](https://discord.com/developers/docs/topics/oauth2) and [here](https://docs.metamask.io/guide/).

### DDOS

We use [HAProxy](https://www.haproxy.org/) for DDOS protection.
