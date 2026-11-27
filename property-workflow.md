# Booking a shared reading room

This fictional portfolio exercise uses two invented booking requests. The goal is to decide what to tell each person when their requests overlap.

## Example

One reader asks for the room from 2 to 3 p.m. Another asks for it from 2:30 to 3:30 p.m. In this exercise, the first confirmed booking holds the room for its full hour. If the first request is confirmed, the second reader sees the conflict and can choose a later start time.

## How I would check the design

- Submit both requests together. At most one overlapping booking should be confirmed.
- Move the second request to 3 p.m. Both bookings should fit because the first ends when the second begins.
- Cancel the first booking. The time should become available again, and a reader who previously saw a conflict should still choose whether to book it.
