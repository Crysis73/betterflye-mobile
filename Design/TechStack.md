# Tech Stack

## Technologies

- ASP.NET Core
- Xamarin Forms
- MonkeyCache
- MySQL
- Docker

## [ASP.NET Core]((https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-3.1))

There will be an ASP.NET Core microservice in the cloud that our application sends rest requests to in order to communicate with the database. The reason behind choosing ASP.NET Core to write the microservice in is because of the extensive documentation behind the .NET Framework and the massive community of developers. We believe that due to the size and activity of the community, we will be able to easily find documentation and answers for questions we have. Additionally, Microsoft provides detailed documentation on design patterns and best practices that we will be able to take advantage of.

## [Xamarin](https://dotnet.microsoft.com/apps/xamarin)

We will be using Xamarin for our Mobile Application code. We chose Xamarin because it is also in the Microsoft tech stack and is a cross-platform mobile development library. With Xamarin.Forms specifically, we can achieve about 96% code reusability and only have to write 4% platform specific code. Additionally, Visual Studio's Android emulator has a hot-reload feature that is *almost* on parity with Flutter's. The immediate feedback we'll gain from this feature will increase our development productivity. Since Xamarin is the oldest cross platform library, we're hoping that the majority of issues we might run into will have been encountered before and that the platform will be more stable than newer versions.

## [MonkeyCache](https://github.com/jamesmontemagno/monkey-cache)

MonkeyCache is a Xamarin package that we will take advantage of in order to cache data client-side. We chose MonkeyCache because it both supports encrypted storage for credentials and setting an expiration for any items that are added to the cache. This package is also cross platform..

## [MySQL](https://www.mysql.com/)

We didn't have a choice for the database technology -- the client already uses MySql so we need to follow suite. We love MySql though :), there are much worse database technologies to be using.

## [Docker](https://www.docker.com/)

We will be using docker to containerize our Microservice and SQL Database. Docker is the industry standard. When Betterflye is in production, it will be hosted on AWS, so if our applications already run inside containers, there will be less work for the client to do once our Capstone project is finished.