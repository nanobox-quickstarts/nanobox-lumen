![Lumen from scratch](https://guides.nanobox.io/assets/quickstart-icons/lumen.png)

# Lumen from scratch

Run a Lumen app locally, install nothing besides nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>


## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-lumen.git

# cd into the lumen app
cd nanobox-lumen
```

## Run the app

```bash
# Run lumen as you would normally, with Nanobox
nanobox run php-server
```

## Check it out

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local lumen.dev
```

Visit your app at <a href="http://lumen.dev" target="\_blank">lumen.dev</a>

## Explore

With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where lumen is installed,
php -v

# your packages are available,
composer show

# and your code is mounted
ls
```

## Now What?
For more details about running lumen apps with nanobox visit [guides.nanobox.io/php/lumen/](https://guides.nanobox.io/php/lumen/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
