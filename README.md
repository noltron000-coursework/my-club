1. Get an event by ID.
	- `Event.objects.get(id=1)`
1. Get an event by name.
	-	`Event.objects.get(name="Lightning Talks")T`
1. In the above brainstorming activity, you generated a few ideas for how you would filter events. Write the solution to those queries now!
	- `Event.objects.filter(name__contains="s").exclude(name="Lightning Talks")`
