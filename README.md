# Reboot01 Tester

A simple app to practice the **bh-piscine checkpoint (1–3)** Go exercises — right in your browser. Write Go, run **real tests** (your code is actually compiled and run, then checked against the expected output), and walk into the exam ready.

> Built by **Mohammed Zuhair**.

> ⚠️ For practice and learning only. The grading is similar to the real checkpoint, but not exactly the same. Use it to prepare and build confidence — not as an official result.

---

## What you get

- **Ready-to-go exercises** — every checkpoint exercise, organized by group.
- **Real testing** — your code is compiled and run, then compared to the expected output.
- **Clear requirements** — instructions, expected function, allowed functions, and sample output for each one.
- **Practice freely** — no pressure, no limits. Solve, fail, retry, learn.
- **Fully offline** — once it's built, no internet needed.

---

## What you need

Just **one** thing:

- **[Docker Desktop](https://www.docker.com/products/docker-desktop/)** — install it and open it once so it's running.

That's it. Nothing else to install.

---

## How to run (first time)

**1.** Open **Docker Desktop** and wait until it's running.

**2.** Open your terminal:
   - **macOS:** open the **Terminal** app
   - **Windows:** open **PowerShell**

**3.** Paste this command and press Enter:

```
docker run -d --name reboot01 -p 8080:8080 ghcr.io/reoobh/reboot01tester:latest
```

**4.** Open your browser and go to:

**http://localhost:8080**

> The first time, Docker downloads the app (a minute or two). After that, it's instant.

---

## Stop and start (after the first time)

**Stop it:**
```
docker stop reboot01
```

**Start it again:**
```
docker start reboot01
```

Your progress is saved automatically.

---

## Update to the latest version

This app gets updated from time to time with new features and fixes. Whenever you want the newest version, just run these commands one by one:

```
docker pull ghcr.io/reoobh/reboot01tester:latest
docker stop reboot01
docker rm reboot01
docker run -d --name reboot01 -p 8080:8080 ghcr.io/reoobh/reboot01tester:latest
```

That's it! You'll always have the latest version. Don't worry — your progress is saved and won't be lost. 👍

---

## Need help?

Something not working? No problem!

Feel free to contact me anytime — I'm happy to help you run it. 🙌

You can open an **[issue](../../issues)** here, or just message me directly.


---

## One last thing 🌟

Don't be afraid to make mistakes here — that's how you learn.
Every problem you solve makes you stronger.
A little practice every day, and you will be ready.

**Believe in yourself. You can do this! 💪**

**Good luck — you've got this! 🍀**

---

With best wishes,
**Mohammed Zuhair**
