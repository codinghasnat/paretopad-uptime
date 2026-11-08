# ParetoPad uptime

Checks paretopad.com, Supabase auth, a public database read, edge functions and the
chat server every 30 minutes. A failing run emails the repository owner.

Only public URLs and the publishable (anon) key that already ships in the app are used.
Manual drill: Actions → Uptime → Run workflow → tick `simulate_outage`.
