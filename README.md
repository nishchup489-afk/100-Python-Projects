
# 🚀 100 FastAPI Projects

### A Mission to Build 100 Practical Python Web Tools with FastAPI

📊 **Project Statistics**

| Metric                 | Value                                         |
| ---------------------- | --------------------------------------------- |
| Total Projects         | **100**                                       |
| Primary Stack          | **CLI in terminal** and **FastAPI + Jinja2 Templates + Tailwind CSS for web** |
| Development Style      | Structured, incremental builds                |
| Deployment             | **Vercel**                                    |
| Environment Management | **Poetry**                                    |
| Architecture           | Template-driven web utilities                 |

---

# 🎯 About

This repository documents my mission to build **100 Python projects using FastAPI**.

Instead of traditional **command-line programs**, every project is implemented as a **web-based tool** using:

* **CLI** for pure python no website and FastAPI
* **FastAPI** for backend logic
* **Jinja2 templates** for rendering pages
* **Tailwind CSS** for clean UI
* **Poetry** for dependency management
* **Vercel** for deployment

Each project is a **small but complete web application**, accessible through a browser rather than the terminal.

The mission transforms classic programming exercises into **interactive web utilities** that demonstrate real-world backend development skills.

---

# 🌟 What Makes This Special

Most “100 Python Projects” repositories build **CLI scripts**.

This project upgrades them into **fully functional web applications**.

Every project includes:

✅ CLI version of project in pure python in **sample.py**
✅ FastAPI backend
✅ Jinja2 template interface
✅ Tailwind CSS UI
✅ Organized folder structure
✅ Documentation and examples
✅ Independent deployment capability

The result is a collection of **real web tools**, not just exercises.

---

# 🧠 Learning Goals

This mission focuses on mastering:

* Python problem solving
* FastAPI backend development
* Template-based web apps
* asynchronous programming
* API design
* software architecture
* project organization

Instead of writing small throwaway scripts, each idea becomes a **deployable web service**.

---

# 🧰 Tech Stack

Core technologies used across the repository:

### Backend

* FastAPI
* Python 3.10+

### Frontend

* Jinja2 templates
* Tailwind CSS
* Babel (for frontend tooling)

### Environment

* Poetry (dependency and virtual environment management)
* you can use venv also , which is much easier

### Hosting

* Vercel

---

# 🏗️ Typical Project Structure

Every project follows a consistent structure:

```
project-name/
│
├── app/
│   ├── main.py
│   ├── routers/
│   ├── services/
│   └── schemas/
│
├── templates/
│   └── index.html
│
├── static/
│   └── styles.css
│
├── pyproject.toml
└── README.md
```

This structure keeps projects **clean, scalable, and maintainable**.

---

# ▶ Running a Project

### Clone the repository

```bash
git clone https://github.com/yourusername/100-fastapi-projects](https://github.com/nishchup489-afk/100-Python-Projects
```

### Navigate to a project

```bash
cd projects/calculator
```

### Install dependencies

```bash
poetry install
```

### Run the development server

```bash
poetry run uvicorn app.main:app --reload
```

### Open in browser

```
http://127.0.0.1:8000
```

---

# 📚 Project Categories

The 100 projects span multiple domains to ensure a wide range of programming experience.

---

## Numbers

