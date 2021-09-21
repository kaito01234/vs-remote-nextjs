FROM node:lts

RUN mkdir __awscli_temp && \
    cd __awscli_temp && \
    curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip" && \
    unzip awscliv2.zip && \
    ./aws/install && \
    rm -r ../__awscli_temp