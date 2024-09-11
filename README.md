# Python Interview Questions
--------------------------

[InterviewBit Python Interview Questions](https://www.interviewbit.com/python-interview-questions/)  
Covers all basic to intermediate level interview questions for Python, OOP, Pandas, NumPy, and library-related questions.

### Mostly Asked:
- **Lambda functions**  
- **Decorators**  
- **Generators**  
- Multi-Threading, Multi-Processing - [YouTube Video](https://www.youtube.com/watch?v=PJ4t2U15ACo&list=PLeo1K3hjS3uub3PRhdoCTY8BxMKSW7RjN)

** - Implement  
* - Theoretical

### Additional Topics:
- Handling files in Python
- JSON, YAML, .env file operations
- Flattening a dict using a recursive approach
- Flattening a list using different methods
- Error/Exception handling in Python

### Pandas:
- **Basic Pandas inbuilt functions:** `dropna`, `fillna`, grouping, merging  
- **Intermediate level:** `apply`, `applymap`, `map`, `interpolate`, using lambda functions, time series modifications.

### Sample Implementations:
- JSON handling
- Requests library usage
- Beautiful Soup for web scraping
- Classes, Objects, Access Modifiers, Inheritance

# Coding Question Topics:
-----------------------
Mostly LeetCode easy-level questions and some common medium-level questions.

### Array and List Operations
- Find the second largest digit
- Find digits with K more occurrences
- Find possible pairs whose sum equals the target

### String Operations
- Find the first repeating character in a string and return the index
- Find the longest substring with non-repeating characters
- Find the longest palindromic substring
- Validate parentheses
- Longest common prefix

Some interviews may include DSA topics like implementing a basic linked list, stack, or queue.

### Better to Learn Approaches:
- Two-pointer
- Sliding window
- At least 3-4 sorting techniques (one with better than O(n²))
- Binary search

For SDE roles, grinding LeetCode might be necessary.  
[Interview Practice Repo](https://github.com/krishnamurthy-srinivasan/interview_practice/tree/main/personal-practice) - Pull and contribute any new questions.

# REST API Interview Questions
----------------------------
- [Basic - YouTube](https://youtu.be/-mN3VyJuCjM?si=5fr8KnDIxtLqO_Pk)  
- [InterviewBit - REST API Interview Questions](https://www.interviewbit.com/rest-api-interview-questions/)

### Commonly Asked Status Codes:
- **1xx** - Informational responses
- **2xx** - Successful responses
- **3xx** - Redirects
- **4xx** - Client errors
- **5xx** - Server errors

#### Most Common Status Codes:
- `200` - Success/OK
- `201` - Created (used in POST or PUT methods)
- `304` - Not Modified (conditional GET requests)
- `400` - Bad Request (validation errors or missing data)
- `401` - Unauthorized (invalid authentication credentials)
- `403` - Forbidden (no access to resource)
- `404` - Not Found (resource/method unavailable)
- `500` - Internal Server Error
- `502` - Bad Gateway (response failure from an upstream server)

[HTTP Status Codes Reference](https://www.w3schools.com/tags/ref_httpmessages.asp)

# FastAPI:
---------
- [Starlette](https://www.starlette.io/)
- [Pydantic Validations](https://docs.pydantic.dev/latest/)
- JWT, Authentication, and Authorization flows
- SQLiteDB, Postgres
- SQLAlchemy with DB
- All CRUD operations
- File handling in FastAPI
- Routers, tags
- ASGI vs WSGI
- Async, Await, Event Loops

### Resources:
- [Learning FastAPI End-to-End](https://www.fastapitutorial.com/blog/what-are-we-going-to-build/)
- [SQLAlchemy with Postgres](https://youtu.be/398DuQbQJq0?si=BPrKkmpRjaTul8wb)
- [JWT OAuth2](https://youtu.be/0A_GCXBCNUQ?si=5usNy1pJYsfLwJhb)
- [File Handling in FastAPI](https://youtu.be/m6Ma6B6VlFs?si=u4vUY34p4TaGWI1J)
- [Complete FastAPI Playlist](https://www.youtube.com/watch?v=8SdR5i3ZoqE&list=PLK8U0kF0E_D6l19LhOGWhVZ3sQ6ujJKq_)

For a fast learning/revision setup:  
[FastAPI Setup Repo](https://github.com/krishnamurthy-srinivasan/FastAPI-PgSQL-SQLAchemy-Oauth2-JWT-Filehandling)

# Pytest
------
Rarely asked in interviews, but you may be asked if you’ve written unit tests and which package you used. Basics are enough.  
[Pytest Basics - YouTube](https://youtu.be/jM-zWp8dNQA?si=f_Bl_T4ftaLyXKmY)
