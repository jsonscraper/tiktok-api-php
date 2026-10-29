# 0.1.2

- Add a prominent MCP launch announcement after the library diagram, with separate mobile/desktop and light/dark variants.
- Document the unified jsonscraper MCP connection and independent Instagram/TikTok license linking.
- Improve mobile quick-start diagrams and give Postman its own row.
- Update package metadata and version-pinned installation examples for this release.

**Full changelog:** [0.1.1...0.1.2](https://github.com/jsonscraper/tiktok-api-php/compare/0.1.1...0.1.2)

# 0.1.1

- Simplify the first-request guide and method navigation.
- Add product-specific MCP connections for ChatGPT and Codex.
- Use numeric release names and installation references.

# 0.1.0

- Complete named access to 54 TikTok routes, plus `call()` and the existing fluent builder.
- Preserve positional signatures of existing methods; new methods accept query arrays.
- Fix accidental POST requests, URL query decoding, disabled TLS verification, credential debug output and undefined fallback errors.
- Authenticate custom builder requests automatically; reject absolute endpoint URLs and disable redirects.
- Add timeout/base URL configuration and injectable Guzzle client.
- Correct response status mapping and extend envelope/payload models.
- Use environment keys and correct autoloader paths in examples.
- Require PHP 8.1+ and only the extensions used by the HTTP client/model mapper. This raises the supported PHP minimum; use the prior release for legacy PHP runtimes.
