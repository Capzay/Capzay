## Capzay

Ex Lead Developer and Co-Founder at [VR AIM](https://vr-aim.com), a VR aim
trainer with 22,000+ players. It's out on Meta and Steam. I worked on the
backend and the trainer itself, plus most of the calls on architecture and
tooling, and a good chunk of Discord moderation and user support.

Mostly Python, TypeScript and C#. I'm fine in Unity, Next.js, Postgres and the
boring infrastructure bits. I run Arch. I'd rather delete a service than scale
one.

### Stuff I've built

**[VR AIM](https://vr-aim.com)** - VR aim trainer, out on Meta and Steam. I
handled the backend and the in-headset trainer.

**[Cpz-Music](https://github.com/Capzay/Cpz-Music)** - Self-hosted music
streamer for my own library. One Next.js process serves the app, the API and the
audio. Supabase just holds the rows. It runs as a PWA, a desktop app and an
Android app, and any of them can act as a remote for whatever device is actually
playing. You can download albums and play them offline, and the listens get
recorded at the time they really happened. The old version of this was a Fastify
API, a Vite SPA, an nginx container and a separate auth gateway all glued
together with Docker Compose. The rewrite does more without any of it.

**[IVI-EVA-01](https://github.com/Capzay/IVI-EVA-01)** - Discord bot for a VR
esports server. Ping-to-play with cooldowns, reaction roles, XP levelling, and
weekly availability calendars the team captains actually use to sort out scrims.
