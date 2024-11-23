

```rust
impl Default for AboutMe {
    fn default() -> Self {
        AboutMe {
            name: "Ruben Kharel".to_string(),
            display_contact_info: true,
            current_title: "Fullstack Dev && DevOps".to_string(),
            intro: "I am a developer and devops guy actively developing webs and also a learner, passively learning various nerdy stuff.".to_string(),
            contact: Contact {
                email: "talkto-at-rubenk-dot-dev".to_string(),
            },
            social: Social {
                website: "http://rubenk.dev".to_string(),
                linkedin: "https://linkedin.com/in/rubenkharel".to_string(),
            },
        }
    }
}
```