| Project | Description |
| :--- | :--- |
| [**Find PI to the Nth Digit**](numbers/n1_find_pi_to_nth_digit) | Enter a number and have the program generate PI up to that many decimal places. |
| [**Find e to the Nth Digit**](Numbers/FindE) | Just like the previous problem, but with e instead of PI. |
| [**Fibonacci Sequence**](Numbers/Fibonacci) | Enter a number and have the program generate the Fibonacci sequence to that number or to the Nth number. |
| [**Prime Factorization**](Numbers/PrimeFactorization) | Have the user enter a number and find all Prime Factors (if there are any) and display them. |
| [**Next Prime Number**](Numbers/NextPrimeNumber) | Have the program find prime numbers until the user chooses to stop asking for the next one. |
| [**Find Cost of Tile to Cover W x H Floor**](Numbers/TileCost) | Calculate the total cost of tile it would take to cover a floor plan of width and height, using a cost entered by the user. |
| [**Mortgage Calculator**](Numbers/MortgageCalculator) | Calculate the monthly payments of a fixed term mortgage over given Nth terms at a given interest rate. |
| [**Change Return Program**](Numbers/ChangeReturn) | The user enters a cost and then the amount of money given. The program will figure out the change and the number of quarters, dimes, nickels, pennies needed. |
| [**Binary to Decimal and Back Converter**](Numbers/BinaryDecimal) | Develop a converter to convert a decimal number to binary or a binary number to its decimal equivalent. |
| [**Calculator**](Numbers/Calculator) | A simple calculator to do basic operators. Make it a scientific calculator for added complexity. |
| [**Unit Converter**](Numbers/UnitConverter) | Converts various units between one another. The user enters the type of unit being entered, the type of unit they want to convert to and then the value. |
| [**Alarm Clock**](Numbers/AlarmClock) | A simple clock where it plays a sound after X number of minutes/seconds or at a particular time. |
| [**Distance Between Two Cities**](Numbers/DistanceBetweenCities) | Calculates the distance between two cities and allows the user to specify a unit of distance. |
| [**Credit Card Validator**](Numbers/CreditCardValidator) | Takes in a credit card number from a common credit card vendor (Visa, MasterCard, American Express, Discoverer) and validates it to make sure that it is a valid number (look into how credit cards use a checksum). |
| [**Tax Calculator**](Numbers/TaxCalculator) | Asks the user to enter a cost and either a country or state tax. It then returns the tax plus the total cost with tax. |
| [**Factorial Finder**](Numbers/FactorialFinder) | The Factorial of a positive integer, n, is defined as the product of the sequence n, n-1, n-2, ...1 and the factorial of zero, 0, is defined as being 1. Solve this using both loops and recursion. |
| [**Complex Number Algebra**](Numbers/ComplexAlgebra) | Show addition, multiplication, negation, and inversion of complex numbers in separate functions. (Subtraction and division operations can be made with pairs of these operations.) Print the results for each operation tested. |
| [**Happy Numbers**](Numbers/HappyNumbers) | A happy number is defined by the following process. Starting with any positive integer, replace the number by the sum of the squares of its digits, and repeat the process until the number equals 1 (where it will stay), or it loops endlessly in a cycle which does not include 1. Those numbers for which this process ends in 1 are happy numbers, while those that do not end in 1 are unhappy numbers. |
| [**Number Names**](Numbers/NumberNames) | Show how to spell out a number in English. You can use a preexisting implementation or roll your own, but you should support inputs up to at least one million (or the maximum value of your language's default integer type, if that's less). |
| [**Coin Flip Simulation**](Numbers/CoinFlip) | Write some code that simulates flipping a single coin however many times the user decides. The code should record the outcomes and count the number of tails and heads. |
| [**Limit Calculator**](Numbers/LimitCalculator) | Ask the user to enter f(x) and the limit value, then return the value of the limit statement. |
| [**Fast Exponentiation**](Numbers/FastExponentiation) | Ask the user to enter 2 integers a and b and output a^b (i.e. pow(a,b)) in O(lg n) time complexity. |

## Classic Algorithms

