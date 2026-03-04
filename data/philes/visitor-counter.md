# fun quirk of the visitor counter

i use Git Pages to host and showcase this website, as can be seen by the domain. a result of this is that i have decided to use as little external APIs as possible, with the exception of one — the visitor counter.

---

it's a very simple thing, it calls to `counterapi` and just increases every time a hit occurs.

if you are a privacy oriented user, you may have noticed the counter not going up when you refresh the site — this is because any tracker blockers you may have on a browser like **Firefox** or **Brave** block the counter API.

i do not mind it myself, but its fun to see how such a simple thing like a counter is something that is picked up as a *"tracker"* by modern security standards.

> that was my observation for the day, hope you enjoyed learning it as much as i did.
