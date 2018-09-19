## Installation

download or clone repo

```bash
virtualenv env
pip install -r requirements/dev.txt
mkdir src
django-admin startproject --template=https://github.com/tonybolanyo/django-project-template/archive/develop.zip --extension=py <project_name> src
docker-compose build
docker-compose up
```