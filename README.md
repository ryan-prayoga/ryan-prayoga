# ryanprayoga

```go
// whoami.go
package main

import "fmt"

type dev struct {
    handle   string
    location string
    stack    []string
    focus    []string
    now      string
}

func main() {
    r := dev{
        handle:   "ryan-prayoga",
        location: "Indonesia",
        stack:    []string{"Go", "SvelteKit", "Swift", "TypeScript", "Postgres"},
        focus:    []string{"backend systems", "civic tech", "security tooling"},
        now:      "shipping openrowdb, jedug, messhub",
    }
    fmt.Printf("%+v\n", r)
}
```

Backend-leaning generalist. Building civic tech, dev tooling, and the occasional native macOS app.
Informatics @ BINUS Online Learning · TA on K-Means clustering over Indonesian government procurement data.

---

### stack

| domain   | tools                                                      |
| -------- | ---------------------------------------------------------- |
| backend  | Go (Fiber, pgx), Postgres, Redis, REST & SSE               |
| frontend | SvelteKit, Svelte 5 runes, TypeScript                      |
| native   | SwiftUI, SwiftData, Liquid Glass                           |
| tooling  | shell, Python, Node, Docker, Caddy, Playwright             |
| infra    | Linux/ARM, Cloudflare, Tailscale, SSH tunnels, self-hosted |

### featured

| repo                                                           | what it is                                                |
| -------------------------------------------------------------- | --------------------------------------------------------- |
| [openrowdb](https://github.com/ryan-prayoga/openrowdb)         | native macOS database client (SwiftUI + Liquid Glass)     |
| [jedug](https://github.com/ryan-prayoga/jedug_v2)              | participatory road-damage reporting for Indonesian cities |
| [korbanmbg](https://github.com/ryan-prayoga/korbanmbg)         | MBG program incident tracker (Go + SvelteKit + PostGIS)   |
| [brunogen](https://github.com/ryan-prayoga/brunogen)           | generates Bruno API collections from source code          |
| [messhub](https://github.com/ryan-prayoga/messhub)             | real-time messaging platform (Go + SvelteKit)             |
| [gas-cli](https://github.com/ryan-prayoga/gas-cli)             | Go backend workflow tool — compile / .env / run          |

### now

- shipping `openrowdb` (Postgres first, MySQL next)
- TA: K-Means clustering with spatial features (LKPP procurement)
- civic-tech weekends: jedug, korbanmbg
- security research on stealth tunneling & AI agent supply chains

### achievements

`PRO` · `Pull Shark` · `Pair Extraordinaire` · `YOLO`

### contact

- 𝕏 [@txtdrprogrammer](https://x.com/txtdrprogrammer)
- 🌐 [ryanprayoga.dev](https://ryanprayoga.dev)
- 📬 GitHub issue
