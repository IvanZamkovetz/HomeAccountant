# HomeAccountent
An application for home accounting using C#/ASP.NET self-hosted WebAPI with SQL14 DataBase and AngularJS Web application for users access.

Purpose of application:
This application represents a home accounting system allowing users to track their costs, control current financial balance and make future predictions.

Key features:
- “Smart” DataBase with service procedures/functions for easy data management;

- LightWeight C# framework Dapper for DataBase access;
- WebAPI Oauth Authentication;
- Asynchronous actions in API controllers;
- using dynamic C# types directly as http response JSON data;

- Single Page Web application for access to WebAPI;
- Custom reusable Angular directives, SSE;
- Highcharts and KendoUI components;

Target device/platform for WebAPI/DataBase:
Windows8.1/10 with .NET4.5 and SQL14 Engine

Target device/platform for Web FrontEnd:
Windows7/8.1/10, FireFox/Opera/Chrome

Tools:
SQL14Server, VisualStudio2013, TypeScript, FireFox+FireBug.

Application frameworks/components:
SQL14 database;
Microsoft WebAPI OWIN self hosted farmework, Dapper provider, OAuthAuthenticationProvider;
AngularJS+TypeScript, HighCharts, KendoUI

Used patterns:
MultiLayered solution, generic repository design pattern, single responsibility principle;
AngularJS MVC
