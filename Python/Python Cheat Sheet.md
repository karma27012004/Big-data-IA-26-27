
## Data_types 

	int("42") - # 42
	float("3.14") - # 3.14
	str(42) - # "42"
	bool(1) - # True
	list("abc") - # ["a", "b", "c"]

## Variables

	name = "Leo" - # String
	age = 7 - # Integer
	height = 1.70 - # Float
	is_cat = true - # Bolean
	flaws = None - # None type

## Assignments

	x, y = 10, 20 - # Assign multiple values
	a = b = c = 0 - # Same value to multiple variables

## Augmented_Assignments

	counter += 1
	numbers += [4, 5]
	permissions |= write

## Strings

	single = 'Hello'
	double = "Hi"
	multi = """ Multiple line string"""

## String_Operations

	greeting = "I " + "am Steve" - # "I am Steve"
	repeat = "Hi! " *3 - # "Hi! Hi! Hi!"
	length = len("Python") - # 6

## String_Methods

	"a".upper() - # "A"
	"A".lower() - # "a"
	" a ".strip() - # "a"
	"abc".replace("bc", "ha") - # "aha"
	"a b".split() - # ["a", "b"]
	"-".join(["a", "b"]) - # "a-b"

## String_Indexing

	text = "Python"
	text[0] - # "P"
	text[-1] - # "n"
	text[1:4] - # "yth"
	text[:3] - # "Pyth"
	text[3:] - # "hon"
	text[::2] - # "Pto"
	text[::-1] - # "nohtyP"

## String_Formatting

	name = "Felix"
	age = 20
	f"Hello, {name}!" - # "Hello, Felix!"
	f"{name} is {age} years old" - # "Felix is 20 years old"
	f"Debug: {age=}" - # "Debug: age=20"
	
	# Format Method
	template = "Hello, {name}! You're {age}."
	template.format(name="Felix", age=20) - # "Hello Felix! You're 20."

## Raw_Strings

	# Normal string with an escaped tab
	"This is:\tCool." - # "This is:    Cool"
	# Raw string
	r"This is:\tCool." - # "This is:\tCool"