| Project | Description |
| :--- | :--- |
| [**Collatz Conjecture**](ClassicAlgorithms/Collatz) | Start with a number n > 1. Find the number of steps it takes to reach one using the following process: If n is even, divide it by 2. If n is odd, multiply it by 3 and add 1. |
| [**Sorting**](ClassicAlgorithms/Sorting) | Implement two types of sorting algorithms: Merge sort and bubble sort. |
| [**Closest pair problem**](ClassicAlgorithms/ClosestPair) | The closest pair of points problem or closest pair problem is a problem of computational geometry: given n points in metric space, find a pair of points with the smallest distance between them. |
| [**Sieve of Eratosthenes**](ClassicAlgorithms/SieveOfEratosthenes) | The sieve of Eratosthenes is one of the most efficient ways to find all of the smaller primes (below 10 million or so). |

## Graph

| Project | Description |
| :--- | :--- |
| [**Graph from links**](Graphs/GraphFromLinks) | Create a program that will create a graph or network from a series of links. |
| [**Eulerian Path**](Graphs/EulerianPath) | Create a program which will take as an input a graph and output either a Eulerian path or a Eulerian cycle, or state that it is not possible. |
| [**Connected Graph**](Graphs/ConnectedGraph) | Create a program which takes a graph as an input and outputs whether every node is connected or not. |
| [**Dijkstra’s Algorithm**](Graphs/Dijkstra) | Create a program that finds the shortest path through a graph using its edges. |
| [**Minimum Spanning Tree**](Graphs/MinimumSpanningTree) | Create a program which takes a connected, undirected graph with weights and outputs the minimum spanning tree of the graph i.e., a subgraph that is a tree, contains all the vertices, and the sum of its weights is the least possible. |

## Data Structures

| Project | Description |
| :--- | :--- |
| [**Inverted index**](DataStructures/InvertedIndex) | An Inverted Index is a data structure used to create full text search. |

## Text

| Project | Description |
| :--- | :--- |
| [**Fizz Buzz**](Text/FizzBuzz) | Write a program that prints the numbers from 1 to 100. But for multiples of three print “Fizz” instead of the number and for the multiples of five print “Buzz”. For numbers which are multiples of both three and five print “FizzBuzz”. |
| [**Reverse a String**](Text/ReverseString) | Enter a string and the program will reverse it and print it out. |
| [**Pig Latin**](Text/PigLatin) | Pig Latin is a game of alterations played on the English language game. To create the Pig Latin form of an English word the initial consonant sound is transposed to the end of the word and an ay is affixed (Ex.: "banana" would yield anana-bay). |
| [**Count Vowels**](Text/CountVowels) | Enter a string and the program counts the number of vowels in the text. For added complexity have it report a sum of each vowel found. |
| [**Check if Palindrome**](Text/Palindrome) | Checks if the string entered by the user is a palindrome. That is that it reads the same forwards as backwards like “racecar” |
| [**Count Words in a String**](Text/CountWords) | Counts the number of individual words in a string. For added complexity read these strings in from a text file and generate a summary. |
| [**Text Editor**](Text/TextEditor) | Notepad style application that can open, edit, and save text documents. |
| [**RSS Feed Creator**](Text/RSSFeedCreator) | A program which can read in text from other sources and put it in RSS or Atom format. |
| [**Quote Tracker**](Text/QuoteTracker) | A program which can go out and check the current value of stocks for a list of symbols entered by the user. |
| [**Guestbook / Journal**](Text/Guestbook) | A simple application that allows people to add comments or write journal entries. It can allow comments or not and timestamps for all entries. |
| [**Vigenere / Vernam / Ceasar Ciphers**](Text/VigenereCipher) | Functions for encrypting and decrypting data messages. Then send them to a friend. |
| [**Regex Query Tool**](Text/RegexQuery) | A tool that allows the user to enter a text string and then in a separate control enter a regex pattern. It will run the regular expression against the source text and return any matches or flag errors in the regular expression. |

## Networking

