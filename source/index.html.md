---
title: DEV-Ops - Dustin's Client Reference

toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# Introduction

Use this to quick-reference DEV-Ops and Support Documents of our clients.


# Orahealth SEO

### Support
- Point: Natalie <natalie@wheelhousedmg.com>
- Backup: Drew <drew@wheelhousedmg.com>
- Strategist: Darla <darla@wheelhousedmg.com>

### Tasks In Progress

- “Sample” Form to Excel Workflow - Dallas

- Ongoing: Supporting Darla

### Web Stack and DEV-Ops

- **CMS**: Shopify
- **Primary Domain**: https://www.oracoat.com/
- **Other Domains:**: https://www.oracoat.eu/
- **Code Control?**: No
- **Access**: Lastpass -> CMS Accounts

### DEV Update Procedure

- Login to Shopify at https://www.oracoat.com/admin
- Select "Online Store" in the menu
- Select "Themes"
- Duplicate "Theme 150" or current open theme.
- Update .liquid files in Duplicated Theme.
- Upon update approval, publish updated Theme.

### Notes

Due to the above there are a lot of old garbage templates in Oracoat. We've recommended that they prune these.

# Project Rise Provider SEO

### Support

- Point: Aditya/Graham
- Backup: Roy?
- Strategist: Darla

### Tasks In Progress

- Project not started, no current context or DEV-Ops

# Providence Sitecore 6 DEV

### Support

- Point: Graham
- Backup: Drew

### Tasks In Progress

- CS-104 – Change Banner for Oregon - in CM, awaiting feedback or green light to deploy
- CA-106 – Change Mobile Experience “Navigation” for Oregon - in CM, awaiting feedback or green light to deploy
- COS-74 – Oregon Location Page Updates

### Notes

- Slack: We have slack channel #prov-sitecore - This has much of Guy’s team on it. @schooley and @Bhanu are our primary contacts.

### Web Stack and DEV-Ops

- **CMS**: Sitecore 6 (.NET)
- **Primary Domain**: https://oregon.providence.org
- **DEV Domains:**: 
  - https://dev-oregon.providence.org/
  - https://cm-oregon.providence.org/
- **Code Control?**: Yes
- **Repository**: https://bitbucket.org/medtouch/providence-oregon/branches/
- **Repository Access**: Bitbucket Access granted to Dustin, Graham and Drew by <Jeremy.Kinser@providence.org>, requests for other access should go through Jeremy.
- **RDP Access**: Personal Credentials emailed to Dustin, Graham and Drew from <Joseph.Schooley@providence.org> on Jan 10, 2019.

> Here are the connections you can now RDP into:

```shell
dev (WEB-SC-DEV): 104.42.55.216 #Sitecore files located at F:\inetpub\wwwroot\dev-oregon.providence.org\
stage (WEB-SC-CM01): 104.42.74.29 #Sitecore files located at F:\inetpub\wwwroot\cm-oregon.providence.org\
prod 1 (WEB-SC-CD01): 104.210.48.125
prod 2 (WEB-SC-CD02): 104.42.46.44
prod 3 (WEB-SC-CD03): 104.42.49.191
prod 4 (WEB-SC-CD04): 104.42.195.182
```
### DEV Update Procedure
- Clone local repository
- Create Feature Branch from Release
- Make Code Updates
- Copy and Paste to WEB-SC-DEV to view on dev-oregon.providence.org
- Coordinate with Guy's team for release to CM
- Guy to coordinate release to Prod

### Other Notes

The repo does contain multiple sites. For now we are only supporting Oregon.

# Robeez SEO

> Install Stencil CLI

```shell
$ npm install -g stencil-cli
```

> Install Support Libraries from Template

```shell
$ npm install
```
> Init Stencil (Robeez API Credentails in Lastpass shared with Natalie, Graham and Drew)

```shell
$ stencil init
```

> Run Stencil CLI

```shell
$ stencil start

-------------------------------------------------

[Browsersync] Proxying: http://localhost:3001
[Browsersync] Access URLs:
 ---------------------------------------
       Local: http://localhost:3000
    External: http://192.168.30.189:3000
 ---------------------------------------
          UI: http://localhost:3002
 UI External: http://192.168.30.189:3002
 ---------------------------------------
[Browsersync] Watching files...
```

>Push Template to Big Commerce

```shell
$ stencil push
```

### Support

- Point: Natalie
- Backup: Graham, Drew

### Tasks In Progress

- Parameters in Pagination Tags

### Web Stack and DEV-Ops

- **CMS**: Bigcommerce
- **CMS Access**: Etana is an admin and can invite any needed. 
- **Hosting** - BigCommerce
- **Primary Domain**: https://www.robeez.com
- **International Domain**: https://www.robeez.ca/
- **Code Control?**: Depricated
- **Why Depricated?**: Client makes many independent updates, code-control is always out of date. Always better to pull current theme from server.

### DEV Update Procedure

- Login to bigcommerce
- Navigate to Storefront -> My Themese
- Advanced -> Download Current Theme
- Navigiate to Download, Install and Run Stencil CLI.
- You should now be able to develop locally
- When development is complete you can bundle or push the changes to BigCommerce
- Other Documentation: [Stencil CLI Docs](https://developer.bigcommerce.com/stencil-docs)

# Evergreen SEO
- Point: Natalie
- Backup: Drew

### Tasks In Progress

- Chatbot for Wordpress (Scoping)

### Web Stack and DEV-Ops

- **CMS**: Wordpress
- **CMS Access**: Lastpass CMS Accounts
- **Hosting** - Unknown
- **Primary Domain**: [https://www.theevergreenmarket.com](https://www.theevergreenmarket.com)
- **Code Control?**: Depricated
- **Why Depricated?**: We do not currently have an engagement, code control and stack are out of date.

### DEV Update Procedure

- Attempt to make updates through wordpress pagebuilder
- Update child-theme directly after taking backups (Not currently supported by DEV-Ops)

# The Met Store Blog SEO

-Point: Natalie
-Backup: Dallas, Drew

### Tasks In Progress

- Wordpress Update
- DEV-Ops handoff
- Otherwise we do not have an engagment, but setup their new AWS Hosting

### Web Stack and DEV-Ops

- **CMS**: Wordpress
- **CMS Access**: Lastpass CMS Accounts
- **Hosting** - AWS - We Setup
- **Primary Domain**: [https://www.metstoreblog.org](https://www.metstoreblog.org)
- **Code Control?**: Depricated
- **Why Depricated?**: We do not currently have an engagement, code control and stack are out of date.

# Trident DEV Migration to Wordpress

### Point: Natalie

### Backup: Drew & Graham

### In Progress:

- Project is essentially being handed off to CE and Nat

### DEV-Ops: In Progress

# Trident SEO

### Point: Graham

### Backup: Natalie

### InProgress:

- [ ] WAP landing page updates - Should be done Fri-5th

- [ ] Recipe page layout changes

# NIST Prospecting Engine

### Point: Liz

### Backup: Roy, Graham, Dallas

### In Progress:

- [ ] End to End Automation, DB Refactoring

- [ ] Backlog Grooming Next Steps

# Crowsnest

### Point: Johnathn

### Backup: Paul, Drew

### DEV-Ops

- [ ] SSL Cert needs to be removed.

