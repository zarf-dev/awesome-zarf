# Awesome Zarf [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of **awesome Zarf packages**, resources, tools, and ecosystem contributions for deploying software in **airgapped**, **semi-connected**, and **connected** environments.

This list showcases the incredible work by the community: everything from `init` packages that bootstrap clusters to complex application packages, tools, and reusable components.

This repository is also available to provide a central location for any packages the community wishes to collaborate on directly. 

Inspired by [awesome](https://github.com/sindresorhus/awesome).

---

## Table of Contents

- [What is Zarf?](#what-is-zarf)
- [Community Packages](#community-packages)
  - [Appliance Packages](#appliance-distro-packages)
  - [Init Packages](#init-packages)
  - [Application Packages](#application-packages)
- [Zarf Tools & Extensions](#zarf-tools--extensions)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)
- [License](#license)

---

## What is Zarf?

> Zarf makes it easy to package and deploy software into disconnected or secure environments.

📦 Zarf packages are declarative, auditable, and easy to create. Each package can bundle containers, Helm charts, raw manifests, data files, binaries, and more.

🔐 Perfect for government, defense, and industry use cases where traditional CI/CD pipelines can't reach.

Learn more: [zarf.dev](https://zarf.dev) | [GitHub](https://github.com/zarf-dev/zarf)

---

## Community Packages

### Appliance (distro) Packages

| Package | Description | Maintainer | Link |
|--------|-------------|------------|------|
| K3S | Zarf K3S package | @zarf-dev | [Zarf](https://github.com/zarf-dev/zarf/tree/main/packages/distros/k3s) |

### Init Packages

| Package | Description | Maintainer | Link |
|--------|-------------|------------|------|
| zarf-init | Standard init package for clusters | @zarf-dev | [Zarf](https://github.com/zarf-dev/zarf) |

---

### Application Packages

| Package | Description | Maintainer | Link |
|--------|-------------|------------|------|
| Wordpress | Wordpress community package | @zarf-dev | [Package](./community/applications/wordpress/zarf.yaml) |

---

## Zarf Tools & Extensions

| Tool | Description | Maintainer | Link |
|------|-------------|------------|------|
| Setup Zarf | GitHub Action for installing Zarf in GitHub Runners | @zarf-dev | [GitHub](https://github.com/zarf-dev/setup-zarf) |


---

## Learning Resources

| Resource | Description | Author | Link |
|---------|-------------|--------|------|
| Zarf Docs | Official documentation site | @zarf-dev | [zarf.dev/docs](https://zarf.dev/docs) |
| Zarf YouTube | Zarf official YouTube Channel | @zarf-dev | [YouTube](https://www.youtube.com/@Zarf-dev) |

---

## Contributing

Want to add your package, tool, or tutorial? We welcome community contributions!

📩 **[Submit a Pull Request](https://github.com/zarf-dev/awesome-zarf/pulls)** with:
- Name and description of your contribution
- Link to your repo or resource
- Place it in the correct table (alphabetically sorted)

> See our [CONTRIBUTING.md](./CONTRIBUTING.md) for full guidelines.

---

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](./LICENSE).

---

> Maintained by the [Zarf](https://github.com/defenseunicorns/zarf) community. You rock. 🤘
