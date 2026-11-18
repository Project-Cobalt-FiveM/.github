<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="cobalt-lockup-dark.svg" />
  <img width="360" alt="Project Cobalt" src="cobalt-lockup.svg" />
</picture>

<p>
  <strong>A FiveM roleplay framework, built properly.</strong>
</p>

<p>
  <a href="https://projectcobalt.net">
    <img src="https://img.shields.io/badge/Website-projectcobalt.net-5078D7?style=for-the-badge" alt="Website" />
  </a>
  <a href="https://github.com/Project-Cobalt-FiveM">
    <img src="https://img.shields.io/badge/GitHub-Project--Cobalt--FiveM-0A0A0A?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://docs.projectcobalt.net">
    <img src="https://img.shields.io/badge/Docs-docs.projectcobalt.net-27272A?style=for-the-badge" alt="Documentation" />
  </a>
  <a href="https://discord.gg/wFneTufDq9">
    <img src="https://img.shields.io/badge/Discord-Project%20Cobalt-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>
</p>

</div>

---

## About

Project Cobalt is a roleplay framework for FiveM: a core for players, characters, money and permissions, with the jobs, inventory, housing, vehicles and UI a server needs built on top of it. It runs on MariaDB and ox_lib, and every resource documents its exports.

Cobalt is open source. Every framework resource is public here, free to run, change and build on.

Cobalt is built and maintained by one developer, [zlexif](https://github.com/zlexif).

## Get started

The [txAdmin recipe](https://github.com/Project-Cobalt-FiveM/txAdminRecipe) sets up a full server: every resource, the database and a ready `server.cfg`. In txAdmin's setup, pick **Remote URL Template** and paste:

```
https://raw.githubusercontent.com/Project-Cobalt-FiveM/txAdminRecipe/main/recipe.yaml
```

Tables are created on the first start, so there's nothing to import. QBCore, ox_inventory and oxmysql scripts run on Cobalt's bridges.

## What's in it

| Area | Resources |
| --- | --- |
| Core | Players, characters, money, permissions and the shared API, on a worker-thread MariaDB layer |
| Inventory | Grid inventory with drop-in ox_inventory support |
| Jobs | Police, EMS, mechanics, City Hall, jobs and gangs with society funds |
| World | Housing, garages, dealership, vehicle keys, weather and time, audio |
| Interface | Notifications, menus, dialogs, HUD, chat, loading screen and character selection |

## License

Cobalt's resources are under the Project Cobalt License: free to run on any server, paid servers included. Changes stay public under the same license. The code can't be sold, and it keeps the Project Cobalt name and `cobalt_` prefix. Third-party resources keep their own licenses.

## Help and contributing

Exports and guides for every resource are at [docs.projectcobalt.net](https://docs.projectcobalt.net). Report bugs as issues on the resource's repo, and send fixes as pull requests. Questions go in the [Discord](https://discord.gg/wFneTufDq9).
