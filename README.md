# Routine Tracker Keypad

A 9-key control pad for logging a morning routine. Designed for tactile task initiation, habit reinforcement, and marking the task done somewhere (Obsidian, a spreadsheet, Telegram, TBD).


---

## The Routine

Keys map to three phases of a morning:

**init**
- audio in
- Rx
- hello world

**main**
- weigh in
- brush teeth
- wash + SPF

**deploy**
- dress + glam
- break fast
- review cal

---

## What It Does

Each key is a momentary switch. Press it → it latches (via SN74HC74 flip-flop) → LED lights up → log entry fires somewhere. The "somewhere" is still TBD: candidates are an Obsidian daily note, a Google Sheet, or a Telegram message. Probably whichever is easiest to automate.

---

## Hardware

- Switches: 9x Durock Sea Glass MX
- Logic: SN74HC74 dual D-type flip-flops for edge-triggered toggling
- PCB: Custom, fab via JLCPCB
- Power: TBD
- LEDs: TBD

---

## Electrical Design

TBD
