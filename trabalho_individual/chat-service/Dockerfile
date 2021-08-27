FROM node:15.13-alpine
WORKDIR /app
ENV PATH="./node_modules/.bin:$PATH"
COPY . .
RUN yarn
CMD ["yarn", "watch"]
EXPOSE 7100