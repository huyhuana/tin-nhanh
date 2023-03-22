# tin-nhanh
A web aplication update news hourly ( or half-hourly if allowed) in Vietnam.

Each hour ( or half-hourly if allowed), the application will automatically update the latest news from various sources through the API provided by NewsCatcher.

The displayed news will include: title, summary, a link to news's source.


## frontend forked from https://github.com/kabirsingh2004/react-news-app
1. Navigate to the project directory: `cd react-news-app/client`
2. Install dependencies: `npm install`
3. Go to src/App.jsx and change `API_BASE_URL` to Your Server Side API Url
4. Start the client: `npm run dev`