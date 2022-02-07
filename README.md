# Python Technical Test 1

This assessment tests your technical skill in Python programming. It also tests your understanding on web service and ability to learn how to use new Python library.

### Web Service Implementation using FastAPI

[FastAPI](https://fastapi.tiangolo.com/) is a web framework for Python like Flask and Django. 

You are tasked to implement a web service with following endpoints using FastAPI.

1. [POST] `/user/register`
  - User register his account with `username`, `full_name`, `password`.

2. [POST] `/user/login`
  - User login his acccount using his `username` and `password`.
  - Upon successful login, the web service will return a JWT token, which user can use it for other API request.  

3. [GET] `/user/profile`
  - User can get his own profile (username and full_name).
  - User needs to send in JWT token for authentication.

### Other Requirements

- [Optional] You can use any database as backend. If database is used, validate JWT token against database too.

### Deliverable

Please create a GitHub repository containing your submission. If you are shortlisted, you will need to give a demo and walk through your code in 2nd interview.

**Dos:**

- Frequent commits
- Descriptive commit messages
- Clear Documentation
- Comments in your code

**Don'ts:**

- Only one commit for all your files
- Submit a zip file
- Sparse or absent documentation
