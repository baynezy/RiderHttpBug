# Rider HTTP Client Bug

## Instructions

1. Open the project in Rider version 2024.1.6
2. Open `requests.http` file
3. Click on the `GET` request
4. IDE runs query as expected
5. Open the project in Rider version 2024.2
6. Open `requests.http` file
7. Click on the `GET` request
8. IDE reports error: `Invalid request because of unsubstituted variable 'query.value' at C:\_development\afterlife\RiderHttpBug\requests\requests.http:2:40`

## References

This has been reported in bug [IJPL-160392](https://youtrack.jetbrains.com/issue/IJPL-160392)
