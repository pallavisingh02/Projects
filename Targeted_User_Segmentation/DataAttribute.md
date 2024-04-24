The Data
---------------

Tracks of the events: "View Project" and "Fund Project," for when a user views details about a project and for when they fund a project. The events also have the following attributes:

* category: what the project is about, e.g. "Sports", "Fashion", "Technology", etc.
* client_time: a UNIX timestamp of when the event occurred.
* amount: how much the user donated (for "Fund Project" only)

#### The bicycle project belongs to two categories: "Sports" and "Environment."

Information about each user:

* session_id: unique identifier for each user
* age range: one of ['18-24', '25-34', '35-44', '45-54', '55+']
* gender: one of ['M', 'F', 'U']
* location:
* city: a city in the United States
* state: a state in the United States
* latitude
* longitude
* marital_status: one of ['single', 'married']
* device: one of ['iOS', 'android']

Dataset of 50,000 events from one month  in a JSON