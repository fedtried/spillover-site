@ -0,0 +1,294 @@
# Spillover

**When your mind won't switch off, write it down and go back to sleep.**

---

## Overview

Spillover is a thought-capture app for people who wake up at night with racing thoughts. Instead of lying awake or reaching for distracting apps, Spillover gives you a calm, dark interface to quickly capture what's on your mind — then review it fresh in the morning.

The app blocks distracting apps during your "quiet hours" and replaces them with a simple prompt: *spill it out*. Tap the button, jot down your thought, and go back to sleep knowing it's saved for tomorrow.

---

## The Problem

You're lying awake at 2am. Your brain won't stop:

- *"I need to email that client"*
- *"Did I lock the back door?"*
- *"What if we tried a different approach on that project?"*

You grab your phone to write it down — and 40 minutes later you're deep in email, Slack, or doomscrolling. The thought that woke you is now buried under anxiety from everything else you saw.

---

## The Solution

Spillover intercepts you at the moment you reach for your phone.

1. **Your distracting apps are blocked** during quiet hours
2. **A calm, dark screen appears** with one option: capture your thought
3. **You type it out** in seconds
4. **Go back to sleep** knowing it's saved
5. **Review in the morning** when you can actually do something about it

No bright screens. No feeds. No rabbit holes. Just capture and sleep.

---

## Key Features

### Thought Capture

A minimal, dark interface designed for 2am:

- **Dark theme** that won't blast your eyes
- **Single text field** — no friction, no choices
- **Haptic confirmation** when saved
- **Capture multiple thoughts** without leaving the screen

### Smart Blocking

Uses Apple's Screen Time API to block apps during quiet hours:

- **Choose which apps to block** — social media, email, work apps, games
- **Block entire categories** — all Social Networking, all Entertainment
- **Flexible scheduling** — set different hours for each day of the week
- **Block all day** option for full rest days

### Two Blocking Modes

**Soft mode** — for when you need flexibility:
- "Open for 10 mins" bypass option
- Timer notifies you when bypass expires
- Good for transition periods

**Hard mode** — for when you mean it:
- No bypass option
- Only choice is to capture your thought
- Maximum friction against distraction

### Shield Screen

When you try to open a blocked app, you see:

- **"not now"** — a gentle reminder, not a scolding
- **"spill it out →"** — tap to capture what's on your mind
- Notification arrives to open the app and type your thought

### Morning Review

When quiet hours end, review what you captured:

- **See all your thoughts** from the night before
- **Copy** any thought to clipboard
- **Add to Reminders** with one tap
- **Dismiss** when you're done

### Smart Notifications

Get reminded at the right time:

- **Notification shows preview** of what you captured
- **Only notifies on days you can act** — skips blocked-all-day days
- **Respects your schedule** — won't notify before your day starts
- **Handles night shifts** — works for any schedule pattern

### Widgets

Quick access from Home Screen and Lock Screen:

- **See status** — quiet hours active or thoughts waiting
- **Tap to capture** or **tap to review**
- **Lock Screen widgets** for instant access
- **Updates automatically** when schedule changes

---

## How It Works

### Setup (2 minutes)

1. **Choose apps to block** — pick the ones that pull you in at night
2. **Set your schedule** — when should these apps be available?
3. **Set morning reminder** — when do you want to review your thoughts?
4. **Done** — blocking starts automatically

### During Quiet Hours

- Selected apps show a block screen instead of opening
- Tap "spill it out" to capture a thought
- Dark, calm interface for minimal stimulation
- Thoughts are saved locally on your device

### When Quiet Hours End

- Apps become available again
- Notification reminds you to review captured thoughts
- Process your list: copy, add to reminders, or dismiss
- Start your day with a clear head

---

## Schedule Options

### Per-Day Control

Set different hours for each day:

| Day | Example Schedule |
|-----|------------------|
| Monday - Friday | 8:30am - 6:30pm available |
| Saturday | 10:00am - 4:00pm available |
| Sunday | Blocked all day |

### Overnight Schedules

Works for night shift workers too:

- Set work hours as 10pm - 6am
- Apps available during your shift
- Blocked during your sleep time (daytime)

### Block All Day

Toggle any day to be completely blocked:

- Perfect for digital sabbath
- Rest days with no work apps
- Weekend disconnection

---

## Privacy

**Your thoughts stay on your device.**

- No account required
- No cloud sync
- No analytics on your content
- Thoughts stored locally using Apple's SwiftData
- Delete anytime from the app

---

## Technical Details

### Requirements

- iOS 17.0 or later
- iPhone (optimized for all sizes)
- Screen Time must be enabled

### Permissions

- **Screen Time** — Required to block apps
- **Notifications** — For morning reminders and capture prompts
- **Reminders** — Optional, for adding thoughts to Apple Reminders

### App Group

Uses a shared container to sync data between:
- Main app
- Block screen extensions
- Widgets

---

## Frequently Asked Questions

### Can I still access blocked apps in an emergency?

In **soft mode**, yes — tap "open for 10 mins" for temporary access. In **hard mode**, no — that's the point.

### What if I capture a thought but want to add more?

The capture screen stays open after each save. Keep typing, keep tapping done.

### Does it work if I restart my phone?

Yes. Blocking resumes automatically based on your schedule.

### Can I block Safari or system apps?

Some system apps can't be blocked due to iOS limitations. Most third-party apps and Safari work fine.

### What happens to my thoughts if I delete the app?

They're deleted with the app. Export anything important first using copy or Reminders.

### Does this use a lot of battery?

No. The app uses Apple's native scheduling APIs, which are highly optimized.

---

## Design Philosophy

### Calm, not punishing

The block screen says "not now" — not "you're addicted" or "put down your phone." Spillover treats you like an adult who made a decision and wants help sticking to it.

### Dark by default

The capture interface uses a dark palette designed for 2am. No bright whites, no blue light, no stimulation.

### Minimal by design

One text field. One button. No settings, options, or choices when you're half asleep. Complexity lives in the settings, not the capture flow.

### Honest blocking

When apps are blocked, they're blocked. No "are you sure?" dialogs, no shame-based warnings. Just a clear message and a useful alternative.

---

## Use Cases

### The overworked professional

Block Slack and email after hours. Capture work thoughts that pop up at night without getting sucked into the inbox.

### The anxious mind

Block social media and news. When anxiety wakes you at 3am, write down what's bothering you instead of doomscrolling.

### The creative

Block entertainment apps. When an idea strikes at night, capture it properly instead of losing it to distraction.

### The parent

Block everything after kids' bedtime. If something urgent comes up mentally, capture it — but don't model phone addiction.

### The student

Block games and social during study hours. Capture assignment ideas or exam worries to process during breaks.

---

## Pricing

**Free**

Spillover is free to download and use.

---

## Support

Having issues? Contact us at [support email].

---

## Links

- [Privacy Policy]
- [Terms of Service]
- [App Store]

---

*Spillover — capture the thought, keep the sleep.*