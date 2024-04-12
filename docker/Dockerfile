FROM ubuntu:22.04
RUN apt-get update && apt-get install -y nano jq curl wget python3-pip && pip install llm-shell weasel stonemill
RUN pip install langchain-core langchain-community langchain-openai pydantic==1.10.9
RUN pip install langchain docarray tiktoken pydantic==1.10.9 jinja2
RUN pip install bs4 boto3
RUN apt install -y inspircd
RUN apt install -y netcat
RUN useradd -ms /bin/bash runuser
RUN mkdir /var/run/inspircd/
RUN chown runuser:runuser -R /etc/inspircd/ /var/run/inspircd
USER runuser
WORKDIR /app
CMD ["./entrypoint.sh"]
