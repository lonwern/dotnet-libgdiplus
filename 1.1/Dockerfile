FROM microsoft/dotnet:1.1-runtime

RUN apt-get update \
    && apt-get -y install libgdiplus \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
