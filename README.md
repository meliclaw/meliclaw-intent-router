# Meliclaw Intent Router (fork)

Producto interno: **Meliclaw Intent Classifier**.

<p>
<img alt="PyPI - Python Version" src="https://img.shields.io/pypi/pyversions/semantic-router?logo=python&logoColor=gold" />
<a href="https://github.com/aurelio-labs/semantic-router/graphs/contributors"><img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/aurelio-labs/semantic-router" />
<a href="https://github.com/aurelio-labs/semantic-router/commits/main"><img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/aurelio-labs/semantic-router" />
<img alt="" src="https://img.shields.io/github/repo-size/aurelio-labs/semantic-router" />
<a href="https://github.com/aurelio-labs/semantic-router/issues"><img alt="GitHub Issues" src="https://img.shields.io/github/issues/aurelio-labs/semantic-router" />
<a href="https://github.com/aurelio-labs/semantic-router/pulls"><img alt="GitHub Pull Requests" src="https://img.shields.io/github/issues-pr/aurelio-labs/semantic-router" />
<a href="https://github.com/aurelio-labs/semantic-router/blob/main/LICENSE"><img alt="Github License" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
</p>

- Crate: [`meliclaw-intent-router`](crates/meliclaw-intent-router)
- Servicio: [`meliclaw-intent-router-service`](crates/meliclaw-intent-router-service)
- Rama de trabajo: `meliclaw-intent-router-main`
- Espejo upstream: `main` (no modificar)

Port Rust (MIT, obra derivada) del algoritmo publicado en
https://github.com/aurelio-labs/semantic-router
(Copyright 2024 Aurelio AI, MIT). Texto de licencia en [`LICENSE`](LICENSE).
Atribución factual: [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md).
Parches: [`MELICLAW_PATCHES.md`](MELICLAW_PATCHES.md).

El árbol Python del upstream permanece como referencia. El artefacto de
Meliclaw es el workspace Cargo.

```bash
cargo test -p meliclaw-intent-router
cargo run -p meliclaw-intent-router-service
```

Capas 2–3 (waterfall + RRF) **no** están en este repositorio.
