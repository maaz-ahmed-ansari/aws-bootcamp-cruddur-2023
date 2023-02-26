# From Image "python:3.10-slim-buster"
FROM python:3.10-slim-buster

# Inside Container
# Make a new folder inside container
WORKDIR /backend-flask

# Outside container -> Inside Container
# "requirements.txt" this contains the libraries want to install to run the app
COPY requirements.txt requirements.txt

# Inside Container
# install the python libraries used for the app
# RUN is used to create a layer on image
RUN pip3 install -r requirements.txt

# Outside Container -> Inside Container
# . means everything in current directory
# first . -  /backend-flask (outside container)
# second . - /backend-flask (inside container)
COPY . .

# Set Environment variables (Env Vars)
# Inside the container and will set when the container is running
ENV FLASK_ENV=development

EXPOSE ${PORT}

# CMD (Command) - container will run when it starts up
# python3 -m flask run --host=0.0.0.0 --port=4567
# -m : specifies module
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]

# -t -> tag list e.g. "name:tag", tag is optional
# here '-t backend-flask'  -> name is 'backend-flask', default tag taken is 'latest'
# since no tag was explicitly given
# latest tag does not necessarily mean latest image, it's just default tag value
# Run the docker build command
# docker build -t  backend-flask ./backend-flask

# Now Run docker run command
# docker run --rm -p 4567:4567 -it -e FRONTEND_URL='' -e BACKEND_URL='' backend-flask