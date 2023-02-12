# fast_api_learning_notes :snake:

Anotações para criação de API Fast API

## Install.

Install fastApi and [uvicorn](https://www.uvicorn.org/).

You can install use PIP.
`pip install "fastapi[all]"`

Or install use poetry.
`poetry add "fastapi[all]"`

## How to build professional projects.
Many times we see tutorials, teaching basic projects, but in real life, we do not create projects like these tutorials.
In documentation fast api we found this [article](https://fastapi.tiangolo.com/tutorial/bigger-applications/), which shows how we can create applications using file structure like this.

```shell
.
├── app
│   ├── __init__.py
│   ├── main.py
│   ├── dependencies.py
│   └── routers
│   │   ├── __init__.py
│   │   ├── items.py
│   │   └── users.py
│   └── internal
│       ├── __init__.py
│       └── admin.py
```
In fast api doc they brief, this structure would be the equivalent of [Flask's Blueprints](https://flask.palletsprojects.com/en/2.2.x/blueprints/).



# Authentication

How to use [fast-api with JWT](https://youtu.be/0_seNFCtglk).

# References

* [DOC_FAST_API](https://fastapi.tiangolo.com/)
* [DOC_FAST_API](https://fastapi.tiangolo.com/pt/) -> pt-Br
* [Beginners FastAPI - 40 min](https://youtu.be/O05PucyQYBg)
* [API com FastAPI, Postgres, SQLAlchemy, Alembic, Docker e Google Cloud.](https://youtube.com/playlist?list=PLJHVw_wMqnI-eX95g9U_W941l_yWsIDIL) -> pt-Br
* [FULL FastAPI project with me!!](https://youtu.be/kyJNbSUz86w)
