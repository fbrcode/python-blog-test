# Project notes

```sh
poetry new --name=blog_app --src blog
git init
cd blog && poetry config virtualenvs.in-project true --local
poetry install
echo ".venv" > .gitignore

```

