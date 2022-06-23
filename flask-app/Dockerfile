#Use Python 3.6 as a base image

# Copy contents into image
 
# install pip dependencies from requirements file
 
# Expose correct port

# Create an entrypoint

FROM python:3.6
COPY . .
RUN pip3 install -r requirements.txt
EXPOSE 5000
ENTRYPOINT [ "python3", "app.py" ]

