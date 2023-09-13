# deep_space_network_api

<p align="center">
    <img src="https://eyes.nasa.gov/dsn/images/spacecraft/james%20webb%20space%20telescope.jpg" width="300px" alt="dsn"/>
</p>

live deep space network API 📡

<h3>Install all packages</h3>

```cmd
npm install
```

<h3>run the api server</h3>

```cmd
npm run api
```

<p>🟠using the post method to get the data</p>

<h3>Get the stations data</h3>

```http
POST / HTTP/1.1
Host: localhost:3001
Content-Type: application/json
Content-Length: 30

{
    "request": "station"
}
```

<h3>Get the antennas data</h3>

```http
POST / HTTP/1.1
Host: localhost:3001
Content-Type: application/json
Content-Length: 30

{
    "request": "dish"
}
```

<h3>Get the all data</h3>

```http
POST / HTTP/1.1
Host: localhost:3001
Content-Type: application/json
Content-Length: 30

{
    "request": "all"
}
```


