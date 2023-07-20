# Expensify App

This is a web application to manage expenses built with React and Redux.

## Features

- Add and edit expenses 
- View expenses by category or date
- Graphs and charts to visualize expenses
- Filter expenses by text, date range, etc
- Supports authentication and private accounts
- Mobile friendly responsive design

## Usage

1. Clone this repo
2. Install dependencies  
`npm install`
3. Start development server  
`npm run dev-server`
4. Open your browser to [http://localhost:8080](http://localhost:8080)

## Customizing

The main React components are located in `src/components/`. 

Redux actions, reducers, and store configuration are located in `src/redux/`.

Stylesheets are located in `src/styles/` and use Sass.

The development server uses [webpack-dev-server](https://github.com/webpack/webpack-dev-server). Configuration is based on `webpack.config.js`.

## Building for Production

Run `npm run build` to compile assets with webpack into `/dist` folder.

## License

This project is open source and available under the [MIT License](LICENSE).
