FROM <image> - this specifies the base image that the build will extend.

WORKDIR <path> - this instruction specifies the "working directory" or the path in the image where files will be copied and commands will be executed.

COPY <host-path> <image-path> - this instruction tells the builder to copy files from the host and put them into the container image.

RUN <command> - this instruction tells the builder to run the specified command.

Copy all of the files from your project on your machine into the container image by using the COPY instruction:

EXPOSE <port-number> - this instruction sets configuration on the image that indicates a port the image would like to expose.

CMD ["<command>", "<arg1>"] - this instruction sets the default command a container using this image will run.