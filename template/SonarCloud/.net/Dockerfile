FROM mcr.microsoft.com/dotnet/sdk:8.0

RUN apt-get update \
    && apt install -y --no-install-recommends openjdk-17-jdk \
    && curl -sL https://deb.nodesource.com/setup_16.x | bash - \
    && apt-get install -y --no-install-recommends nodejs \
    && apt-get install -y unzip \ 
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*