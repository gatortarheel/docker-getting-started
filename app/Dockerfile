FROM node:12-alpine
WORKDIR /app
COPY . .
#5 does not work --> 
# XCOPY test1.text c:\temp

#6 
ADD test1.txt c:/tempadd/

#7
COPY test1.txt c:/tempcopy/

#8
COPY test1.txt /tempcopynoC/

RUN yarn install --production
CMD ["node", "/app/src/index.js"]