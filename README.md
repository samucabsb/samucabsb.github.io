# SAMUEL RODRIGUES — AI & Software Engineering Portfolio

> **Live Deployment:** **[samucabsb.github.io](https://samucabsb.github.io/)**

Portfólio técnico construído sob a estética **Swiss Brutalism & Latent Tensor Vector Field**, projetado com foco em **simpatia mecânica**, zero dependências externas e renderização matemática a **120–240 FPS**.

---

## Especificações de Arquitetura

| Camada | Implementação Técnica |
| :--- | :--- |
| **Pegada de Rede (Payload)** | `39 KB` arquivo único (`~7.2 KB` Gzip) • `FCP < 15ms` |
| **Dependências Externas** | `0` pacotes npm • `0` frameworks JS • `100%` Vanilla HTML5 / CSS Grid / Canvas 2D |
| **Motor Gráfico (Canvas 2D)** | Campo vetorial contínuo $\theta(x,y,t) = (\sin(kx + \omega_x t) + \cos(ky + \omega_y t))\pi$ com vórtice interativo |
| **Otimização de GPU** | *Batched Path Rendering*: `140` vetores agrupados em apenas **`2` draw calls (`ctx.stroke()`) por frame** |
| **Compositor & DOM** | Canal alpha desativado (`{ alpha: false }`), *squared-distance culling* (`distSq < 40000`) e telemetria sincronizada ao `requestAnimationFrame` |
| **CI/CD** | Deploy automatizado via GitHub Actions (`.github/workflows/deploy.yml`) |

---

## Contato & Links

- **Portfólio Interativo:** [https://samucabsb.github.io/](https://samucabsb.github.io/)
- **LinkedIn:** [linkedin.com/in/samuel-rodrigues-tech](https://www.linkedin.com/in/samuel-rodrigues-tech/)
- **E-mail:** [samuca.9706@gmail.com](mailto:samuca.9706@gmail.com)
