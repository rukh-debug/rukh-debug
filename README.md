

```rust
impl Default for AboutMe {
    fn default() -> Self {
        AboutMe {
            name: "Ruben Kharel".to_string(),
            display_contact_info: true,
            current_title: "Security, AI harnesses && homelab tinkerer".to_string(),
            intro: "I break things, build things, and automate the rest. Started in cybersecurity, \
                    now building AI agents and the harnesses around them on models I host myself, \
                    all running on a homelab that's basically a small prod.".to_string(),
            interests: vec![
                "cybersecurity: honeypots, recon, hardening",
                "AI agents && harnesses: langgraph, deepagents, self-hosted LLMs",
                "homelab: proxmox, docker, traefik, tailscale, cloudflare tunnels",
            ],
            now: "Running a public SSH/web honeypot with a live attacker dashboard.".to_string(),
            contact: Contact {
                email: "talkto-at-rubenk-dot-dev".to_string(),
            },
            social: Social {
                website: "https://rubenk.dev".to_string(),
                blog: "https://blog.rubenk.dev".to_string(),
                linkedin: "https://linkedin.com/in/rubenkharel".to_string(),
            },
        }
    }
}
```
