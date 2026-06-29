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
- **Your progress is saved** — even after closing or updating, your solutions and notes stay.

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
docker run -d --pull always -v reboot01-data:/data --name reboot01 -p 8080:8080 ghcr.io/reoobh/reboot01tester:latest
```

**4.** Open your browser and go to:

**http://localhost:8080**

> The first time, Docker downloads the app (a minute or two). You need internet to start it.

---

## Stop and open it again

**Stop it:**

```
docker stop reboot01
```

**Open it again (use this each time you want to start it):**

```
docker rm -f reboot01 ; docker run -d --pull always -v reboot01-data:/data --name reboot01 -p 8080:8080 ghcr.io/reoobh/reboot01tester:latest
```

> 💡 **You don't need to copy this command every time!** It's already saved in your terminal. Just press the **Up Arrow (↑)** key to bring it back, then press Enter to run it.

Don't worry — your progress and notes are saved automatically and won't be lost. 👍


---

## Always the newest version

You don't need to update anything yourself. Every time you open the app, it gets the newest version automatically. You are always up to date. ✅

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
