#base image
FROM node:alpine

#copy build files
COPY ./ ./

#install dependencies
RUN npm install

#default command
CMD ["npm", "start"]