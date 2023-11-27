0x0D. Web stack debugging #0

## Tasks :page_with_curl:

* **0. Give me a page!**
  * [0-give_me_a_page](./0-give_me_a_page): Bash script that runs Apache on a
  web server and gets it to respond to queries to the root.
Here we can see that after starting my Docker container, I curl the port 8080 mapped to the Docker container port 80, it does not return a page but an error message. Note that you might also get the error message curl: (52) Empty reply from server.
After connecting to the container and fixing whatever needed to be fixed (here is your mission), you can see that curling port 80 return a page that contains Hello Holberton. Paste the command(s) you used to fix the issue in your answer file.
