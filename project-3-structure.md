### First use Irongenerator to start the project and create the backend

### In this example our project will be called 'projector'

```bash
$ irongenerate projector
```

### Now we will go into this folder and create a react app there - this will be in a folder called 'client'

```bash
$ cd projector
$ npx create-react-app client
```

### Then we also want to remove git from within the client folder - otherwise you will get an error later if you use git in your project

```bash
# in: projector/client
$ rm -rf .git
```

Now we have our basic project structure 

Happy hacking 💙
