FROM ubuntu:16.04



RUN apt-get update

RUN apt-get install curl git -y

RUN curl -sL https://deb.nodesource.com/setup_6.x | bash - && apt-get install nodejs -y

RUN npm install

#CMD webpack --watch --watch-polling

RUN npm install webpack -g

RUN git ls-remote -h -t https://github.com/ev1stensberg/generator.git

RUN git ls-remote -h -t git://github.com/ev1stensberg/generator.git

RUN npm install webpack-cli -D

RUN npm config get prefix

RUN npm install --save-dev webpack

RUN npm install --global webpack

RUN npm install axios

RUN npm install regenerator-runtime -g

RUN npm install --dev babel-preset-env

RUN npm install install --save-dev html-loader

RUN npm install mustache --save

RUN npm config set registry http://registry.npmjs.org/ && npm install

RUN npm -v

RUN nodejs -v

RUN webpack -v

#RUN mkdir -p /usr/src/app
#ADD hello.js /usr/src/app/hello.js

ENV NODE_ENV=production

ENV PORT=4000

WORKDIR /usr/src/app

#CMD [ “nodejs”, “hello.js” ]
#ENTRYPOINT nodejs hello.js
#EXPOSE 4000FROM ubuntu:16.04


RUN apt-get update

RUN apt-get install curl git -y

RUN curl -sL https://deb.nodesource.com/setup_6.x | bash - && apt-get install nodejs -y

RUN npm install

#CMD webpack --watch --watch-polling

RUN npm install webpack -g

RUN git ls-remote -h -t https://github.com/ev1stensberg/generator.git

RUN git ls-remote -h -t git://github.com/ev1stensberg/generator.git

RUN npm install webpack-cli -D

RUN npm config get prefix

RUN npm install --save-dev webpack

RUN npm install --global webpack

RUN npm install axios

RUN npm install regenerator-runtime -g

RUN npm install --dev babel-preset-env

RUN npm install install --save-dev html-loader

RUN npm install mustache --save

RUN npm config set registry http://registry.npmjs.org/ && npm install

RUN npm -v

RUN nodejs -v

RUN webpack -v

RUN mkdir -p /usr/src/app
ADD server.js /usr/src/app/server.js

ENV NODE_ENV=production

ENV PORT=4000

WORKDIR /usr/src/app

#CMD [ “nodejs”, “hello.js” ]
#ENTRYPOINT nodejs hello.js
EXPOSE 4000