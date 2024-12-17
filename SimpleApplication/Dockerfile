FROM mcr.microsoft.com/dotnet/sdk:6.0 AS build

# Set the working directory
WORKDIR /app

# Copy the project file and restore dependencies
COPY ./*.csproj ./


# Copy the remaining files and build the application
COPY . ./
