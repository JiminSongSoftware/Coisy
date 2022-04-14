### Better Installation Instructions
These instructions assume you use `pyenv` and `nvm`.
If you do not already have these, it is best to read first about why you may want to use these tools 
[here](https://opensource.com/article/19/5/python-3-default-mac) 
and [here](https://dev.to/melvnl/why-you-should-use-nvm-node-version-manager-and-how-to-install-it-52oh).
If you would rather not, go back to the [README](../README.md) and follow those instructions as that is sufficient.

- Install `pyenv` [Mac](https://github.com/pyenv/pyenv#homebrew-in-macos)
	| [Linux, or Windows (via WSL)](https://github.com/pyenv/pyenv-installer)
	
- Install virtualenv plugin for `pyenv` [Mac](https://formulae.brew.sh/formula/pyenv-virtualenv)
	| [Linux, or Windows (via WSL)](https://github.com/pyenv/pyenv-virtualenv)
	
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
