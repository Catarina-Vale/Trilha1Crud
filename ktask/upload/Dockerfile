FROM public.ecr.aws/lambda/python:3.8

COPY app.py .env requirements.txt ./

RUN python3.8 -m pip install -r requirements.txt -t .

CMD ["app.lambda_handler"]