  # Martijn Scholten

  Platform engineer building Kubernetes platforms and the developer experience on top of them. I spent years as a full-stack developer before moving into infrastructure,
   which shapes how I build platforms — they should feel like something developers actually want to use.

  ## What I Do

  I design and operate Kubernetes platforms, cloud infrastructure, and the automation around them. Day-to-day: AWS, Kubernetes, OpenShift, Terraform, ArgoCD, Helm. I
  still write code — Python and Go — when the problem calls for it.

  Previously led a Kubernetes practice across Europe. Today I run my own consultancy, [MrContainer](https://github.com/mrcontainer-tech), helping teams build reliable
  platforms.

  I'm also the creator of **[OpenConveyor](https://github.com/openconveyor/openconveyor)** — a Kubernetes-native orchestrator that runs AI coding agents as
  least-privilege, one-shot Jobs. Agent-agnostic, trigger-agnostic, homelab-first.

  ## How I Work

  Keyboard-centric, terminal-first. Neovim, Alacritty, Zsh with Powerlevel10k. Everything is managed with [chezmoi](https://github.com/scholtenmartijn/dotfiles-chezmoi),
   so a new machine is bootstrapped in a single command.

  ## Open Source

  | Repository | What it is |
  |---|---|
  | [openconveyor](https://github.com/openconveyor/openconveyor) | Kubernetes-native orchestrator for AI agents. Least-privilege by default. |
  | [homelab-turing](https://github.com/mrcontainer-tech/homelab-turing) | GitOps-managed Talos cluster: ArgoCD, MetalLB, Longhorn, Knative |
  | [dotfiles-chezmoi](https://github.com/scholtenmartijn/dotfiles-chezmoi) | Neovim + LSP, Zsh, Alacritty — bootstrap a machine in one command |
  | [cv-martijn-scholten](https://github.com/scholtenmartijn/cv-martijn-scholten) | LaTeX CV in Git |

  ## Homelab

  A [Turing Pi v2.5](https://github.com/mrcontainer-tech/homelab-turing) with four Raspberry Pi CM4s and a Dell XPS with an NVIDIA GPU. Fully GitOps — ArgoCD watches the
   repo and reconciles everything from cert-manager to a media server. It's also where OpenConveyor gets dogfooded.

  \```
  ┌─────────────────────────────────────────────────────┐
  │  Turing Pi v2.5                                     │
  │  ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐                    │
  │  │ CM4 │ │ CM4 │ │ CM4 │ │ CM4 │  ← Control Plane   │
  │  │node1│ │node2│ │node3│ │node4│    + Worker        │
  │  └─────┘ └─────┘ └─────┘ └─────┘                    │
  └─────────────────────────────────────────────────────┘
           ↓
  ┌─────────────────┐
  │   Dell XPS      │  ← x86_64 Worker
  │   GTX 1650 Ti   │    GPU workloads
  └─────────────────┘
  \```

  ## Stack

  **Platforms:** Kubernetes · OpenShift · Talos · EKS · AKS
  **Cloud:** AWS · Azure
  **IaC:** Terraform · Helm · ArgoCD · Kustomize
  **Languages:** Python · Go · Bash
  **Editor:** Neovim & VS Code
  **Terminal:** Alacritty · Zsh · Powerlevel10k

  ## Writing

  I write about platform engineering, Kubernetes, and cloud infrastructure at [mrcontainer.nl](https://www.mrcontainer.nl).

  Key changes:
  - Dropped the 👋 and "aficionado" — the title and lede are cleaner.
  - New paragraph in What I Do prominently introduces OpenConveyor with a one-sentence pitch.
  - Added OpenConveyor as the top row of the Open Source table.
  - Tied the homelab back to OpenConveyor ("where it gets dogfooded") — reinforces the homelab-first thesis without a separate section.
  - "Codium" → "VS Code" (Codium is the unbranded fork; if you actually use Codium/VSCodium, revert that).
  - Renamed "Blog" → "Writing", slightly more natural for a professional profile.

  Remove the backslash escapes on the code fences when you paste — they're only there because this response itself is a fenced markdown block.
