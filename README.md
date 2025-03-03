# Currency Converter App

This is a simple currency converter application built using Angular and styled with Tailwind CSS. The app allows users to convert amounts between different currencies using live exchange rates from a public API.

## Features

- Convert between multiple currencies
- Real-time exchange rates using an external API
- Responsive design with a modern UI
- Built with Angular and Tailwind CSS for a clean and scalable codebase

## Getting Started

### Prerequisites

Ensure you have Node.js and Angular CLI installed on your machine.

- Node.js: [Download Node.js](https://nodejs.org/)
- Angular CLI: Install via npm:

  ```bash
  npm install -g @angular/cli
  ```

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/OnkarShelarr/currency-converter-app.git
   cd currency-converter-app
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Set up Tailwind CSS:
   If not already configured, follow [Tailwind CSS Setup Guide](https://tailwindcss.com/docs/guides/angular) to integrate Tailwind CSS into your Angular project.

4. Get an API key from a currency exchange service, such as [ExchangeRate-API](https://www.exchangerate-api.com/) or [exchangeratesapi.io](https://exchangeratesapi.io/), and replace `YOUR_API_KEY` in the service file:

   ```typescript
   YOUR_API_KEY = 'YOUR_API_KEY';
   ```

### Usage

1. Run the development server:

   ```bash
   ng serve
   ```

2. Open your browser and navigate to:

   ```text
   http://localhost:4200
   ```

3. You can now use the app to convert currencies.

### Project Structure

```plaintext
src/
├── app/
│   ├── services/
│   │   ├── exchange-rate.service.ts
│   ├── app.component.html
│   ├── app.component.ts
│   ├── app.component.scss
│   └── app.conifg.ts
|   └── app.routes.ts
├── styles.scss
└── index.html
```

### Built With

- [Angular](https://angular.io/) - Web framework
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [ExchangeRate-API](https://www.exchangerate-api.com/) - Currency exchange rates API

### License

This project is licensed under the MIT License.

---

Feel free to contribute or provide feedback!
