<p align="center">
<a href="https://dte.devzar.com" target="_blank">
<img src="logo.png" width="400">

<h1 align="center"> Technical Education Board</h1>
<br>
<br>
</a>
</p>

## About DTE API Mangment System

This is a general project API management system for the dynamic data of "DTE Android apps" for all employees information of the Technical Education Board.

<br>
<br>

<h3>API Documentation</h3>
<hr>

-   Fatch All Category Data

    ```
    http://127.0.0.1:8000/api/category
    ```

    -   OR

    ```
    https://dte.devzar.com/api/category
    ```

-   Fatch All institute Data

    ```
    http://127.0.0.1:8000/api/institute
    ```

    -   OR

    ```
    https://dte.devzar.com/api/institute
    ```

    -   if you want to Search institute by category then follow this url

        ```
        http://127.0.0.1:8000/api/institute?category_id=1
        ```

        -   OR

        ```
        https://dte.devzar.com/api/institute?category_id=1
        ```

-   Fatch All Employee Information Data

    ```
    http://127.0.0.1:8000/api/employee-infoemployee-info
    ```

    -   OR

    ```
    https://dte.devzar.com/api/employee-info
    ```

    -   if you wan to Search Employee Information by any key the follow like that

        -   for only key

        ```
        http://127.0.0.1:8000/api/employee-info?key=Rooney
        ```

        -   OR

        ```
        https://dte.devzar.com/api/employee-info?key=Rooney
        ```

        -   for only category

            ```
            http://127.0.0.1:8000/api/employee-info?category_id=1
            ```

            -   OR

            ```
            https://dte.devzar.com/api/employee-info?category_id=1

            ```

        -   for only institute

            ```
            http://127.0.0.1:8000/api/employee-info?institute_id=2
            ```

            -   OR

            ```
            https://dte.devzar.com/api/employee-info?institute_id=2
            ```

        -   for key and category

            ```
            http://127.0.0.1:8000/api/employee-info?key=Rooney&category_id=1
            ```

            -   OR

            ```
            https://dte.devzar.com/api/employee-info?key=Rooney&category_id=1
            ```

        -   for key and institute

            ```
            http://127.0.0.1:8000/api/employee-info?key=Rooney&institute_id=2
            ```

        -   OR

            ```
            https://dte.devzar.com/api/employee-info?key=Rooney&institute_id=2
            ```

        -   for key,category and institute

            ```
             http://127.0.0.1:8000/api/employee-info?key=Rooney&category_id=1&institute_id=2
            ```

            -   OR

            ```
            https://dte.devzar.com/api/employee-info?key=Rooney&category_id=1&institute_id=2
            ```

-   Fatch All Category,institute and Employee info Data

    ```
    http://127.0.0.1:8000/api/employee-info/all
    ```

    -   OR

    ```
    https://dte.devzar.com/api/employee-info/all
    ```

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to IQBAL HASAN via [info@iqbalhasan.dev](mailto:info@iqbalhasan.dev). All security vulnerabilities will be promptly addressed.

## License

The DTW BMDA is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
