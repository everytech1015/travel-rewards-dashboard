
# Travel Rewards Dashboard

A sleek and intuitive **Travel Rewards Dashboard** built with **Next.js**, **React**, and **Tailwind CSS** to help users explore travel reward redemptions.

## Features
- **Responsive design** for both mobile and desktop views.
- Display travel reward redemption options (destination, airline, cost, and points value).
- **Interactive UI**: Click to select a reward and see detailed information.
- Book rewards (in progress).

## Tech Stack
- **Next.js**: A powerful React framework for building fast, server-side rendered applications.
- **React**: Frontend library for building the UI.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **TypeScript**: A superset of JavaScript that provides static typing.
- **React Hooks** (`useState`): To manage the state of the selected reward.

## Getting Started

Follow these steps to get the project running locally:

### Prerequisites
- **Node.js** (Recommended version: v16 or later)

### Install Dependencies
1. Clone the repository:

   ```bash
   git clone https://github.com/everytech1015/travel-rewards-dashboard.git
   cd travel-rewards-dashboard
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

### Run the Development Server
Start the Next.js development server:

```bash
npm run dev
```

Now open your browser and go to [http://localhost:3000](http://localhost:3000) to view the dashboard.

## Folder Structure

```
/src
  /app
    page.tsx       # Main page for the dashboard UI
  /components
    /ui
      card.tsx     # Card component for displaying reward details
      button.tsx   # Button component for interaction
```

## Future Features
- Add the ability to **filter** rewards by airline, points, or class.
- Integrate with a **real booking API** for actual reward booking.
- Improve **state management** with tools like **Redux** or **Recoil**.

## Contributing

Feel free to fork the repository, submit issues, and create pull requests.

1. Fork the repo
2. Clone your forked repo
3. Create a new branch (`git checkout -b feature-name`)
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to your branch (`git push origin feature-name`)
6. Create a new Pull Request

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
