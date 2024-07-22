# base image
FROM node:12.2.0-alpine

# working dire
WORKDIR app

# Copy code into container
COPY . .

# requirement
RUN npm install
RUN npm run test

# Expose 8000 port to outside container
EXPOSE 8000

#Run
CMD ["node","app.js"]
