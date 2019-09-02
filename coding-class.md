# Intro to Programming for Journalists

- Solitaire example
- python anywhere setup
- python anywhere wakeup example
	
	```
	alarm_hrs = 7
	alarm_min = 22
	weekday = "Tues"
	busy_day = True
	rain = True
	shower_night_before = False
	guest_1 = {"name": "Brian", "relationship": "friend"}
	guest_2 = {"name": "Morgan", "relationship": "cousin"}
	guests = [guest_1, guest_2]
	todo = []
	```
	```
	if alarm_hrs < 8 and busy_day == False:
	    todo.append("hit snooze")
	    todo.append("get up")
	else:
	    todo.append("get up")
	if weekday in ["Tues", "Thurs"]:
	    todo.append("say hi to Nikki")
	if len(guests) > 0:
	    for guest in guests:
	        todo.append("say hi to " + guest["relationship"] + " " + guest['name'])
	if shower_night_before == False:
	    todo.append("shower")
	for task in ["brush teeth", "wash face", "make lunch"]:
	    todo.append(task)
	if rain == False:
	    todo.append("check bike tires")
	    todo.append("ride bike to work")
	else:
	    todo.append("walk to subway")
	    todo.append("take subway to work")
	print(todo)
	```


- make your own wakeup schedule
- What can journalists do with [code](https://github.com/nprapps/heat-income/blob/master/analyze_geojson_output.py)
- [what the hell is an API](https://prezi.com/hsbuuq7r3z1n/what-the-hell-is-r/)