# Node API Proxy Server

Server used for hiding API keys, rate limiting and caching.

## Usage

### Install dependencies

```bash
npm install
```

### Run on http://localhost:3000

```bash
npm start
```

### Add public API info

**.env**

If the public API URL is **https://api.openweathermap.org/data/2.5/weather?q={city}&appid={APIkey}**

- API_BASE_URL = "https://api.openweathermap.org/data/2.5/weather"
- API_KEY_NAME = "appid"
- API_KEY_VALUE = "YOUR API KEY"
