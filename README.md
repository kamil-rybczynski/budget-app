# Home budgeting - app

## About

This is a front-end of home budgeting app.

![](./docs/preview.png)

## Installation

```bash
$ npm install
```

## Running the app

### Dev

```bash
$ npm run start
```

Open http://localhost:4200 url in web browser.

### Prod

Edit `src/environments/environment.prod.ts` file and set `apiUrl` param which must be url to installed `budget-api` repository.

```bash
$ npm run build
```

Handle `build` directory by web server (eg. Nginx or Apache).

## Roadmap

## 0.9.0

- [ ] Feature: Order contractors by transaction's interval by default

### 0.8.0

- [ ] Feature: Change password

### 0.7.0

- [ ] Feature: Monthly budget planning
- [ ] Feature: Progress bar of monthly budget plan realisation on budget table
- [ ] Feature: Current month plan realisation on dashboard

### 0.6.0

- [ ] Feature: Statistics for contractors
- [ ] Feature: Statistics for accounts
- [ ] Feature: Many categories to one transaction
- [ ] Travis CI and Coveralls integration
- [ ] Unit tests for NGRX store

### 0.5.0

- [ ] Feature: Add icons to categories
- [ ] Feature: Add color to parent categories
- [ ] Feature: Show categories on charts of dashboard in selected color

### 0.4.1

- [x] Fix: Unselectable categories select input on params of the transaction list
- [x] Fix: Month and category query params not handled on transaction list
- [x] Fix: Category query param handling on add transaction
- [x] Fix: Parent query param handling add category

### 0.4.0

- [x] Feature: Categories order changing by drag'n'drop

### 0.3.0

- [x] Feature: Quarterly expenses by categories chart on dashboard
- [x] Feature: Quarterly cash flow chart on dashboard
- [x] Refactoring: NGRX for state management
- [x] Upgrade Angular to v11

### 0.2.0

- [x] Enable serving app as PWA

### 0.1.0

- [x] Removing transaction
- [x] Removing category group
- [x] Removing category
- [x] Add modals for delete operations confirmation
- [x] Transactions list filtering by month
