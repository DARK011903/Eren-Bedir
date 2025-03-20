# Eren-Bedir
animals = [
    {
        "name": "Cat",
        "group": "mammals",
        "number_of_legs": 4,
        "skills": ["jumping", "climbing"]
    },
    {
        "name": "Dog",
        "group": "mammals",
        "number_of_legs": 4,
        "skills": ["running", "smelling"]
    },
    {
        "name": "Eagle",
        "group": "birds",
        "number_of_legs": 2,
        "skills": ["flying", "hunting"]
    },
    {
        "name": "Frog",
        "group": "amphibians",
        "number_of_legs": 4,
        "skills": ["jumping", "swimming"]
    },
    {
        "name": "Snake",
        "group": "reptiles",
        "number_of_legs": 0,
        "skills": ["crawling", "hunting"]
    }
]


for animal in animals:
    print(f"{animal['name']} ({animal['group']}): {animal['number_of_legs']} legs - Skills: {', '.join(animal['skills'])}")
