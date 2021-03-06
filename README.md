# Broadcast CLI

> **IMPORTANT**
> This plugin is dummy project! it doesn't have any intention to solve any problem at all!
> I might be updating the plugin in the future to make it usable! 
> For now, feel free to fork it and add everything you need!

This is a simple node cli app that send an email to a list of user from a `.csv` file using [Sendgrid](https://sendgrid.com/)

### installation

```
npm i -g broadcast-sendgrid-cli
```

after that you can run the following command on your terminal.

```
broadcast-sendgrid-cli
```
After that, you'll be prompt for some information about the sender, just fill the information and hit 'Enter'.


### local installation

first clone the project and navigate to the project

```
git clone <repo> folder_name

cd folder_name
```

The project already have a small `.cvs` file under `assets/data.csv`

Once you clone the project, create a `.env` file inside root directory with the following:

```
SENDGRID_API_KEY=<YOUR_SENDGRID_API_KEY>
```

### Run

Under root directory just run

```
npm start
```

> This will use the default data inside `assets/`

Additionally you can run 

```
npm start -- --list=<route_to_your_csv_file>
```

After that, you'll be prompt for some information about the sender, just fill the information and hit 'Enter'.


### lint

This project uses [standard JS](https://standardjs.com/)

just run:

```
npm run lint
```

## Enjoy!
