# Demonstration

As request by `ALX SE Program`, you'll find below a step-by-step demonstration of how i moved `command_line_for_the_win` from my local machine to my sandbox.

As a notice, i am not using ALX's sandbox, i am running Ubuntu 20.04 in a container using [LXC](https://linuxcontainers.org/) .



1. `sftp` into your container
   
   ```shell
   sftp root@10.55.2.253
   ```

2. `PUT` the files from your local machine to the container
   
   ```shell
   >PUT -r command_line_for_the_win/ .
   ```

3. Voila
