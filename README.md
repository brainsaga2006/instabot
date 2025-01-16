
1. Clone the repository:
   ```bash
   git clone https://github.com/brainsaga2006/instabot.git
   cd instabot
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the project root directory and add the following environment variables:
   ```env
   RAPID_API_KEY=your-rapid-api-key
   RAPID_API_HOST=your-rapid-api-host
   TELEGRAM_API=your-telegram-api-token
   ```

   You can obtain the `RAPID_API_KEY` and `RAPID_API_HOST` by signing up for the [Instagram Looter2 API on RapidAPI](https://rapidapi.com/iq.faceok/api/instagram-looter2).

4. Start the server in development mode using Nodemon:
   ```bash
   npm run dev
   ```

5. Start using your Telegram bot! Send it Instagram links (except for stories), and it will reply with the media files.

