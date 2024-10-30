# AlertMedia Code Challenge

Your challenge is to build something interesting that makes use of the mock data provided. You
can choose whichever technologies you like to create this application (we love Python), and
then walk us through your implementation. Tell us about the decisions that you made along the
way.

- What areas (if any) required special consideration?
- Would you have done anything differently if you had more time?

## Ideas

Below are some examples of what can be done with this data, but feel free to be creative and
build your own thing:

- A task manager application
- Data analysis dashboard

## Data
One way to make use of the mock data (JSON file) is to deploy it into a local API endpoint using
JSON-Server.

1. Install json-server

```> npm install -g json-server```

2. Make a copy of the provided `db.json` file.  **POST**, **PUT**, **PATCH** and **DELETE** requests will be automatically saved to the file.
3. Start JSON-Server

```> json-server -p [PORT] --watch db.json```

4. Access API endpoint through `http://localhost:[PORT]`

See https://github.com/typicode/json-server for full JSON-Server documentation
