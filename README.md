# Build
   ```docker build . -t <name>/flask``` 
   
   Example: docker build . -t gagan/flask
   (. means the current Directory)
# RUN
   ```docker run --name=fask -p=3004:80 <name>/flask```
   
   
    
  Example: docker run --name=fask -p=3004:80 gagan/flask

  -p porting traffic from 3004 port to port 80 of container

	
