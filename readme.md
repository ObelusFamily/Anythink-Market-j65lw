# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).
<br>
<br>

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.
<br>
<br>

## First setup

1. Clone the repository
2. We need docker to run the application, so install docker; if already installed proceed to next step
3. Verify that docker is ready byt running the following commands in your terminal

```
docker -v
```

```
docker-compose -v
```

4. Open terminal in the cloned projet root directory
5. Run the following command to start the application

```
docker-compose up
```

6. If everything worked properly, you should see compilation successful mesaage in the terminal, also server will start and links will be provided in the terminal . Ctrl+click (for windows) on the link - this will open up the running application.
   <br>
   <br>

#### Happy development
