Notes:

Realized that when autopep8 reformatted the code on save causing errors

make sure to use python manage.py migrate, to apply migrations

I could not get certs to work correctly on my computer. I could not figure out how to change my local /etc/hosts file as an admin so I cannot get past the SSL certificate to bookmark an image.

__Initialize__

Add a new repo

`git init`

__Git ignore__

Do not track instructions

__git add__

Add files for tracking

`git add -A`

__git commit__

commit recent tracked changes

`git commit -m "message`

__set up remote__

set up a remote peer (like github)

`git remote add origin https://github.com/Slimjim821/CIDM6325.git`

__push to remote__

push to the remote peer (github)

`git push -u origin master`

## Setup steps for virtual Environment and Jupyter Notebook use

1. make virtual environment: `py -m venv ch3_env`

2. Activate virtual environment
`.\env\Scripts\activate` (assumes you are on windows using powershell)
in git bash `source env/bookmarks/Scripts/activate`

3. Install requirements
`pip install -r .\Requirements.txt`

4. Run Jupyter Lab: `Jupyter lab`

