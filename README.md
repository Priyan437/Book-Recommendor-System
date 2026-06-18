# Book Recommendor System 

A Book Recommendor system used by using Python analysis and logic having the Top 50 trending recommendation as well the 5 similar Books Recommendation pages.

  
<!-- About the Project -->
## About the Project


<!-- Screenshots -->
### Screenshots of the 5 Similar Book Recommendor Page

<div align="center"> 
  <img src="https://github.com/Priyan437/Book-Recommendor-System/blob/4d5136e6f674403a88a14dfc854ff4f8bb09549f/Asset/Screenshot%20From%202026-06-18%2020-08-10.png" alt="Webpage Image" />
</div>


<!-- TechStack -->
### Tech Stack

<details>
 
  <ul>
    <li>Flask</li>
    <li>Python</li>
    <li>HTML</li>
    <li>Excel</li>
  </ul>
</details>

<!-- Features -->
### Features

- It has the Top 50 Book recommended according to the available Database(This is being calculated on analysis and the eligibile books are that which has being rated by 250 or greater than that Users and avg rating greater that 4.)
- It has the section of Book Recommendor in which user can write book name that is available in Database and 5 similar books are recommended to user which is similar.(Here I primarily use Cosine Similarity).
- It has the Contact page consisting of my contact.


Clone the project

```bash
https://github.com/Priyan437/Book-Recommendor-System.git
```

Go to the project directory

```bash
  cd Book-Recommendor-System
```

Create and Activate the Virtual Enviroment

```bash
python -m venv book
# Windows:
.\book\Scripts\activate
# Linux/macOS:
source book/bin/activate
```


Install dependencies

```bash
  pip install requirements.txt
```




