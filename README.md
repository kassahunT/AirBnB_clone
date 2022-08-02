#  AirBnB_clone
# Description

This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

- put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
- create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
- create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
- create the first abstracted storage engine of the project: File storage.
- create all unittests to validate all our classes and storage engine
# What’s a command interpreter?
Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc…
- Do operations on objects (count, compute stats, etc…)
- Update attributes of an object
- Destroy an object
# Environment
- Ubuntu 20.04

- Python version: Python 3.10.5
# Installation
- Clone this repository: git clone "https://github.com/kassahunT/AirBnB_clone.git"
- Access AirBnb directory: cd AirBnB_clone
- Run hbnb(interactively): ./console and enter command
- Run hbnb(non-interactively): echo "" | ./console.py
# Tests
All the code is tested with the unittest module. The test for the classes are inthetest_models folder.

# Authors
- Kassahun Tilahun Tekelie < https://github.com/kassahunT >
- JOHNPAUL IMEOGU < https://github.com/Imeogu>
