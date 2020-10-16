# Tech Stack

## Technologies

- ASP.NET Core
- Xamarin Forms
- MonkeyCache
- MySQL
- Docker

## [PHP](https://www.php.net/)

The current Betterflye implementation features a publicly accessible API written in PHP. We will take advantage of this API so that our mobile application can communicate with the backend. We do have the option of writing our own API, but it wouldn't make sense to not use something that's already done for us.

## [Xamarin](https://dotnet.microsoft.com/apps/xamarin)

We will be using Xamarin for our Mobile Application code. We chose Xamarin because it is also in the Microsoft tech stack and is a cross-platform mobile development library. With Xamarin.Forms specifically, we can achieve about 96% code reusability and only have to write 4% platform specific code. Additionally, Visual Studio's Android emulator has a hot-reload feature that is *almost* on parity with Flutter's. The immediate feedback we'll gain from this feature will increase our development productivity. Since Xamarin is the oldest cross platform library, we're hoping that the majority of issues we might run into will have been encountered before and that the platform will be more stable than newer versions.

## [MonkeyCache](https://github.com/jamesmontemagno/monkey-cache)

MonkeyCache is a Xamarin package that we will take advantage of in order to cache data client-side. We chose MonkeyCache because it both supports encrypted storage for credentials and setting an expiration for any items that are added to the cache. This package is also cross platform..

## [MySQL](https://www.mysql.com/)

We didn't have a choice for the database technology -- the client already uses MySql so we need to follow suite. We love MySql though :), there are much worse database technologies to be using.

## [Docker](https://www.docker.com/)

We will be using docker to containerize our Microservice and SQL Database. Docker is the industry standard. When Betterflye is in production, it will be hosted on AWS, so if our applications already run inside containers, there will be less work for the client to do once our Capstone project is finished.