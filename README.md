Brainy Flavors
##### Linkedin Learning Courses Downloader
###### v0.2: now works without webdriver

A simple python scraper tool that downloads video lessons from Linkedin Learning

## How to use
* Make sure you have installed python 2.7 version in your PC
* Install pip (If you do not install it before)
* Intall BS4 (BS4 = BeautiFul Soup 4)



First install the requirements:
```
pip install -r requirements.txt
```
In the `config.py` file, write your login info and fill the `COURSES` array with the slug of the the courses you want to download, for example:

`https://www.linkedin.com/learning/it-security-foundations-core-concepts/ -> it-security-foundations-core-concepts`

```
USERNAME = 'user@email.com'
PASSWORD = 'password'

COURSES = [
    'it-security-foundations-core-concepts',
    'javascript-for-web-designers-2'
]
```
Then excecute the script:
```
python llcd.py
```
The courses will be saved in the `out` folder.

### Demo
