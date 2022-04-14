### Better Installation Instructions

- Install `pyenv` [Mac](https://formulae.brew.sh/formula/pyenv#default)
	| [Linux, or Windows (via WSL)](https://github.com/pyenv/pyenv-installer)
	
- Install `nvm` [Mac](https://formulae.brew.sh/formula/nvm#default)
	| [Linux, or Windows (via WSL)](https://github.com/nvm-sh/nvm#installing-and-updating)

#### To run the django application , go to coisy_django folder and run commands below
`pyenv virtualenv system Coisy`
<br>`pip install -r requirements.txt`
<br>`python manage.py makemigrations`
<br>`python manage.py migrate`
<br>`python manage.py runserver`

-> keep it open and do next step


#### To get the vue interface, go to coisy_vue and run :
`nvm install`
<br>`nvm use`
<br>`npm install -g @vue/cli`
<br>`npm install`
<br>`npm run serve`

After that, open the url:

[http://localhost:8080/](http://localhost:8080/)
