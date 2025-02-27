---
title: Wuhan University
published: 2024-05-01
updated: 2024-11-29
description: 'Read more about Markdown features in Fuwari'
image: ''
tags: [Demo, Example, Markdown, Fuwari]
category: 'Examples'
draft: false 
---

##  GitHub Repository Cards
You can add dynamic cards that link to GitHub repositories, on page load, the repository information is pulled from the GitHub API. 

::github{repo="Fabrizz/MMM-OnSpotify"}

Create a GitHub repository card with the code `::github{repo="<owner>/<repo>"}`.

```markdown
::github{repo="saicaca/fuwari"}
```

## Admonitions

Following types of admonitions are supported: `note` `tip` `important` `warning` `caution`

:::note
Highlights information that users should take into account, even when skimming.
:::

:::tip
Optional information to help a user be more successful.
:::

:::important
Crucial information necessary for users to succeed.
:::

:::warning
Critical content demanding immediate user attention due to potential risks.
:::

:::caution
Negative potential consequences of an action.
:::

### Basic Syntax

```markdown
:::note
Highlights information that users should take into account, even when skimming.
:::

:::tip
Optional information to help a user be more successful.
:::
```

### Custom Titles

The title of the admonition can be customized.

:::note[MY CUSTOM TITLE]
This is a note with a custom title.
:::

```markdown
:::note[MY CUSTOM TITLE]
This is a note with a custom title.
:::
```
# This Article is a Draft

# **2025 Wuhan Cherry Blossom Season - Ultimate 3-Day Itinerary**

Spring is coming, and that means it's time for **Wuhan's cherry blossom season**! The best time to see cherry blossoms in Wuhan is from **mid to late March**. To help you make the most of your trip, here's a **detailed 3-day itinerary** that combines cherry blossom viewing with top tourist attractions. Plus, we’ve included a food guide for an unforgettable culinary experience!

> **Note:** This itinerary is packed, requiring early mornings. Feel free to adjust based on your interests to avoid exhaustion.

---

## **🌸 Popular Cherry Blossom Viewing Spots in Wuhan**

### 📍 Wuhan University 🌸🌸🌸🌸🌸
- **🎫 Admission:** Free (Reservation required **3 days in advance**)
- **⏱ Opening Hours:** Weekdays **8:30 AM - 5:30 PM**, Weekends **8:00 AM - 6:00 PM**
- **🚥 Transportation:** Metro **Line 2** or **Line 8**, get off at **Jiedaokou Station**

### 📍 East Lake Cherry Blossom Park 🌸🌸🌸🌸🌸
- **🎫 Admission:** ~$8 (¥60) (Reservation required **3 days in advance**)
- **⏱ Opening Hours:** **8:00 AM - 9:00 PM** (*Night cherry blossom area opens after 6:00 PM*)
- **🚥 Transportation:**
  - Take **Metro Line 8** to **Liyuan Station** (Hubei Provincial Museum is nearby)
  - **Ferry Option:** Navigate to **Chufengyuan Pier**, take a ferry to **Meiyuan Pier** (*Round-trip ferry + Cherry Blossom Park ticket: ~$13 (¥99)*)

### 📍 Hankou River Beach Park 🌸🌸🌸🌸
- **🎫 Admission:** Free
- **⏱ Opening Hours:** Open all day
- **🚥 Transportation:** Metro **Line 2** to **Jianghan Road Station**, then walk **15 minutes**

### 📍 Northwest Lake Square 🌸🌸🌸🌸
- **🎫 Admission:** Free
- **⏱ Opening Hours:** Open all day
- **🚥 Transportation:** Metro **Line 2** to **Wangjiadun East Station**, then walk **12 minutes**

### 📍 Wangjiadun Park 🌸🌸🌸🌸
- **🎫 Admission:** Free
- **⏱ Opening Hours:** Open all day
- **🚥 Transportation:** Metro **Line 3** or **Line 7**, get off at **Wuhan Business District Station**

### 📍 Qingshan Park 🌸🌸🌸🌸
- **🎫 Admission:** Free
- **⏱ Opening Hours:** Open all day
- **🚥 Transportation:** Metro **Line 5** to **Honggangcheng Station**

### 📍 Guishan Park 🌸🌸🌸🌸
- **🎫 Admission:** Free
- **⏱ Opening Hours:** Open all day
- **🚥 Transportation:** Metro **Line 4** to **Zhongjiacun Station**, then walk **11 minutes**

---

## **🌟 Top Instagram-Worthy Cherry Blossom Spots**
1. **Luoyu Road - Dahuang Village Bus Stop** *(Nicknamed "Most Beautiful Cherry Blossom Bus Stop")*
2. **Lumo Road - Yangguang Community Cherry Blossoms** *(Perfect for aesthetic photography)*
3. **Metro Line 7 - Xinlucun Station** *(Cherry blossom pedestrian bridge, a dreamlike backdrop)*

### GitHub Syntax

> [!TIP]
> [The GitHub syntax](https://github.com/orgs/community/discussions/16925) is also supported.

```
> [!NOTE]
> The GitHub syntax is also supported.

> [!TIP]
> The GitHub syntax is also supported.
```