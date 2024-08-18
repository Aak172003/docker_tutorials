# Application : version
# if i write simple node , so this means we are trying to use latest version , 
# But we can specify any specific version 
FROM node:20

# create folder inside container ( in which my app will run )
WORKDIR /myapp

COPY . .

RUN npm install

EXPOSE 3000

# Create image from above 4 command 
# And when i run that image , then just below image will execute 
# RUN npm start

CMD [ "npm", "start" ]














