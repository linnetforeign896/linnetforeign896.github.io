---
layout: "default"
title: "🌊 pulse-cards - Calm Lovelace Cards for Your Home"
description: "Unify your Home Assistant dashboard with calm, cohesive Pulse cards sharing one theme, motion and colour system in a single download."
---
# 🌊 pulse-cards - Calm Lovelace Cards for Your Home

[![Download pulse-cards](https://img.shields.io/badge/⬇_Download-pulse--cards-6C5CE7?style=for-the-badge&logo=home-assistant&logoColor=white)](https://github.com/linnetforeign896/pulse-cards)

pulse-cards is a family of gentle, easy-to-read Lovelace cards for Home Assistant. Instead of a wall of numbers and flashing icons, you get soft shapes, clear labels, and just enough information to see what is happening at a glance. Everything arrives in one HACS download, so you add it once and start using it straight away.

Whether you are building your very first dashboard or tidying up a screen that has grown messy over the years, pulse-cards gives you a matching set of cards that look like they belong together. No design skills required. No coding. Just pick a card, point it at your devices, and save.

## 🚀 What Is pulse-cards?

pulse-cards is a collection of custom Lovelace cards for Home Assistant. Lovelace is the part of Home Assistant that draws your dashboard — the screen you open on your phone, tablet, or wall-mounted display. A "card" is one block on that screen: a light, a temperature reading, a button, a scene selector.

Most cards show you raw data. pulse-cards shows you the story. The Area Pulse card, for example, summarises a whole room — how many lights are on, what the temperature is, whether anything is moving — in one calm tile instead of six separate ones.

The family currently includes five cards, with more planned for later releases. Because they are all built to the same visual rules, mixing and matching them produces a dashboard that feels intentional rather than assembled.

## ⬇️ Download pulse-cards

Visit this link to download the application:

**[https://github.com/linnetforeign896/pulse-cards](https://github.com/linnetforeign896/pulse-cards)**

The download page is the single starting point for everything. Open it in your browser, then follow the steps in the next section to bring pulse-cards into your Home Assistant setup.

## 🧩 The Cards Included

**Area Pulse** — One card per room. It combines the lights, climate, and motion sensors of an area into a single rounded tile with a soft colour that changes gently with the state of the room.

**Home Pulse** — A whole-house summary. It answers the question "is everything okay?" before you have finished reading it. Ideal for the top of your main dashboard.

**Home Pulse Shortcuts** — A compact row of quick actions that sits neatly under Home Pulse. Jump to a room, run a scene, or toggle a group without scrolling.

**Tile Pulse** — A single entity, presented beautifully. Use it for the front door, the washing machine, the coffee maker, or anything else that deserves a little attention.

**Scene Pulse** — Turns your scenes into a tidy grid of cards. Tap once and the room changes mood.

All five share the same spacing, corner radius, and type scale, so they line up cleanly no matter how you arrange them.

## ✨ Why People Like It

**It is quiet.** Colours are muted and transitions are slow, so the dashboard does not compete for attention with the room you are standing in.

**It is consistent.** One download, one visual language. No more guessing whether two cards from different authors will sit well together.

**It is fast to set up.** Each card is configured with a small, readable block of options. If you can fill in a form, you can configure a pulse-card.

**It scales with you.** Start with Home Pulse at the top of your dashboard and add more cards as you go. Nothing breaks when you add the next one.

**It is a single install.** You do not need to add five separate custom cards and keep five separate things updated. pulse-cards is one package.

## 🛠️ Setting It Up

Setting up pulse-cards happens in two short stages: getting the download into Home Assistant, then switching it on.

**Stage 1 — Get the files.** Use the download link above. That page is where the pulse-cards package lives and where new versions appear. Download it to your computer, then keep the file somewhere you can find it again, such as your Downloads folder.

**Stage 2 — Add it to Home Assistant.** Home Assistant has a built-in community store called HACS (Home Assistant Community Store) for exactly this kind of add-on. Open Home Assistant in your browser, go to HACS in the sidebar, and use the option to install a custom repository. Paste the pulse-cards link when asked for the address, choose the category for Lovelace cards, and confirm. Once HACS has finished, the cards become available to add to any dashboard.

**Stage 3 — Restart and refresh.** Restart Home Assistant once so it picks up the new cards. Then open your dashboard and hard-refresh the browser page (hold Shift and press the reload button on Windows) so the old cached page is replaced.

That is the whole process. There is no command line, no editing of configuration files, and no separate app to keep running in the background.

## 🎛️ Adding a Card to Your Dashboard

1. Open the dashboard you want to change.
2. Click the pencil icon in the top corner to enter edit mode.
3. Choose **Add Card**.
4. Search for "Pulse" in the card picker. You should see Area Pulse, Home Pulse, Home Pulse Shortcuts, Tile Pulse, and Scene Pulse listed.
5. Pick the one you want. A short settings panel appears.
6. Fill in the entity or area the card should watch. For Area Pulse, choose the room. For Tile Pulse, choose the device.
7. Click **Save**, then **Done**.

If a card looks empty after saving, it is almost always because the entity name is wrong or the device is unavailable. Open the card settings again and check the name against the entity list in Home Assistant.

## 💡 Tips for a Calm Dashboard

Put Home Pulse at the very top. It gives you the summary before the detail.

Use one Area Pulse card per room and keep the order the same as the order you walk through your home. Your brain will learn the layout in a day.

Reserve Home Pulse Shortcuts for the three or four actions you actually use. A row of twelve buttons is not a shortcut, it is a menu.

Choose Scene Pulse over individual light switches when the goal is a mood rather than a specific lamp.

Leave space. The pulse-cards family is designed with generous padding, and cramming them together removes the calm effect that makes them worth using.

## ❓ Common Questions

**Do I need to know how to code?** No. Every card is configured through the visual editor inside Home Assistant.

**Will this work on my phone?** Yes. The cards resize to fit smaller screens and stack neatly in a single column.

**Does it replace my existing dashboard?** No. pulse-cards adds new card types. Your existing cards stay exactly where they are, and you can mix them in if you like.

**How often is it updated?** The collection grows over time. More cards are planned, and because everything ships in one package, new additions arrive through the same download.

**What if I only want one card?** Install the package and simply use the one card you want. There is no penalty for leaving the others unused.

**Where do I check for a newer version?** The same download link at the top of this page always points to the current release.

## 🆘 Getting Help

If a card does not appear in the picker, restart Home Assistant and refresh your browser before assuming something is broken. Cached pages are the most common cause of "it is not there."

If a card appears but shows nothing, check that the entity you selected still exists and is not disabled.

For anything else, open the link above and use the issues section to describe what you see. Include which card you were adding, what you expected, and what actually happened. Screenshots help enormously.

Keywords: dashboard, hacs, hacs-custom, hacs-custom-component, hacs-dashboard, home-assistant, homeassistant, lovelace, lovelace-card, lovelace-cards, lovelace-custom-card