# @capire/data-viewer

This is a CAP plugin which adds a generic browser for data to your application.
It is used in the `bookstore` sample.

> [!CAUTION]
> This is just a sample, not intended for production use. It is meant to demonstrate how to create a CAP plugin and how to use it in your application. It is not optimized for performance or security.


### Reuse

```bash
npm add @capire/data-viewer
```

<details>
  <summary><i> Requires this in your .npmrc: </i></summary>

  ```java
  @capire:registry=https://npm.pkg.github.com
  ```
</details>


### Plug & Play

Following the plug & play principle of CAP plugins, adding this dependency to your project will add a service for browsing all your data, served automatically at `/data`.
