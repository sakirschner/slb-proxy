# student-leader-board-api-proxy

NGINX proxy app for [slb-api](https://github.com/sakirschner/slb-api)

## Usage

### Environment Variables

 - `LISTEN_PORT` - Port to listen on (default: `8000`)
 - `APP_HOST` - Hostname of the app to forward requests to (default: `app`)
 - `APP_PORT` - Port of the app to forward requests to (default: `9000`)
