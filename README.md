Got it! Here's the updated README:

---

# Live Docs

Welcome to **Live Docs**, a real-time collaborative document editing application with live cursors, built using [Liveblocks](https://liveblocks.io/).

## Features

- **Real-time Collaboration**: Multiple users can edit documents simultaneously.
- **Live Cursors**: See where others are editing in real-time with live cursors.
- **User Presence**: Know who is currently online and active in the document.
- **Version Control**: Keep track of changes and document versions.

## Tech Stack

- **Frontend**: Next.js, Tailwind CSS, Shadcn
- **Real-time Collaboration**: Liveblocks
- **Text Editor**: Lexical

## Getting Started

Follow these instructions to get the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Liveblocks API key (Sign up at [Liveblocks](https://liveblocks.io/) to get your API key)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/jaykapade/docs-live.git
   cd live-docs
   ```

2. Install dependencies:

   ```sh
   npm install
   # or
   yarn install
   ```

3. Create a `.env` file in the root directory and add all secrets present in .env.example:

4. Start the development server:

   ```sh
   npm run dev
   # or
   yarn dev
   ```

   The app should now be running on `http://localhost:3000`.

## Usage

1. Open `http://localhost:3000` in your browser.
2. Start a new document or join an existing one using a document ID.
3. Share the document ID with others to collaborate in real-time.

## Contributing

We welcome contributions to improve Live Docs Edit! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Liveblocks](https://liveblocks.io/) for providing real-time collaboration infrastructure.
- [Lexical](https://lexical.dev/) for the powerful text editor.
- [Next.js](https://nextjs.org/) for the robust framework.
- [Tailwind CSS](https://tailwindcss.com/) for the styling.
- [Shadcn](https://shadcn.dev/) for UI components.
