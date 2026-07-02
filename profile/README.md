# Swift IETF

Swift implementations of IETF (Internet Engineering Task Force) specifications — a per-authority organization of [swift-standards](https://github.com/swift-standards), Layer 2 of the [Swift Institute](https://github.com/swift-institute) ecosystem.

## What this is

One package per specification, named `swift-rfc-<number>`. Each package implements its source document as literally as possible — parsing, validation, and formatting enforced by Swift's type system — and defines its own namespace (`RFC_3986`). Where several specifications govern one subject, the unifying `swift-*-standard` package lives in [swift-standards](https://github.com/swift-standards).

## Start here

| Package | Specification |
|---|---|
| [swift-rfc-9110](https://github.com/swift-ietf/swift-rfc-9110) | HTTP Semantics |
| [swift-rfc-3986](https://github.com/swift-ietf/swift-rfc-3986) | URI Generic Syntax |
| [swift-rfc-8259](https://github.com/swift-ietf/swift-rfc-8259) | JSON Data Interchange Format |
| [swift-rfc-8446](https://github.com/swift-ietf/swift-rfc-8446) | TLS 1.3 |
| [swift-rfc-7519](https://github.com/swift-ietf/swift-rfc-7519) | JSON Web Token (JWT) |
| [swift-rfc-9562](https://github.com/swift-ietf/swift-rfc-9562) | Universally Unique IDentifiers (UUIDs) |

## Browse everything

The [repositories tab](https://github.com/orgs/swift-ietf/repositories) lists every package with its full specification title — to check whether a specific RFC is covered, search its number there. Or browse by domain:

[http](https://github.com/orgs/swift-ietf/repositories?q=http) · [email](https://github.com/orgs/swift-ietf/repositories?q=email) · [json](https://github.com/orgs/swift-ietf/repositories?q=json) · [oauth](https://github.com/orgs/swift-ietf/repositories?q=oauth) · [tls](https://github.com/orgs/swift-ietf/repositories?q=tls) · [dns](https://github.com/orgs/swift-ietf/repositories?q=dns) · [uri](https://github.com/orgs/swift-ietf/repositories?q=uri) · [uuid](https://github.com/orgs/swift-ietf/repositories?q=uuid) · [abnf](https://github.com/orgs/swift-ietf/repositories?q=abnf)

## Status

Public alpha — packages are being released RFC by RFC. Maintained by [Coen ten Thije Boonkkamp](https://github.com/coenttb) — contributions welcome via pull request.

## License

All packages use the Apache License 2.0.
