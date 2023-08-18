## Getting Started

The backend API runs over Python 3.10:

First you need to configurate your virtual enviroment going to the root of the project and run:
```bash
#for complete documentation go to: https://docs.python.org/3/library/venv.html

python -m venv .venv
# then you need to activate the virtual environment
source .venv/bin/activate
```

Then you need to install the packages

```bash
pip install -r requirements.txt
```

Now  run the development server:

```bash
uvicorn app.main:app --reload
```

Open [http://localhost:8000/docs](http://localhost:8000/docs) with your browser to see the Swagger docs.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [FastApi Documentation](https://fastapi.tiangolo.com/) - learn about FastApi features and API.
