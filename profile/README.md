# Swift IETF

Swift implementations of IETF (Internet Engineering Task Force) specifications — a per-authority organization of [swift-standards](https://github.com/swift-standards), Layer 2 of the [Swift Institute](https://github.com/swift-institute) ecosystem.

## What this is

One package per specification, named `swift-rfc-<number>`. Each package implements its source document as literally as possible — parsing, validation, and formatting enforced by Swift's type system — and defines its own namespace (`RFC_3986`). Where several specifications govern one subject, the unifying `swift-*-standard` package lives in [swift-standards](https://github.com/swift-standards).

## Coverage

**HTTP** — [RFC 7230](https://github.com/swift-ietf/swift-rfc-7230) · [RFC 7231](https://github.com/swift-ietf/swift-rfc-7231) · [RFC 7232](https://github.com/swift-ietf/swift-rfc-7232) · [RFC 7233](https://github.com/swift-ietf/swift-rfc-7233) · [RFC 7234](https://github.com/swift-ietf/swift-rfc-7234) · [RFC 7235](https://github.com/swift-ietf/swift-rfc-7235) · [RFC 9110](https://github.com/swift-ietf/swift-rfc-9110) · [RFC 9111](https://github.com/swift-ietf/swift-rfc-9111) · [RFC 9112](https://github.com/swift-ietf/swift-rfc-9112) · [RFC 9113](https://github.com/swift-ietf/swift-rfc-9113) · [RFC 9114](https://github.com/swift-ietf/swift-rfc-9114) · [RFC 6265](https://github.com/swift-ietf/swift-rfc-6265) · [RFC 6585](https://github.com/swift-ietf/swift-rfc-6585) · [RFC 7616](https://github.com/swift-ietf/swift-rfc-7616) · [RFC 7617](https://github.com/swift-ietf/swift-rfc-7617) · [RFC 8288](https://github.com/swift-ietf/swift-rfc-8288) · [RFC 9457](https://github.com/swift-ietf/swift-rfc-9457) · [RFC 8030](https://github.com/swift-ietf/swift-rfc-8030)

**Transport & TLS** — [RFC 768](https://github.com/swift-ietf/swift-rfc-768) · [RFC 9293](https://github.com/swift-ietf/swift-rfc-9293) · [RFC 9000](https://github.com/swift-ietf/swift-rfc-9000) · [RFC 6455](https://github.com/swift-ietf/swift-rfc-6455) · [RFC 8446](https://github.com/swift-ietf/swift-rfc-8446) · [RFC 7301](https://github.com/swift-ietf/swift-rfc-7301)

**Internet protocol** — [RFC 791](https://github.com/swift-ietf/swift-rfc-791) · [RFC 8200](https://github.com/swift-ietf/swift-rfc-8200) · [RFC 4291](https://github.com/swift-ietf/swift-rfc-4291) · [RFC 4007](https://github.com/swift-ietf/swift-rfc-4007) · [RFC 5952](https://github.com/swift-ietf/swift-rfc-5952)

**DNS** — [RFC 1034](https://github.com/swift-ietf/swift-rfc-1034) · [RFC 3596](https://github.com/swift-ietf/swift-rfc-3596) · [RFC 6891](https://github.com/swift-ietf/swift-rfc-6891)

**URI** — [RFC 3986](https://github.com/swift-ietf/swift-rfc-3986) · [RFC 6570](https://github.com/swift-ietf/swift-rfc-6570)

**Security, OAuth & JOSE** — [RFC 5280](https://github.com/swift-ietf/swift-rfc-5280) · [RFC 6749](https://github.com/swift-ietf/swift-rfc-6749) · [RFC 6750](https://github.com/swift-ietf/swift-rfc-6750) · [RFC 7636](https://github.com/swift-ietf/swift-rfc-7636) · [RFC 7515](https://github.com/swift-ietf/swift-rfc-7515) · [RFC 7516](https://github.com/swift-ietf/swift-rfc-7516) · [RFC 7517](https://github.com/swift-ietf/swift-rfc-7517) · [RFC 7519](https://github.com/swift-ietf/swift-rfc-7519) · [RFC 6238](https://github.com/swift-ietf/swift-rfc-6238)

**Email & MIME** — [RFC 2822](https://github.com/swift-ietf/swift-rfc-2822) · [RFC 6531](https://github.com/swift-ietf/swift-rfc-6531) · [RFC 8058](https://github.com/swift-ietf/swift-rfc-8058) · [RFC 2046](https://github.com/swift-ietf/swift-rfc-2046) · [RFC 2183](https://github.com/swift-ietf/swift-rfc-2183) · [RFC 7578](https://github.com/swift-ietf/swift-rfc-7578)

**Data formats** — [RFC 8259](https://github.com/swift-ietf/swift-rfc-8259) · [RFC 6902](https://github.com/swift-ietf/swift-rfc-6902) · [RFC 7396](https://github.com/swift-ietf/swift-rfc-7396) · [RFC 8949](https://github.com/swift-ietf/swift-rfc-8949) · [RFC 7405](https://github.com/swift-ietf/swift-rfc-7405)

**Identifiers & language** — [RFC 4122](https://github.com/swift-ietf/swift-rfc-4122) · [RFC 9562](https://github.com/swift-ietf/swift-rfc-9562) · [RFC 5646](https://github.com/swift-ietf/swift-rfc-5646) · [BCP 47](https://github.com/swift-ietf/swift-bcp-47) · [RFC 9557](https://github.com/swift-ietf/swift-rfc-9557)

Every repository description carries the specification's full title; the [repositories tab](https://github.com/orgs/swift-ietf/repositories) lists them all.

## Status

Public alpha. Maintained by [Coen ten Thije Boonkkamp](https://github.com/coenttb) — contributions welcome via pull request.

## License

All packages use the Apache License 2.0.
