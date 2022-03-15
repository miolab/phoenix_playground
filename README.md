# Phoenix playground

Prepared for experimental use only.:penguin:

## Versions

```
➜ docker compose run --rm app elixir --version
Erlang/OTP 24 [erts-12.3] [source] [64-bit] [smp:4:4] [ds:4:4:10] [async-threads:1] [jit]

Elixir 1.13.3 (compiled with Erlang/OTP 24)

➜ docker compose run --rm app mix archive
* hex-1.0.1
* phx_new-1.6.6
Archives installed at: /root/.mix/archives

➜ docker compose run --rm db psql --version
psql (PostgreSQL) 12.10
```
