Keyword Pilot AI

Keyword Pilot AI helps you find keyword ideas and plan content for websites, YouTube, and social media.

It is designed for content creators, bloggers, marketers, and small businesses who want help deciding what to write about.

✨ Features

- Keyword Suggestions: Enter a topic to get related keywords, long-tail keywords, and questions.
- Search Intent Analysis: Understand what people may want when they search for something.
- Keyword Metrics: View search volume, keyword difficulty, and CPC when available.
- Charts and Analytics: Explore keyword results through visual charts.
- Filter and Sort: Find keywords based on their phrase, type, intent, or difficulty.
- Copy and Export: Copy selected keywords or download them as a CSV file.
- Save Keywords: Bookmark useful keywords for later.
- Content Planning: Generate SEO titles, meta descriptions, YouTube tags, social media hashtags, and article outlines.

🛠️ Technologies Used

- HTML5 and CSS3
- Tailwind CSS
- JavaScript (ES6+)
- Google Gemini API ("gemini-3-flash-preview")
- Chart.js
- Lucide Icons

🚀 Getting Started

1. Open the Application

Open the main HTML file in a modern web browser, or use the development setup provided by the project.

2. Choose a Mode

KeywordPilot AI offers two modes.

Demo Simulation Mode

- No API key is required.
- Uses simulated results to demonstrate keyword research.
- Search volume and difficulty values are not guaranteed to reflect real Google data.

Live Gemini AI Mode

- Requires a Google Gemini API key.
- Uses AI to generate keyword ideas and content suggestions.
- AI-generated metrics may be estimates rather than verified search data.

Important: Connecting a Gemini API key does not automatically provide real Google search-volume data. The project documentation does not specify a connection to Google Keyword Planner or another verified keyword-metrics provider.

🔑 How to Set Up Gemini AI

1. Visit "Google AI Studio" (https://aistudio.google.com/) to obtain an API key.
2. Open KeywordPilot AI.
3. Find the Gemini API Key Integration field through the mode badge or the API & Source Info tab.
4. Enter your API key and click Save Key.
5. Check that the application displays Gemini AI Live Mode.

Keep your API key private. Do not upload it to GitHub or share it publicly.

📖 How to Use KeywordPilot AI

Step 1: Enter Your Topic

Enter a keyword or topic, such as:

- Digital marketing
- Cold brew coffee
- Website development

Step 2: Choose Your Target Audience

Select your preferred platform, country, and language. You can also enter your industry and target audience.

Step 3: Generate Keywords

Choose how many keyword ideas you want: 15, 25, 35, or 50.

Click Generate Keyword Intelligence to generate the results.

Step 4: Analyze the Results

Review the suggested keywords, search intent, search volume, keyword difficulty, and charts.

Step 5: Save or Export Keywords

Filter and sort the results, bookmark useful keywords, copy selected results, or export them as a CSV file.

Step 6: Create a Content Plan

Open Content Plan & Meta Generator to generate draft SEO titles, meta descriptions, YouTube tags, social media hashtags, and article outlines.

Review the suggestions before publishing.

📊 Understanding Keyword Metrics

- Keyword: A phrase that someone might search for online.
- Search Intent: What the person may want to find, learn, or do.
- Search Volume: An estimate of how often a keyword is searched.
- Keyword Difficulty: An estimate of how difficult it may be to rank for a keyword.
- CPC: Cost per click, when available.
- Rationale: An explanation of why a keyword might be useful.

If a metric displays "N/A", the value is unavailable. It does not mean zero.

Remember: Keyword suggestions can be useful for brainstorming, but search-volume and difficulty figures should be verified using reliable data sources before making important SEO decisions.

🔒 Privacy and Security

According to the project documentation:

- The application does not scrape Google search results pages.
- The Gemini API key is stored in the browser's "localStorage".
- The documentation states that the application does not send the key through a proxy server or external backend.

Browser storage does not make an API key completely secure. For a public production website, consider using a secure server-side integration and appropriate API key restrictions.

When using Live mode, requests are sent to Google's Gemini API.

⚠️ Limitations

- Demo mode uses simulated results.
- AI-generated suggestions may be inaccurate or irrelevant.
- Search volume and keyword difficulty may be estimates.
- The documentation does not establish that verified Google keyword metrics are connected.
- Live mode requires a valid Gemini API key and is subject to Google's API limits and terms.

🤝 Contributing

Contributions and suggestions are welcome.

1. Fork the repository.
2. Create a branch for your changes.
3. Make and test your improvements.
4. Submit a pull request explaining your changes.

Never include API keys, passwords, or other private information in commits.

🙌 Acknowledgements

Built using HTML, CSS, JavaScript, Tailwind CSS, Google Gemini API, Chart.js, and Lucide Icons.

KeywordPilot AI — Find keyword ideas, understand search intent, and plan better content.
