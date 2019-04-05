# use the latest node LTS release
FROM 308017/sampleuiproject1

COPY package*.json ./
RUN npm install

# copy the app
COPY . .

# expose port 3000 and start the app
EXPOSE 3000
CMD [ "npm", "start" ]

