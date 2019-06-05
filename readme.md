# Wait-for-it.js

Node wrapper for [wait-for-it.sh](https://github.com/vishnubob/wait-for-it).

## How to use

```bash
npm install https://github.com/lucaslugao/wait-for-it.js

wait-for-it host:port [-s] [-t timeout] [-- command args]
    -h HOST | --host=HOST       Host or IP under test
    -p PORT | --port=PORT       TCP port under test
                                Alternatively, you specify the host and port as host:port
    -s | --strict               Only execute subcommand if the test succeeds
    -q | --quiet                Don't output any status messages
    -t TIMEOUT | --timeout=TIMEOUT
                                Timeout in seconds, zero for no timeout
    -- COMMAND ARGS             Execute command with args after the test finishes
```

## License

[MIT](LICENSE) © Lucas Lugao

