# LabReserva — Mid-fidelity prototype

**Author:** João Henrique Porfirio Firmiano, with assistance from Claude (Anthropic).

Clickable grayscale prototype of a **lab booking and equipment loan** system for a college (fictional case: Faculdade Horizonte). Academic project for the Human-Computer Interaction (HCI) course of the Software Engineering program at UniRV.

**▶ [Open the prototype in Penpot](https://design.penpot.app/?screen=viewer&file-id=c6f51e89-5d00-81ce-8008-e4eafc136fb0&page-id=c6f51e89-5d00-81ce-8008-e4eafc136fb1&section=interactions&index=0&zoom=fit&share-id=28115847-11dc-4234-872a-bf97b0e21492)**. In view mode, pick the flow in the top menu (T1, T2 or T3) and navigate by clicking the buttons.

## The problem

Today, bookings are made through a spreadsheet and WhatsApp messages to the lab technician. This leads to scheduling conflicts discovered right at class time, no information about installed software or working machines, free time slots that students can't see, unrecorded loans and an overloaded technician.

## Prototyped tasks

| Task | User | Device | The flow covers |
|---|---|---|---|
| T1 | Professor | Mobile (360 × 800) | Log in, search for a lab by date, time and software, check availability, create a weekly recurring booking and get a confirmation |
| T2 | Student | Mobile (360 × 800) | Log in, find a free slot, book for a group, request equipment and cancel in "My bookings" |
| T3 | Technician | Desktop (1280 × 720) | View pending requests, resolve a conflict (approve one and decline another with a reason) and record an equipment return |

There are 23 screens, including empty, error and confirmation states.

## Main screens

| T1 · Availability | T1 · Recurring booking | T2 · Error (2 h limit) | T2 · Empty state |
|---|---|---|---|
| ![P04](telas/P04-disponibilidade.png) | ![P05](telas/P05-reserva-recorrente.png) | ![A05](telas/A05-erro-limite-de-2-horas.png) | ![A11](telas/A11-minhas-reservas-vazio.png) |

**T3 · Resolve conflict (technician)**

![D02](telas/D02-resolver-conflito.png)

All screens are in the [`telas/`](telas/) folder.

## Screen map

![Screen map](docs/mapa-de-telas.png)

Solid arrow: task path. Dashed arrow: go back or cancel. Dotted arrow: fixed menu.

## Documentation

The [full report (PDF, in Portuguese)](docs/relatorio.pdf) covers the user profile, the personas (and the anti-persona), the usage scenario, the hierarchical task analysis (HTA), the usability goals (ISO 9241-11), the design decisions and the prototype's limitations.

## Tool

[Penpot](https://penpot.app): free, open source and browser-based.
