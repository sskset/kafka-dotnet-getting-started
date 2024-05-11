# Getting Started with Apache Kafka and .NET

The code is implemented by following: [Kafka .NET tutorial](https://developer.confluent.io/get-started/dotnet/).

## Start the project

  1. Run `docker compose up -d` at root folder
  2. Produce messages: go to `/producer` folder and run `dotnet run "$(pwd)/../getting-started.properties"`
  3. Consume messages: go to `/consumer` folder and run `dotnet run "$(pwd)/../getting-started.properties"`
  
