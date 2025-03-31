# RSS
RSSReader + RSS Aggregator
A Java application that parses and processes RSS 2.0 feeds from the web and generates corresponding HTML output pages. This project includes both a standalone RSS Reader and an RSS Aggregator that builds a full HTML index page linking to multiple individual news feeds.

Features
- Parses XML RSS 2.0 feeds from any valid URL
- Extracts news items including publication date, source, title/description, and link
- Dynamically generates HTML pages displaying formatted news content in tables
- Includes an aggregator that builds an index HTML page with links to multiple feeds
- Handles missing elements gracefully and defaults to fallback content when needed

Tech Stack
Language: Java

Libraries: Custom course-provided components (SimpleReader, SimpleWriter, XMLTree)

Output: HTML (SimpleWriter)

 Overview
This project was designed as a practical exercise in XML parsing, data extraction, and HTML generation in Java. The application reads RSS feeds in real time and converts them into styled, browser-readable summaries. It demonstrates proficiency in:
- Tree-based XML navigation
- Dynamic HTML formatting
- Modular Java class structure
- Error handling and user input validation

Structure
RSSReader.java — parses and displays a single RSS feed as an HTML table

RSSAggregator.java — processes multiple feeds and builds an index page

Utilizes helper methods to handle missing data, extract specific tags, and format output cleanly

To Run Code - 
This project requires Java and a set of course-specific utility classes (provided in OSU package). 
- Compile the .java files
- Execute RSSReader or RSSAggregator
- Enter a valid RSS feed URL and an output HTML file name when prompted
- Open the generated HTML file in your browser

