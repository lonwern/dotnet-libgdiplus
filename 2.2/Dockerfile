FROM microsoft/dotnet:2.2-runtime

RUN apt-get update \
    && apt-get -y install libgdiplus \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
