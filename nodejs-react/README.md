# Create the react app and move all files in this folder to the cloned repository

```sh
# Build the image 
docker build -t project/name --build-arg NODE_ENV=development

# Run the image 
docker run -p 80:80 project/name
```

[Reference link](https://www.belatrixsf.com/blog/dockerize-angular-react-vue-web-apps/)
