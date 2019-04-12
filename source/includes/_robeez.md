# Robeez SEO

> Use n from npm to manage your node version, (stencil can be grouchy with newer node versions)

```shell
$ npm install -g n
$ n install 8.12.0
$ n use 8.12.0
```

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