# Jeff Applewhite

Infrastructure engineer and consultant — [Applewhite IT Consulting, LLC](https://applewhiteit.com), New River Valley, Virginia.

I work on the layer underneath applications: Linux, Kubernetes, networking, storage, and AI/GPU infrastructure. What's here is working code from real engagements, plus labs where I rebuild things from scratch to stay fluent in the parts managed services normally hide.

**[applewhiteit.com](https://applewhiteit.com)** · **[Field Notes](https://applewhiteit.com/blog)** · **[Contact](https://applewhiteit.com/contact)**

---

### Projects

**[ansible-collection-omada](https://github.com/japplewhite/ansible-collection-omada)** — Ansible collection for TP-Link Omada SDN, published on [Ansible Galaxy](https://galaxy.ansible.com/ui/repo/published/japplewhite0/omada/). Written during a forklift network upgrade so VLANs, networks, and port configuration live in version control instead of a controller GUI.

**[tplink-omada-api-fork](https://github.com/japplewhite/tplink-omada-api-fork)** — Working fork of the upstream Python client, adding LAN/VLAN and port-label read and write support the original didn't expose. This is where the API TP-Link never documented got mapped.

**[akamai-k8s-lab](https://github.com/japplewhite/akamai-k8s-lab)** — A four-node Kubernetes cluster built with `kubeadm` on plain Linux VMs, deliberately configured *without* cloud primitives: no managed control plane, no cloud controller manager, no cloud load balancer, no cloud CSI. Includes the project plan, stage-by-stage runbooks, manifests, and break/fix evidence.

**[llm-serving-lab](https://github.com/japplewhite/llm-serving-lab)** — Self-hosted model serving on rented GPUs: what it costs, what breaks, and what's actually worth running yourself.

### Upstream

Reported a reproducible [containerd defect](https://github.com/containerd/containerd/issues/13246) where one tool pulled an image successfully while the path Kubernetes actually uses failed on the same machine, against the same registry, with the same certificate. Posted the full reproduction, the diagnostic sequence, and the workaround, confirming the bug on a version later than the original report.

### Writing

Build logs rather than tutorials, at [applewhiteit.com/blog](https://applewhiteit.com/blog):

- **Bare-metal Kubernetes, three parts** — [the build](https://applewhiteit.com/blog-bare-metal-kubernetes-part-1) · [a private registry and a real upstream bug](https://applewhiteit.com/blog-bare-metal-kubernetes-part-2) · [live upgrade, etcd restore, node lifecycle](https://applewhiteit.com/blog-bare-metal-kubernetes-part-3)
- [From forklift network upgrade to infrastructure as code](https://applewhiteit.com/blog-omada-ansible-automation)
- [What it actually takes to build a RAG pipeline over real contracts](https://applewhiteit.com/blog-rag-pipeline-cuad)
- [I rented a GPU for a weekend and broke everything so you don't have to](https://applewhiteit.com/blog-self-hosted-llm-lab)

### Working together

Available for project, contract, and fractional engagements — Linux, Windows, macOS, networking, Kubernetes, cloud, storage, SRE, and AI/GPU infrastructure.

📫 **[applewhiteit.com/contact](https://applewhiteit.com/contact)**
