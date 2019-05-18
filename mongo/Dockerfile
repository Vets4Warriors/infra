FROM mongo:3.0.9

RUN mkdir /home/mongo
WORKDIR /home/mongo
COPY location.json location.json

CMD mongoimport \
    --file location.json \
    --host mongodb \
    --db vets \
    --collection location 