# HYPE DCA Calculator

Static English-language HYPE dollar-cost averaging calculator.

## Deploy on Vercel

### Without GitHub (Vercel CLI)
1. Unzip the archive.
2. Install Node.js if needed, then run `npm install -g vercel`.
3. In a terminal, change to the extracted `hype-dca` directory.
4. Run `vercel login` and then `vercel --prod`.
5. Follow the prompts. Use the current directory as the project root and choose **Other** for the framework if asked.

### With GitHub
Push the extracted files to a GitHub repository. In Vercel, choose **Add New > Project**, import the repository, select **Other** framework, and deploy.

## Notes
- No API keys or environment variables are required for this version.
- The calculator fetches historical prices from the public DefiLlama Coins API in the visitor's browser. Internet access is required.
- Live data fetching and historical price coverage have not been verified in a deployed browser; the calculator will show an error if the feed is unavailable.
- Trading fees, slippage and taxes are not included unless indicated in the app.
