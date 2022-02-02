# Run Application

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds application that can be copied or hosted in a live server for production

# Application Content || Wiki

## Purpose

```
The aim of this application is to create a platform for  an income/expense web app where a user can keep a
record of the finantial expenditures and also be able to have the posibility to view these expenses graphically
```

## Entities

```
Category {
  id: string;
  label: string;
}

Transaction {
  id: string;
  label: string;
  date: Date | string;
  amount: number;
  category: string;
}
```

## Relationships

Transaction holds the category which is a reference to the category entity id; This is used to identify the category of a transaction

# Pages

### Home

```
This contains the key components such as
->Transaction
--->Transaction form
--->Transaction list
--->Transaction item

->Category
--->Category form
--->Category list
--->Category item

```

### Graph

```
This mainly contains a component to display the graphical representation of transactions, categories and expenses for a given user

```

# Technologies

- Javascript
- Typescript
- SCSS Modules
- React
- Redux
- localStorage as database
- uuid
- react-router & react-router-dom
