# Hey, I'm Martijn 👋

Platform Engineer & Cloud aficionado who still writes code. I spent years as a full stack developer before moving into infrastructure—which means I build platforms with the developer experience in mind.

## What I Do

I design and build Kubernetes platforms, cloud infrastructure, and the automation that keeps it all running. Currently focused on AWS, Kubernetes, OpenShift, and the tooling around them (Terraform, ArgoCD, Helm). I still code in Python and Go when the problem calls for it.

Previously led a Kubernetes practice across Europe. Now I run my own consultancy, [MrContainer](https://github.com/mrcontainer-tech), helping teams build reliable platforms their developers actually want to use.

## How I Work

Keyboard-centric, terminal-first. My workflow lives in Neovim, Alacritty as my terminal, Zsh with Powerlevel10k.

Everything is managed with [chezmoi](https://github.com/scholtenmartijn/dotfiles-chezmoi), so I can bootstrap a new machine in one command.

## My Homelab

My homelab runs on a [Turing Pi v2.5](https://github.com/mrcontainer-tech/homelab-turing) cluster with four Raspberry Pi CM4s and a Dell XPS with an NVIDIA GPU. It's fully GitOps—ArgoCD watches the repo and deploys everything from cert-manager to a media server.

```
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
```

## Open Source

| Repository                                                                    | What it is                                                               |
| ----------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| [homelab-turing](https://github.com/mrcontainer-tech/homelab-turing)          | GitOps-managed K3s cluster: ArgoCD, MetalLB, Longhorn, Knative           |
| [dotfiles-chezmoi](https://github.com/scholtenmartijn/dotfiles-chezmoi)       | Neovim + LSP, Zsh, Alacritty, chezmoi—bootstrap a machine in one command |
| [cv-martijn-scholten](https://github.com/scholtenmartijn/cv-martijn-scholten) | LaTeX CV in Git, because version control makes sense for everything      |

## Stack

**Platforms:** Kubernetes · OpenShift · K3s · EKS · AKS  
**Cloud:** AWS · Azure  
**IaC:** Terraform · Helm · ArgoCD · Kustomize  
**Languages:** Python · Go · Bash  
**Editor:** Neovim & Codium  
**Terminal:** Alacritty · Zsh · Powerlevel10k

---
