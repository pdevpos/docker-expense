FROM node:20
RUN useradd expense
RUN mkdir /opt/server
RUN chown -R expense:expense /opt/server
WORKDIR /opt/server
COPY backend/server/*.js /opt/server/
COPY backend/server/package.json /opt/server/
RUN npm install

