<p align="center">
  <img src="https://avatars.githubusercontent.com/u/339198347?s=200" width="120" alt="Snugmo logo: The Bond" />
</p>

<h1 align="center">snugmo</h1>

<p align="center">
  <em>A snug little home for your agents' dev environment.</em>
</p>

---

Snugmo builds self-hostable development environments where **you and your coding agent share the same workspace**: one terminal for the human, one for the agent, the same files, the same tools — inside a container that keeps both of them cozy and contained.

Our logo, *The Bond*, is a soft capsule holding a single molecule: the bond between your terminal and your agent.

## 🏠 The house

| Project | What it is | Status |
| --- | --- | --- |
| **cote** | Base OCI image for the Snugmo agent dev environment — a shelter where a human and an agent work side by side. | 🚧 in the oven |
| [**flue**](https://github.com/snugmo/flue) | A narrow channel from your host's SSH agent into the cote. Forwards `SSH_AUTH_SOCK` into containers with host-side filtering, so `git push` works without handing your keys to the agent. | 🔥 early |
| [**inglenook**](https://github.com/snugmo/inglenook) | A bootc OS image — a small Linux desktop to sit by the fire and reach your dev environment from. | 🔥 early |

## 🪵 What we care about

- **Self-hosted first** — runs on your own hardware, no cloud account required.
- **Open-weight friendly** — designed to work with locally served models.
- **Narrow channels** — agents get exactly the access they need, and nothing slips up the chimney.
- **Declarative** — images and infrastructure defined in code, rebuilt rather than hand-tuned.

## 📜 License

Snugmo projects are licensed under the [AGPL-3.0](https://www.gnu.org/licenses/agpl-3.0.html) unless stated otherwise in the repository.

---

<p align="center"><sub>Pull up a chair. 🔥</sub></p>
