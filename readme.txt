VirtualEnv : https://virtualenv.pypa.io/en/latest/userguide/

virtualenv ENV
source /path/to/ENV/bin/activate
ENV\Scripts\activate
Set-ExecutionPolicy AllSigned
Set-ExecutionPolicy RemoteSigned
rm -r /path/to/ENV
activate_this = '/path/to/env/bin/activate_this.py'
execfile(activate_this, dict(__file__=activate_this))
virtualenv --relocatable ENV
virtualenv --extra-search-dir=/path/to/distributions ENV
-------------------------------------------------------------------
python.exe .\scrapper.py

-------------------------------------------------------------------
GITHUB :
https://github.com/fredericazoulay/scraper_beautifulsoup.git
…or create a new repository on the command line
echo "# scraper_beautifulsoup" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/fredericazoulay/scraper_beautifulsoup.git
git push -u origin master
…or push an existing repository from the command line
git remote add origin https://github.com/fredericazoulay/scraper_beautifulsoup.git
git push -u origin master
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


-------------------------------------------------------------------
#html_doc = """
#<html><head><title>The Dormouse's story</title></head>
#<body>
#<p class="title"><b>The Dormouse's story</b></p>
#
#<p class="story">Once upon a time there were three little sisters; and their names were
#<a href="http://example.com/elsie" class="sister" id="link1">Elsie</a>,
#<a href="http://example.com/lacie" class="sister" id="link2">Lacie</a> and
#<a href="http://example.com/tillie" class="sister" id="link3">Tillie</a>;
#and they lived at the bottom of a well.</p>
#
#<p class="story">...</p>
#"""
#soup = BeautifulSoup(html_doc, 'html.parser')