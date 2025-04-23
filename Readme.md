本项目是基于 SafeLine（雷池）WAF 的 Kubernetes 部署练习版本。通过将雷池 WAF 集成到 Kubernetes 环境中，帮助用户快速熟悉容器化部署、Kubernetes 编排以及如何在云原生架构中保护 Web 应用免受攻击。

雷池 WAF 是一款简单易用且效果显著的 Web 应用防火墙（WAF），能够过滤和监控 Web 应用与互联网之间的 HTTP 流量，有效防御 SQL 注入、XSS、命令注入、路径遍历等多种威胁。本练习版本专为学习和研究设计，旨在帮助用户掌握 Kubernetes 技术栈的同时，了解 WAF 的工作原理及其在生产环境中的应用。

### 免责声明

本项目为开源软件，仅供学习、研究和交流使用，**不得用于生产环境**。开发者已尽可能确保代码的正确性和稳定性，但由于项目中存在大量明文配置、未优化的逻辑以及其他潜在问题，可能会导致不可预见的安全性或功能性问题。

#### 使用者责任

1. **风险自担**：使用本项目的用户需自行承担因使用本软件而产生的任何风险。开发者不对因使用本软件而导致的任何直接或间接损失负责。
2. **非生产用途**：本项目不适合在生产环境中使用，任何因将本项目部署到生产环境而导致的问题均由使用者自行承担责任。
3. **安全性**：项目中可能存在未加密的敏感信息、默认密码或其他安全漏洞。使用者需自行检查并修复这些问题后方可用于实际场景。

#### 开源性质

1. **无技术支持**：本项目以开源形式提供，开发者不承诺提供任何形式的技术支持或后续更新。
2. **贡献与改进**：欢迎社区用户提交问题、建议或代码贡献，但开发者不保证所有问题都能得到解决或所有功能需求都会被实现。

#### 版权声明

本项目遵循 [MIT License] 开源协议。未经许可，不得将本项目用于商业用途或未经授权的分发。

#### 其他说明

- 本项目仅用于帮助用户熟悉部署流程、学习相关技术知识以及进行合法范围内的交流讨论。
- 使用者需遵守所有相关的法律法规，并对自身的使用行为负责。

---

This project is a Kubernetes deployment practice version based on SafeLine WAF . By integrating SafeLine WAF into a Kubernetes environment, this project helps users quickly become familiar with containerized deployment, Kubernetes orchestration, and how to protect web applications from attacks in a cloud-native architecture.

SafeLine WAF is a simple yet highly effective Web Application Firewall (WAF) that filters and monitors HTTP traffic between web applications and the Internet, effectively defending against threats such as SQL injection, XSS, command injection, path traversal, and more. This practice version is designed for learning and research purposes, aiming to help users master Kubernetes technologies while understanding the principles of WAF and its application in production environments.

### Disclaimer

This project is open-source software intended solely for learning, research, and communication purposes. It **must not be used in production environments**. The developers have made every effort to ensure the correctness and stability of the code; however, due to the presence of numerous plaintext configurations, unoptimized logic, and other potential issues within the project, unforeseen security or functional problems may arise.

#### User Responsibilities

1. **Use at Your Own Risk**: Users of this project assume all risks associated with its use. The developers are not responsible for any direct or indirect damages caused by using this software.
2. **Not Suitable for Production**: This project is unsuitable for deployment in production environments. Any issues arising from such deployments are the sole responsibility of the user.
3. **Security Concerns**: The project may contain unencrypted sensitive information, default passwords, or other vulnerabilities. Users must inspect and address these issues before applying the project to real-world scenarios.

#### Open Source Nature

1. **No Technical Support**: This project is provided as-is under an open-source model. Developers do not guarantee any form of technical support or future updates.
2. **Contributions Welcome**: Contributions, bug reports, and feature requests from the community are welcome, but there is no assurance that all issues will be resolved or that all requested features will be implemented.

#### Copyright Notice

This project adheres to the [MIT License]. Unauthorized commercial use or redistribution without permission is prohibited.

#### Additional Notes

- This project aims to assist users in familiarizing themselves with deployment processes, learning relevant technical knowledge, and engaging in lawful discussions.
- Users must comply with all applicable laws and regulations and are responsible for their actions when using this project.
