# Trident Wordpress - Dev Onboarding

> Getting up and running quickly for Trident Wordpress 

```shell
$ git clone https://github.com/wheelhousedev/trident-wordpress.git

```
> Setup your local environment

```shell
$ cd trident-wordpress
$ export DATABASE_USER=wh-admin@wh-trident-dev
$ export DATABASE_NAME=wp_data
$ export DATABASE_HOST=wh-trident-dev.mysql.database.azure.com
$ export DATABASE_CHARSET=utf8
$ export DATABASE_PASSWORD=VALUE_IN_LASTPASS
```

> Use the included script to run docker

```shell
$ chmod u+x local-deploy-mount.sh
$ local-deploy-mount.sh
```

Use these docs to get started supporting Trident Seafoods on Wordpress

### Getting Started

 - **Docker** - Developing for Trident wordpress currently requires Docker. [Please install it from here](https://www.docker.com/products/docker-desktop) if you haven't already.
 - **Environment** - Trident uses a shared database, in order to access it we'll need to get the environment from Lastpass. Note name: **Trident Wordpress Local Dev Environment Variables**
 - **Run Docker** - Use the "local-deploy-mount.sh" script to run the docker image. (May need to run multiple times, should see "Starting Nginx.." as last command)
 - **Access the Site** - You should be able to access it now on http://localhost/
 - **Wordpress Access** - You can now login to http://localhost/wp-admin using the username "wh" and the password from Lastpass (See Graham or Dustin)

### Development Workflow

Trident is being build out using the DIVI template which builds pages through an internal pagebuilder. Since the DEV database is shared it is important to maintain backups.

1. Backup current DEV db (Graham to update docs)
2. Run local-deploy-mount.sh to launch your docker image
3. login to the Admin at http://localhost/wp-admin
3. Build pages in DIVI

## Troubleshooting

 If you're having problems, please seek Graham Dougherty <graham@wheelhousedmg.com> for help.

