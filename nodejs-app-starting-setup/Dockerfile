FROM node

WORKDIR /app

#host -> container(app)
COPY . ./ 

# Build image
RUN npm install 

EXPOSE 82

# After build
CMD ["node", "server.js"] 