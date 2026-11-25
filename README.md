<img src="assets/banner.svg" alt="Aeon Roamer — Rust backend and systems engineer" width="100%" />

<h1>
  Hi, I'm Aeon Roamer!
  <img src="https://skillicons.dev/icons?i=rust" height="36" alt="Rust" />
</h1>

<p>
  <em>Rust backend &amp; systems engineer from Pakistan</em>
  <img src="https://rustacean.net/assets/rustacean-flat-happy.svg" height="22" alt="Ferris" />
</p>

<p>
  <em>I design backends and scalable systems: fast, reliable, and built to grow.</em>
</p>

<p>
  💼 <strong>Open to remote Rust / backend roles</strong>, full-time or contract
</p>

<hr />

<h3>
  <img src="https://rustacean.net/assets/rustacean-flat-gesture.svg" height="28" alt="Ferris" />
  A little more about me...
</h3>

```rust
let aeon = Engineer {
    name: "Aeon Roamer",
    from: "Pakistan 🇵🇰",
    speaks: vec!["Urdu", "English", "Rust"],
    role: "backend & systems",
    loves: vec!["system design", "APIs", "databases", "performance", "scaling"],
    stack: Stack {
        lang: vec!["Rust"],
        backend: vec!["Axum", "Tokio", "AWS Lambda"],
        data: vec!["SurrealDB"],
        also: vec!["GPUI", "Leptos"],
    },
    now: "a shared auth service in Axum for multiple apps",
    looking_for: "a remote Rust backend team to grow with",
    motto: "if it compiles, it ships 🦀",
};
```

<hr />

<h3>
  <img src="https://skillicons.dev/icons?i=rust" height="26" alt="Rust" />
  Projects
</h3>

#### 🧾 Scan & Fill

```rust
let scan_fill = Project {
    name: "Scan & Fill",
    what: "scan a bill's barcode, and it gets typed into payment software for you",
    platform: "Windows desktop",
    tech: vec!["Rust", "GPUI", "SurrealDB (SurrealKV)", "Tokio", "Win32 API", "WiX"],
    architecture: Workspace {
        client: "GPUI app: screens, pages, state, local database",
        shared: "bill formats and barcode parsing, UI-free",
        win_ops: "Win32 layer: keyboard hooks, focus tracking, typing",
    },
    features: vec![
        "live scanning with a global trigger key",
        "bulk mode: scan many bills, type them all in one run",
        "detects which app is focused before typing",
        "data-driven bill formats and software profiles",
        "single instance, crash hook, MSI installer",
    ],
    challenges: vec![
        "typing into other apps reliably with SendInput",
        "global keyboard hooks without blocking the UI thread",
        "keeping the UI responsive while a run is typing",
    ],
};
```
