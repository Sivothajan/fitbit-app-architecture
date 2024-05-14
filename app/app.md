# Application
## /app/

This folder contains the application logic which executes on the device. Code in this folder has access to the [Device API](https://dev.fitbit.com/build/reference/device-api/) and is capable of interacting directly with the presentation layer, communicating with the companion, or reading and writing settings.

An <code>index.js</code> or <code>index.ts</code> file must exist in this folder, and must not be empty, or the build process will fail.
