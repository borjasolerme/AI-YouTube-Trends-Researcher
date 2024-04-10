# AI YouTube Trends Researcher

[![Twitter Follow](https://img.shields.io/twitter/follow/borjasolerr?style=social)](https://twitter.com/borjasolerr) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1slMRdB5xE5UhQ4kgvkrbLzYaQkLp2IT1?usp=sharing)

The AI YouTube Trends Researcher is a Google Colab notebook that utilizes the Anthropic Claude AI model to generate video ideas based on trending YouTube videos for a given topic. It analyzes the trending videos, identifies key trends and insights, and provides actionable recommendations for creating successful content.

## Features

- Fetches trending YouTube videos related to a specified topic using the `youtubesearchpython` library
- Ranks the video trends based on the frequency of topics and total view counts
- Generates a mini report analyzing the trends, patterns, and opportunities for content creation
- Provides video ideas inspired by the trending videos and the generated mini report
- Saves the mini report, video ideas, and trending video information in a Word document

## Prerequisites

- Google Colab account
- Anthropic API key (replace `YOUR KEY HERE` with your actual API key)

## Getting an Anthropic API Key

To use the YouTube Video Idea Generator, you need an Anthropic API key. Follow these steps to obtain one:

1. Go to the Anthropic website: https://www.anthropic.com

2. Click on the "Sign Up" button in the top right corner of the page.

3. Fill out the registration form with your email address and desired password.

4. Verify your email address by clicking on the verification link sent to your registered email.

5. Once logged in, navigate to the API section of your Anthropic account dashboard.

6. Click on the "Create API Key" button to generate a new API key.

7. Copy the generated API key and replace YOUR KEY HERE in the notebook with your actual API key.

Note: Keep your API key confidential and avoid sharing it publicly.

## Usage

1. Open the `YouTube_Video_Idea_Generator.ipynb` notebook in Google Colab.

2. Replace `YOUR KEY HERE` with your actual Anthropic API key in the following line:

   ```
   ANTHROPIC_API_KEY = "YOUR KEY HERE"
   ```

3. Run the notebook cells sequentially.

4. When prompted, enter a topic to generate video ideas for and the desired number of video ideas.

5. The notebook will perform the following steps:

   - Fetch trending YouTube videos related to the specified topic
   - Rank the video trends based on topic frequency and view counts
   - Generate a mini report analyzing the trends and providing insights
   - Generate video ideas inspired by the trending videos and the mini report

6. The mini report, video ideas, and trending video information will be displayed in the notebook.

7. A Word document containing the mini report, video ideas, and trending video information will be generated and automatically downloaded.

## Customization

You can customize the behavior of the YouTube Video Idea Generator by modifying the following parameters in the notebook:

- `model`: The name of the Anthropic Claude AI model to use (default: "claude-3-haiku-20240307").
- `max_tokens`: The maximum number of tokens to generate in each AI response (default: 2000).
- `temperature`: The temperature value for controlling the randomness of the AI responses (default: 0.7).

## Limitations

- The quality and relevance of the generated video ideas and mini report depend on the performance of the Anthropic Claude AI model and the trending YouTube videos fetched for the specified topic.
- The notebook may take some time to execute, especially for topics with a large number of trending videos.

## License

This project is licensed under the MIT License.

## Disclaimer

The AI YouTube Trends Researcher is an experimental tool and should be used for informational and educational purposes only. The generated video ideas and mini report may not guarantee success or viral performance on YouTube. Always exercise your own judgment and creativity when creating content based on the generated ideas.

## Acknowledgments

- Anthropic for providing the Claude AI API.
- The developers of the `youtubesearchpython` library for simplifying YouTube video search.

## Contact

For any questions or feedback, please reach out me on Twitter: [![Twitter Follow](https://img.shields.io/twitter/follow/borjasolerr?style=social)](https://twitter.com/borjasolerr)

🙋🏻‍♂️ before you go, if you want to try some AI products I'm building, check out [videotok.app](https://videotok.app) and [editby.ai](https://editby.ai). Videotok.app is an AI-powered platform that creates viral Shorts and videos from text, while editby.ai helps you create SEO-optimized content that ranks on Google and social media.
