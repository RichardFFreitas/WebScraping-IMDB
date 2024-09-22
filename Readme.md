<h1 align="center" style="font-weight: bold;">IMDB Web Scraper 🎬</h1>

<p align="center">
  <a href="#tech">Technologies</a> •
  <a href="#started">Getting Started</a> •
  <a href="#usage">Usage</a> •
  <a href="#colab">Collaborators</a> •
  <a href="#contribute">Contribute</a>
</p>

<p align="center">
  <b>A Python-based web scraper to extract movie information from IMDB.</b>
</p>

<h2 id="technologies">💻 Technologies</h2>

- Python 3.x
- BeautifulSoup4
- Requests
- CSV

<h2 id="started">🚀 Getting started</h2>

Here's how to set up the project locally.

<h3>Prerequisites</h3>

- [Python 3.x](https://www.python.org/downloads/)
- [Git](https://git-scm.com/downloads)

<h3>Cloning</h3>

```bash
git clone https://github.com/yourusername/imdb-web-scraper.git
cd imdb-web-scraper
```

<h3>Setting up a virtual environment</h3>

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

<h3>Installing dependencies</h3>

```bash
pip install -r requirements.txt
```

<h2 id="usage">🎯 Usage</h2>

To run the IMDB web scraper:

```bash
python scraper.py
```

This will start the scraping process and save the results to a CSV file named `movies.csv` in the project directory.

<h3>Customization</h3>

You can modify the `scraper.py` file to change:
- The number of movies to scrape
- The specific information to extract (e.g., title, rating, year, etc.)
- The output format or filename

<h2 id="colab">🤝 Collaborators</h2>

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/your_id?v=4" width="100px;" alt="Your Name Profile Picture"/><br>
        <sub>
          <b>Your Name</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

<h2 id="contribute">📫 Contribute</h2>

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<h3>Documentations that might help</h3>

- [How to create a Pull Request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)
- [Python Style Guide (PEP 8)](https://www.python.org/dev/peps/pep-0008/)
- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Requests Documentation](https://docs.python-requests.org/en/latest/)
