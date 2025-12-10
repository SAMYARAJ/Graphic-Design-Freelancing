📊 **YouTube Low-View Creator Data Extractor**

🚀 Overview
This Python program is a specialized data extraction tool designed for market research, creator scouting, and competitive analysis within specific content niches on YouTube.

It leverages the YouTube Data API v3 to identify and analyze channels that are highly active (posting multiple videos within the last 7 days) but whose recent videos are performing below a specified view count threshold (0 to 5,000 views). This targets new, emerging, or niche creators with high dedication but low visibility.

The program outputs a detailed list to the console and generates a structured PDF report containing key metrics and direct channel links for easy outreach or further investigation.

✨ Features
1. Niche-Specific Search: Accepts user input to narrow down the search to any topic (e.g., 'technical', 'indie games', 'vegan cooking').

2. Time-Based Filtering: Automatically filters videos published within the last 7 days.

3. Performance-Based Filtering: Filters videos to include only those with 0 to 5,000 views, ensuring focus on emerging content.

4. Creator Ranking: Sorts identified creators based on the highest number of videos posted this week, highlighting high-output channels.

5. Detailed Metrics: Calculates and reports the average view count for the filtered videos of each creator.

6. Professional Reporting: Generates a clean, multi-column PDF report (YouTube_Creator_Report.pdf) ready for sharing.

7. Actionable Links: Provides the direct channel link in both the console and the PDF output.
