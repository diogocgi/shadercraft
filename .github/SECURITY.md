# Security policy

## Reporting a vulnerability

**Do not open a public issue for a security vulnerability.**

Report it privately, in either of these ways:

1. **GitHub private vulnerability reporting** — the **Report a vulnerability** button under this repository's **Security** tab. This opens a private advisory that only the maintainers can see.
2. **Email** — [shadercraftpt@gmail.com](mailto:shadercraftpt@gmail.com), with `SECURITY` in the subject line.

Please include what an attacker can do, the steps to reproduce it, and the version and platform you tested on. A proof of concept helps, but do not attach one to a public issue.

You will get an acknowledgement within a few days. Once a fix ships, we are happy to credit you in the advisory unless you would rather stay anonymous.

## Scope

In scope: the ShaderCraft editor and the shadercraft.com website — anything that lets a crafted document, image, mesh, or link read data it should not, run code outside the page, or reach another user's projects.

Out of scope: findings that only affect a browser or GPU driver, missing hardening headers with no demonstrated impact, denial of service by feeding the editor an enormous file, and automated scanner output without a working reproduction.

## Please avoid

Testing against other people's accounts or projects, and any testing that degrades the service for others.
