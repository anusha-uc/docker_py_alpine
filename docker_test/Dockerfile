FROM python:2
FROM alpine:3.7


RUN apk add --no-cache python
    
COPY . .

ENTRYPOINT [ "python" ]

CMD [ "add_number.py" ]
