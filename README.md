#🎬 OMDb Movie Metadata Fetcher with Caching

A Python script that fetches movie metadata from the OMDb API using a custom caching system. This is a Coursera course project from the course "Data Collection and Processing with Python". Designed for educational use without requiring an API key, the tool prioritizes efficiency by checking a permanent cache before making live API calls. If a response is missing, it fetches the data, stores it in a temporary cache, and uses it for future requests.

✅ Features

    Fetch movie details like title, year, rating, and plot

    Uses permanent and temporary cache files to avoid redundant API calls

    No API key needed for pre-cached movies

    Clean separation of caching logic and API handling

    Designed for coursework and offline API simulation

🔧 Tech Stack

    Python 3

    requests module

    JSON file-based caching
