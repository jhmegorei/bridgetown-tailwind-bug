```
➤ bin/bridgetown start
[Bridgetown]           Starting: Bridgetown v1.3.2 (codename "Kelly Butte")
[Server] * Puma version: 6.4.2 (ruby 3.3.0-p0) ("The Eagle of Durango")
[Server] * PID: 12762
[Server] * Listening on http://0.0.0.0:4000
[Server] Use Ctrl-C to stop
[Frontend] touch frontend/styles/jit-refresh.css
[Frontend] yarn run esbuild-dev
[Frontend] yarn run v1.22.19
[Frontend] $ node esbuild.config.js --watch
[Bridgetown]        Environment: development
[Bridgetown]             Source: /Users/jhaubold/projects/privat/bridgetown-tailwind-bug/src
[Bridgetown]        Destination: /Users/jhaubold/projects/privat/bridgetown-tailwind-bug/output
[Bridgetown]     Custom Plugins: /Users/jhaubold/projects/privat/bridgetown-tailwind-bug/plugins
[Bridgetown]         Generating…
[Frontend] esbuild: frontend bundling started...
[Bridgetown]         Pagination: disabled. Enable in site config with pagination:\n enabled: true
[Bridgetown]            esbuild: The `css' asset could not be found.
[Bridgetown]            esbuild: Double-check your frontend config or re-run `bin/bridgetown frontend:build'
[Bridgetown]             Done! 🎉 Completed in less than 0.6 seconds.
[Bridgetown]
[Bridgetown]     Now serving at: http://localhost:4000
[Bridgetown]                     http://192.168.178.70:4000
[Bridgetown]
[Server] 127.0.0.1 - - [21/Jan/2024:23:23:12 +0100] "GET /test HTTP/1.1" 404 2561 0.0005
[Frontend] >>> looping through outputs
[Frontend] {
[Frontend]   'output/_bridgetown/static/index.NCQMQHBI.js.map': { imports: [], exports: [], inputs: {}, bytes: 401 },
[Frontend]   'output/_bridgetown/static/index.NCQMQHBI.js': {
[Frontend]     imports: [],
[Frontend]     exports: [],
[Frontend]     entryPoint: 'frontend/javascript/index.js',
[Frontend]     cssBundle: 'output/_bridgetown/static/index.TSTMPP2Y.css',
[Frontend]     inputs: {
[Frontend]       'frontend/styles/index.scss': [Object],
[Frontend]       'frontend/styles/syntax-highlighting.css': [Object],
[Frontend]       'frontend/javascript/index.js': [Object]
[Frontend]     },
[Frontend]     bytes: 153
[Frontend]   },
[Frontend]   'output/_bridgetown/static/index.TSTMPP2Y.css.map': { imports: [], exports: [], inputs: {}, bytes: 10028 },
[Frontend]   'output/_bridgetown/static/index.TSTMPP2Y.css': {
[Frontend]     imports: [],
[Frontend]     inputs: {
[Frontend]       'frontend/styles/jit-refresh.css': [Object],
[Frontend]       'frontend/styles/index.scss': [Object],
[Frontend]       'frontend/styles/syntax-highlighting.css': [Object]
[Frontend]     },
[Frontend]     bytes: 4622
[Frontend]   }
[Frontend] }
[Frontend]   >>> processing output output/_bridgetown/static/index.NCQMQHBI.js.map
[Frontend]   >>> processing output output/_bridgetown/static/index.NCQMQHBI.js
[Frontend]     >>> value has an entrypoint
[Frontend]   >>> processing output output/_bridgetown/static/index.TSTMPP2Y.css.map
[Frontend]   >>> processing output output/_bridgetown/static/index.TSTMPP2Y.css
[Frontend]     >>> value is an index-file
[Frontend]     >>> using input frontend/styles/jit-refresh.css
[Frontend] >>> writing manifest {
[Frontend]   'javascript/index.js': 'index.NCQMQHBI.js',
[Frontend]   'styles/jit-refresh.css': 'index.TSTMPP2Y.css'
[Frontend] }
[Frontend] esbuild: frontend bundling complete!
[Frontend] esbuild: entrypoints processed:
[Frontend]          - index.NCQMQHBI.js: 153B
[Frontend]          - index.TSTMPP2Y.css: 4.51KB
[Bridgetown]          Reloading… 1 file changed at 2024-01-21 23:23:12
[Bridgetown]                     - .bridgetown-cache/frontend-bundling/manifest.json
[Server] 127.0.0.1 - - [21/Jan/2024:23:23:12 +0100] "GET /MISSING_ESBUILD_ASSET HTTP/1.1" 404 2561 0.0004
[Server] 127.0.0.1 - - [21/Jan/2024:23:23:12 +0100] "GET /_bridgetown/static/index.X2KBHGU6.js HTTP/1.1" 200 113 0.0004
[Server] 127.0.0.1 - - [21/Jan/2024:23:23:12 +0100] "GET /images/logo.svg HTTP/1.1" 200 8973 0.0003
[Server] 127.0.0.1 - - [21/Jan/2024:23:23:12 +0100] "GET /MISSING_ESBUILD_ASSET HTTP/1.1" 404 2561 0.0002
[Bridgetown]         Pagination: disabled. Enable in site config with pagination:\n enabled: true
[Bridgetown]            esbuild: The `css' asset could not be found.
[Bridgetown]            esbuild: Double-check your frontend config or re-run `bin/bridgetown frontend:build'
[Bridgetown]             Done! 🎉 Completed in less than 0.09 seconds.
[Bridgetown]
[Server] 127.0.0.1 - - [21/Jan/2024:23:23:12 +0100] "GET /favicon.ico HTTP/1.1" 200 - 0.0003
[Server] 127.0.0.1 - - [21/Jan/2024:23:23:12 +0100] "GET /_bridgetown/static/index.X2KBHGU6.js.map HTTP/1.1" 200 398 0.0003
```
