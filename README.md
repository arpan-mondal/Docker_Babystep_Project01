
# Docker_Babystep_Project01

This project will help you to dockerise and push your application image onto the DockerHub in Python. Here on the babystep project we will be going to see a flask app which is made in python in a docker image.




## Installation

Install my-project with GitHub CLI

```bash
  gh repo clone arpan-mondal/Docker_Babystep_Project01
```
Install my-project with HTTPS

```bash
  https://github.com/arpan-mondal/Docker_Babystep_Project01.git
```


## Run Locally

Clone the project

```bash
  git clone https://github.com/arpan-mondal/Docker_Babystep_Project01
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


    




## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Authors

- [@Arpan Mondal](https://github.com/arpan-mondal)








## Roadmap

- Step 1 : Head to index.py it's a basic flask app which need to run on the port 3000 (or you can create a flask app of your own haed to Reference 1.01 in Documentation)

- Step 2 : Create a Dockerfile. Head to 'Dockerfile' to copy the code.

- Step 3 : Build the image.





## Commands to build images

To run this project, you will need to run the following commands 

- `docker build -t <username>/any_name_you_want_to_define:latest . `

- `docker container run -d -p 3000:3000 <username>/any_name_you_want_to_define:latest `

- here the port is exposed of 3000:and map at our real machine at 3000

- `docker container ls `

- To stop it you can run `docker container stop: name_of_container `

- Now all the container are free. Therefore you can push this particular image on to the docker hub so anybody can use it.

- `docker push <username>/any_name_you_want_to_define:latest . `




## Documentation

- [Flask Documentation](https://flask.palletsprojects.com/en/2.2.x/quickstart/)

- [Docker Documentation](https://docs.docker.com/)

- [Reference 1.01](https://docs.google.com/document/d/1O9q7PNXeTGOGO7SsUF9FBr3a9LCrJoCa1ZvKQGGPVq8/edit?usp=sharing)



## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?

- Write about what you learnt on the [lesson.txt] file with your name and mail address.




## Feedback

If you have any feedback, please reach out to us at accesstoarpan@gmail.com

## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arpan-mondal-816569183/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/Arpan_MegaVerse)