| Project | Description |
| :--- | :--- |
| [**FTP Program**](Networking/FTPProgram) | A file transfer program which can transfer files back and forth from a remote web sever. |
| [**Bandwidth Monitor**](Networking/BandwidthMonitor) | A small utility program that tracks how much data you have uploaded and downloaded from the net during the course of your current online session. |
| [**Port Scanner**](Networking/PortScanner) | Enter an IP address and a port range where the program will then attempt to find open ports on the given computer by connecting to each of them. On any successful connection mark the port as open. |
| [**Mail Checker (POP3 / IMAP)**](Networking/MailChecker) | The user enters various account information include web server and IP, protocol type (POP3 or IMAP) and the application will check for email at a given interval. |
| [**Country from IP Lookup**](Networking/CountryFromIP) | Enter an IP address and find the country that IP is registered in. |
| [**Whois Search Tool**](Networking/WhoisSearch) | Enter an IP or host address and have it look it up through whois and return the results to you. |
| [**Site Checker with Time Scheduling**](Networking/SiteChecker) | An application that attempts to connect to a website or server every so many minutes or a given time and check if it is up. If it is down, it will notify you by email or by playing a sound. |

## Classes

| Project | Description |
| :--- | :--- |
| [**Product Inventory Project**](Classes/ProductInventoryProject) | Create an application which manages an inventory of products. Create a product class which has a price, id, and quantity on hand. Then create an inventory class which keeps track of various products and can sum up the inventory value. |
| [**Airline / Hotel Reservation System**](Classes/ReservationSystem) | Create a reservation system which books airline seats or hotel rooms. It charges various rates for particular sections of the plane or hotel. Example, first class is going to cost more than coach. Hotel rooms have penthouse suites which cost more. Keep track of when rooms will be available and can be scheduled. |
| [**Company Manager**](Classes/CompanyManager) | Create an hierarchy of classes - abstract class Employee and subclasses HourlyEmployee, SalariedEmployee, Manager and Executive. Every one's pay is calculated differently, research a bit about it. After you've established an employee hierarchy, create a Company class that allows you to manage the employees. You should be able to hire, fire and raise employees. |
| [**Bank Account Manager**](Classes/BankAccountManager) | Create a class called Account which will be an abstract class for three other classes: CheckingAccount, SavingsAccount and BusinessAccount. Manage credits and debits from these accounts through an ATM style program. |
| [**Patient / Doctor Scheduler**](Classes/PatientDoctorScheduler) | Create a patient class and a doctor class. Have a doctor that can handle multiple patients and setup a scheduling program where a doctor can only handle 16 patients during an 8 hr work day. |
| [**Recipe Creator and Manager**](Classes/RecipeManager) | Create a recipe class with ingredients and a put them in a recipe manager program that organizes them into categories like deserts, main courses or by ingredients like chicken, beef, soups, pies etc. |
| [**Image Gallery**](Classes/ImageGallery) | Create an image abstract class and then a class that inherits from it for each image type. Put them in a program which displays them in a gallery style format for viewing. |
| [**Shape Area and Perimeter Classes**](Classes/ShapeArea) | Create an abstract class called Shape and then inherit from it other shapes like diamond, rectangle, circle, triangle etc. Then have each class override the area and perimeter functionality to handle each shape type. |
| [**Flower Shop Ordering To Go**](Classes/FlowerShop) | Create a flower shop application which deals in flower objects and use those flower objects in a bouquet object which can then be sold. Keep track of the number of objects and when you may need to order more. |
| [**Family Tree Creator**](Classes/FamilyTree) | Create a class called Person which will have a name, when they were born and when (and if) they died. Allows the user to create these Person classes and put them into a family tree structure. Print out the tree to the screen. |

## Threading

| Project | Description |
| :--- | :--- |
| [**Create A Progress Bar for Downloads**](Threading/DownloadProgressBar) | Create a progress bar for applications that can keep track of a download in progress. The progress bar will be on a separate thread and will communicate with the main thread using delegates. |
| [**Bulk Thumbnail Creator**](Threading/BulkThumbnailCreator) | Picture processing can take a bit of time for some transformations. Especially if the image is large. Create an image program which can take hundreds of images and converts them to a specified size in the background thread while you do other things. For added complexity, have one thread handling re-sizing, have another bulk renaming of thumbnails etc. |

