## Node.js and backend

- Internals and concepts
  - Strong and weak sides of node.js c
  - Stateful and stateless servers c
  - Nonblocking I/O and blocking code c
  - Event loop phases c
  - Event loop microtasks and macrotasks c
  - Garbage collection c
  - Node.js LTS schedule c
  - I/O-bound, CPU-bound, memory-bound tasks c
  - Interactive applications (close to real-time) c
- Modularity, layers and dependencies
  - CommonJS modules c
  - ECMAScript modules c
  - Module `node:module` c
  - Caching in CJS and ESM c
  - Modules as singletons c
  - Contexts and scripts module `node:vm` c
  - Dependencies: `npm`, `node_modules` c
  - Files `package.json`, `package-lock.json` c
  - Module-based permissions model c
  - Isolation with modularity c
  - Dependency injection c
  - DI containers c
  - Coupling and cohesion c
  - Framework agnostic approach c
- Environment
  - Command line arguments c
  - Node.js CLI c
  - Process-based permissions c
  - Graceful shutdown c
  - Clustering c
  - Watch filesystem changes with --watch c
- Internal API
  - Streams API c
  - Web Streams API c
  - Crypto API c
  - Password hashing with crypto.scrypt c
  - Web Crypto API c
  - File system API (sync and async) c
  - Copy folder recursively c
  - Worker threads c
  - Performance hooks c
  - Native fetch and nodejs/undici c
  - async_hooks c
  - AsyncLocalStorage c
  - AsyncResource c
  - Deprecated domain API c
  - Node.js single executable c
  - SharedArrayBuffer c
  - Module `node:worker_threads` c
  - Module `node:child_process` c
  - MessageChannel, MessagePort c
  - BroadcastChannel c
  - Generating crypto random UUID c
  - Module `node:url` vs `new URL` c
  - Module `node:assert` c
  - Internationalization c
  - Blob, File, Buffer, module `node:buffer` c
  - Module `node:zlib` c
- Network
  - Endpoint throttling c
  - ALPN r
  - SNI callback r
  - SSL certificates c
  - Protocol agnostic approach r
  - Fetch API c
  - IncomingMessage c
  - HTTP(S) c
  - TCP/SSL c
  - UDP c
  - TLS c
  - Websocket c
  - SSE r
  - HTTP/3 (QUIC) r
  - Long pollingr 
  - REST c
  - RPC c
  - Routing c
  - DoS c
  - DDoS c
  - XSS
  - Path traversal c
  - CSRF c
  - DNS c
  - SQL injection c
  - noDelay c
  - keep-alive c
  - IP sticky sessions c
- Technique and tools
  - Native test runner c
  - Logging c
  - Application configuring c
  - Testing c
  - CI/CD r
  - Readable c
  - Writable c
  - Transform c
  - Back pressure c
  - Buffer c
  - Console c
  - Inspector c
- Data access
  - Data access layer c
  - Repository c
  - Active record c
  - Query builder c
  - Object-Relational Mapping c
  - CRUD c
  - DTO c
- Error handling and debugging
  - `Error` c
  - `error.cause` c
  - `error.code` c
  - `error.message` c
  - `error.stack` c
  - `Error.captureStackTrace` c
  - How to avoid mixins c
  - Uncaught exceptions c
  - Heap dump c
  - Debugging tools c
  - Flame graph c
  - Memory leaks c
  - Resource leaks c
  - Data race c
- Integrations and bindings
  - Native addons r
  - `C` and `C++` addons r
  - `Rust` addons e
  - `Zig` addons e
  - NAN (Native Abstractions for Node.js) e
  - Node-API (formerly N-API) e
  - NAPI `C` and `C++` e
  - NAPI `Rust` e
  - NAPI `Zig` e
  - Webassembly `WAT` e
  - Webassembly `C` and `C++` e
  - Webassembly `Rust` e
  - Webassembly `Zig` e 
  - Webassembly `AssemblyScript` e
  - Shared memory e
  - V8 binary serialization 
