FROM node:10.12.0
USER node
COPY emi-gateway /nebulae/pyxis/emi-gateway
WORKDIR /nebulae/pyxis/emi-gateway
RUN npm install --prod
CMD [ "npm","start" ]