# dockerized-devtools
Docker image contains tools for backend developers

## Tools available

* `telnet`
* [jkbrzt/httpie](https://github.com/jkbrzt)

  > CLI HTTP client, user-friendly curl replacement with intuitive UI, JSON support, syntax highlighting, wget-like downloads, extensions, etc. http://httpie.org

## Usage example

```bash
docker run --rm  andromedarabbit/devtools bash -c 'http'
```

Once you have run this command you will get printed messages from `httpie`!

```bash
usage: http [--json] [--form] [--pretty {all,colors,format,none}]
          [--style STYLE] [--print WHAT] [--headers] [--body] [--verbose]
          [--all] [--history-print WHAT] [--stream] [--output FILE]
          [--download] [--continue]
          [--session SESSION_NAME_OR_PATH | --session-read-only SESSION_NAME_OR_PATH]
          [--auth USER[:PASS]] [--auth-type {basic,digest,oauth1}]
          [--proxy PROTOCOL:PROXY_URL] [--follow]
          [--max-redirects MAX_REDIRECTS] [--timeout SECONDS]
          [--check-status] [--verify VERIFY]
          [--ssl {ssl2.3,ssl3,tls1,tls1.1,tls1.2}] [--cert CERT]
          [--cert-key CERT_KEY] [--ignore-stdin] [--help] [--version]
          [--traceback] [--default-scheme DEFAULT_SCHEME] [--debug]
          [METHOD] URL [REQUEST_ITEM [REQUEST_ITEM ...]]
http: error: too few arguments
```
