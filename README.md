## Commands to run the container:

###  Build the image (if you are not downloading it)
```
docker build <directory with the dockerfile>
docker build -t clrhoades1/shap-notebook-container:latest .
```

### Create the container
```
docker run -p 8888:8888 clrhoades1/shap-notebook-container

