# caddy-just-abort-http


## Description

`caddy-just-abort-http` is a listener wrapper for Caddy that aborts incorrect HTTP requests sent to the TLS server.

This project is based on the code from [caddyhttp/httpredirectlistener.go](https://github.com/caddyserver/caddy/blob/v2.7.6/modules/caddyhttp/httpredirectlistener.go) in the [Caddy](https://github.com/caddyserver/caddy) repository.

## Usage

listener_wrappers {
	http_just_abort
	tls
}

See Also: https://caddyserver.com/docs/caddyfile/options#listener-wrappers

## License

This project is licensed under the [Apache License, Version 2.0](LICENSE).