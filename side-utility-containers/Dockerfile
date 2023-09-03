FROM node:14-alpine
# very slim and optimized version

WORKDIR /app

#CMD [ "executable" ]           # this command will be overwritten by npm install command in
                                # docker run -it -v $(pwd):/app node-util npm install
#ENTRYPOINT [ "executable" ]
                                # this command will appended after npm install
ENTRYPOINT [ "npm" ]
                                # in docker should point only 'init' in the end ('install' and other)