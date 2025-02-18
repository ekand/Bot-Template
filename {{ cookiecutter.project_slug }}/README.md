# {{cookiecutter.project_name}}




A discord bot made with [interactions.py](https://github.com/interactions-py/interactions.py).
Visit [the official website](https://interactions-py.github.io/interactions.py/) to get started.

# Running the Application
There are multiple ways to launch the application.


### Python
To start the bot with python, you first need to install the required packages with either `poetry install` or `pip install -r requirements.txt` 


Then, run:

1) `python main.py`


### Docker-Compose
You can use the pre-made docker-compose by running:

1) `docker-compose up`

### Docker
For most users, the use of `docker-compose` is highly recommended.

Nevertheless, you can import the pre-made Dockerfile into your own docker-compose or run it manually by with:

1) `docker build -t your_project_name .`
2) `docker run -it your_project_name`

Note: Make sure that you created a volume so that you local `./logs` folder gets populated.

# Additional Information
Additionally, this comes with a pre-made [pre-commit](https://pre-commit.com) config to keep your code clean. 

It is recommended that you set this up by running:

1) `pip install pre-commit`
2) `pre-commit install`