## Web

| Project | Description |
| :--- | :--- |
| [**Page Scraper**](Web/PageScraper) | Create an application which connects to a site and pulls out all links, or images, and saves them to a list. |
| [**Online White Board**](Web/OnlineWhiteBoard) | Create an application which allows you to draw pictures, write notes and use various colors to flesh out ideas for projects. |
| [**Get Atomic Time from Internet Clock**](Web/AtomicTime) | This program will get the true atomic time from an atomic time clock on the Internet. Use any one of the atomic clocks returned by a simple Google search. |
| [**Fetch Current Weather**](Web/Weather) | Get the current weather for a given zip/postal code. |
| [**Scheduled Auto Login and Action**](Web/AutoLogin) | Make an application which logs into a given site on a schedule and invokes a certain action. |
| [**E-Card Generator**](Web/ECardGenerator) | Make a site that allows people to generate their own little e-cards and send them to other people. Do not use Flash. Use a picture library and perhaps insightful mottos or quotes. |
| [**Content Management System**](Web/CMS) | Create a content management system (CMS) like Joomla, Drupal, PHP Nuke etc. Start small. Open a file and change the title or text or HTML. |
| [**Web Board (Forum)**](Web/WebBoard) | Create a forum for you and your buddies to post, administer and share thoughts and ideas. |
| [**CAPTCHA Maker**](Web/CaptchaMaker) | Ever see those images with letters a numbers when you signup for a service? This is a CAPTCHA. The purpose is to prevent automated programs from signing up and spamming. Create a program to generate them. |

## Files

| Project | Description |
| :--- | :--- |
| [**Quiz Maker**](Files/QuizMaker) | Make an application which takes various questions from a file, picked randomly, and puts together a quiz for students. Each quiz can be different and then reads a key to grade the quizzes. |
| [**Sort Excel/CSV File Utility**](Files/SortUtility) | Reads a file of records, sorts them, and then writes them back to the file. Allow the user to choose various sort style and sorting based on a particular field. |
| [**Create Zip File Maker**](Files/ZipFileMaker) | The user enters various files from different directories and the program zips them up into a zip file. Optional: Apply actual compression to the files. Start with Huffman Coding. |
| [**PDF Generator**](Files/PDFGenerator) | An application which can read in a text file, html file or some other file and generates a PDF file out of it. |
| [**Mp3 Tagger**](Files/Mp3Tagger) | Modify and add ID3v1 tags to MP3 files. See if you can also add in the album art into the MP3 file’s header as well as other ID3v2 tags. |
| [**Code Snippet Manager**](Files/SnippetManager) | Another utility program that allows coders to save functions and classes into a file to load up at a later time. |

## Databases

| Project | Description |
| :--- | :--- |
| [**SQL Query Analyzer**](Databases/SQLQueryAnalyzer) | A utility application which a user can enter a query and have it run against a local database and look for ways to make it more efficient. |
| [**Remote SQL Tool**](Databases/RemoteSQLTool) | A utility that can execute queries on remote servers from your local computer across the Internet. It should take in a remote host, user name and password, run the query and return the results. |
| [**Report Generator**](Databases/ReportGenerator) | Create a utility that generates a report based on some tables in a database. Generates a sales reports based on the order/order details tables or sums up the days current database activity. |
| [**Event Scheduler and Calendar**](Databases/EventScheduler) | Make an application which allows the user to enter a date and time of an event, event notes and then schedule those events on a calendar. The user can then browse the calendar or search the calendar for specific events. |
| [**Budget Tracker**](Databases/BudgetTracker) | Write an application that keeps track of a household’s budget. The user can add expenses, income, and recurring costs to find out how much they are saving or losing over a period of time. |
| [**TV Show Tracker**](Databases/TVShowTracker) | Got a favorite show you don’t want to miss? User inputs various shows and this program checks when the next new episode of that show is scheduled to be aired and reminds you. |
| [**Travel Planner System**](Databases/TravelPlanner) | Make a system that allows users to put together their own little travel itinerary and keep track of the airline / hotel arrangements, points of interest, budget and schedule. |

