# Tech Stack

## Technologies

- PHP
- Xamarin Forms
- MonkeyCache
- MySQL
- Docker

## [PHP](https://www.php.net/)

The current Betterflye implementation features a publicly accessible API written in PHP. The mobile application will consume this API to communicate with the backend. There is the option option of writing a new API in ASP.NET Core, but it makes sense to use what is already there rather than reinvent the wheel.

## [Xamarin](https://dotnet.microsoft.com/apps/xamarin)

The mobile application will be written in C#, using the Xamarin Framework. Xamarin was chosen because it is in the Microsoft tech stack and is a cross-platform mobile development library. With Xamarin.Forms specifically, about 96% code reusability can be achieved. Additionally, Visual Studio's Android emulator has a hot-reload feature that is *almost* on parity with Flutter's. The immediate feedback gained from this feature will increase development productivity. Since Xamarin is the oldest cross platform library, it's likely that the majority of issues encountered will already have a forum post and solution.

## [MonkeyCache](https://github.com/jamesmontemagno/monkey-cache)

MonkeyCache is a Xamarin package that will be used to cache data client-side. MonkeyCache was chosen because it both supports encrypted storage for credentials and setting an expiration for any items that are added to the cache. This package is also cross platform.

## [MySQL](https://www.mysql.com/)

The client uses MySql as their database technology.

## [Docker](https://www.docker.com/)

Docker will be used to containerize the API and SQL Database. Docker is the industry standard. When Betterflye is in production, it will be hosted on AWS, so if applications already run inside containers, there will be less work for the client to do once the Capstone project is finished.
