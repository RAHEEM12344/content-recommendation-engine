# Content Recommendation Engine

A modern, responsive web application that delivers personalized content recommendations based on user preferences and behavior. This interactive recommendation system allows users to discover content tailored to their interests through category selection, tag filtering, and customizable content parameters.

## Features

- **Personalized Recommendations**: Intelligent content discovery based on user preferences
- **Category Selection**: Filter content by specific categories like Technology, Cooking, Health, etc.
- **Tag-Based Filtering**: Fine-tune recommendations with interest-based tags
- **Customizable Parameters**: Adjust recommendation algorithm with sliders for:
  - Popularity: Balance between trending and niche content
  - Similarity: Control content diversity based on previous selections
- **Match Scoring**: Visual indication of how well content matches user preferences
- **Responsive Design**: Seamless experience across desktop and mobile devices

## Implementation Details

The recommendation engine uses a sophisticated algorithm that considers:

- Category matching
- Tag relevance
- Content popularity
- Similarity to previously viewed content
- User-adjusted preference weights

The scoring system combines these factors to present the most relevant content to each user, continuously adapting as they interact with the application.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Styling**: Custom CSS with CSS variables for theming
- **Icons**: Font Awesome
- **Responsive Layout**: Flexbox and CSS Grid

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/husal90/content-recommendation-engine.git
   ```

2. Open `index.html` in your browser to run the application locally

3. Alternatively, deploy to any static site hosting service

## Usage

1. **Select Categories**: Click on category buttons to filter content by topics
2. **Choose Tags**: Select interest tags to refine recommendations
3. **Adjust Parameters**:
   - Slide toward "Popular" for trending content
   - Slide toward "Similar" for content matching your previous selections
4. **Update Recommendations**: Click the "Update Recommendations" button to refresh content
5. **Explore Content**: Click on content cards to view (this also affects future recommendations)

## Dataset

The application includes a sample dataset of 120 content items across various categories:
- Technology
- Cooking
- Design
- Finance
- Health
- Business
- Education
- Art
- Lifestyle
- Travel
- Psychology

Each content item contains metadata including title, category, tags, and popularity metrics.

## Customization

- **Theming**: Modify CSS variables in the `:root` selector to change the color scheme
- **Content Database**: Replace or expand the `contentDatabase` array with your own content
- **Algorithm Weighting**: Adjust the scoring formula in the `calculateRecommendationScore()` function

## Future Enhancements

- User accounts and preference saving
- Machine learning-based recommendation improvements
- Content filtering by date/recency
- Social sharing integration
- Detailed content pages
- API integration for dynamic content

## License

MIT License

## Author

- GitHub: [@husal90](https://github.com/husal90)

---

Feel free to contribute to this project by submitting pull requests or opening issues for bugs and feature requests.