## Graphics and Multimedia

| Project | Description |
| :--- | :--- |
| [**Slide Show**](Graphics/SlideShow) | Make an application that shows various pictures in a slide show format. Optional: Try adding various effects like fade in/out, star wipe and window blinds transitions. |
| [**Stream Video from Online**](Graphics/VideoStreamer) | Try to create your own online streaming video player. |
| [**Mp3 Player**](Graphics/Mp3Player) | A simple program for playing your favorite music files. Add features in as you think they are needed. |
| [**Watermarking Application**](Graphics/Watermarker) | Have some pictures you want copyright protected? Add your own logo or text lightly across the background so that no one can simply steal your graphics off your site. Make it use a thread so that if you add a 50 pictures all at once it won’t freeze the window. |
| [**Turtle Graphics**](Graphics/TurtleGraphics) | This is a common project where you create a floor of 20 x 20 squares. Using various commands you tell a turtle to draw a line on the floor. You have move forward, left or right, lift or drop pen etc. Do a search for "Turtle Graphics" for more information. |
| [**GIF Creator**](Graphics/GIFCreator) | A program that puts together multiple images (PNGs, JPGs, TIFFs) to make a smooth GIF that can be played back, with optional frame delay and loop count. |

## Security

| Project | Description |
| :--- | :--- |
| [**Caesar cipher**](Security/CaesarCipher) | Implement a Caesar cipher, both encoding and decoding. The key is an integer from 1 to 25. This cipher rotates the letters of the alphabet (A to Z). The encoding replaces each letter with the 1st to 25th next letter in the alphabet (wrapping Z to A). So key 2 encrypts "HI" to "JK", but key 25 encrypts "HI" to "GH". |



---

# ➕ Additional Projects Added (to Reach 100)

To expand the original list to 100 projects, the following additional tools were included:

1. **Password Strength Analyzer**
   Evaluates password security using entropy and pattern detection.

2. **Markdown to HTML Converter**
   Converts Markdown text into styled HTML pages.

3. **URL Metadata Preview Generator**
   Generates preview cards for URLs (similar to social media previews).

4. **JSON Formatter and Validator**
   Validates and formats JSON input with syntax highlighting.

5. **API Latency Tester**
   Measures response time and performance metrics for API endpoints.

---



## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.

### How to Contribute

1. Fork this repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

# 📈 Mission Progress

This repository is being developed incrementally.

Each project includes:

* problem description
* implementation details
* usage instructions
* screenshots (optional)

Progress will be tracked as projects are completed.

---

# 🎯 Final Goal

By completing all 100 projects, this repository will become a **comprehensive collection of FastAPI-based web utilities**, showcasing:

* backend engineering skills
* problem solving ability
* structured development discipline
* modern Python web development

---

## 🙏 Acknowledgments

- **[strange0g](https://github.com/strange0g)** for curating the original [Mega Project List](https://github.com/strange0g/95-python-projects)
- The Python community for excellent documentation and libraries
- All contributors who helped improve these implementations

---

# 🤝 Contributions

Contributions and suggestions are welcome.

To contribute:

1. Fork the repository
2. Create a new branch
3. Implement a project or improvement
4. Submit a pull request

---

# 📜 License

This project is licensed under the **MIT License**.

---

If you want, I can also help you with **two things that will make this repo MUCH stronger**:

1️⃣ A **clean folder architecture for 100 projects** (so it doesn’t become messy)
2️⃣ A **GitHub strategy to make the repo go viral / attract recruiters**.
