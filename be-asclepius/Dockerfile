FROM node:18

WORKDIR /app
ENV MODEL_URL='https://storage.googleapis.com/cancer-bucket-12/model-in-prod/model.json'

COPY . .

RUN npm install
EXPOSE 8080
CMD [ "npm", "run", "start"]