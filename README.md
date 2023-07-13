Welcome to Docker Coffee-Shop:

In order to run this app you need Docker desktop and a terminal.

All the configurations are in the Dockerfile this app comes with, and, in order to run the app, execute docker build -t coffee-shop in the terminal.
This instructs docker to build an image based on the blueprint and the react component.
  
After running the build command, execute docker run -p 3000:3000 coffee-shop which runs the app itself on your local host in port 3000.
