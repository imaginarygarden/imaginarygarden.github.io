---
title: "Vehicle Tracking"
description: "Self-hosted web application for managing vehicles, refueling history, fuel consumption, mileage, and running costs"
external_url: "https://github.com/imaginarygarden/vehicletracking"
tags:
  - C#
  - ASP.NET Core
  - Blazor
  - PostgreSQL
  - Docker
---

Self-hosted vehicle management application for recording vehicles and refueling history while automatically calculating fuel consumption, mileage, and operating costs from the stored data.

Key features:
- **Vehicle Management:** Create, edit, list, and remove vehicles with user-scoped access
- **Fuel Tracking:** Record refueling date, odometer, fuel volume, price, and full-tank status
- **Statistics:** Calculates average consumption, fuel costs, distance traveled, price per liter, and cost per kilometer
- **Authentication:** Account registration, cookie-based sessions, authorization policies, and role-aware access
- **Persistent Storage:** PostgreSQL database integration through Entity Framework Core
- **Responsive UI:** Blazor interface built with MudBlazor and light/dark themes
- **Self-Hosting:** Multi-stage Docker image and Docker Compose deployment configuration

Tech stack: C#, .NET 9, ASP.NET Core, Blazor, MudBlazor, Entity Framework Core, PostgreSQL, Docker
