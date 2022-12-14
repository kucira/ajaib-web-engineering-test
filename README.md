<h1 align="center">Welcome to ajaib-web-engineering-test 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="#" target="_blank">
    <img alt="License: UNLICENSED" src="https://img.shields.io/badge/License-UNLICENSED-yellow.svg" />
  </a>
  <a href="https://twitter.com/ikhlassandy" target="_blank">
    <img alt="Twitter: ikhlassandy" src="https://img.shields.io/twitter/follow/ikhlassandy.svg?style=social" />
  </a>
</p>

> This project is about Ajaib Web engineering test, a simple project to fetch fake API to show user table data with functionality of search, filter, sort, reset fiilter, pagination. This project have unit test with minimal test.

> Tech stack :
- ReactJS & NextJS
- Ant Design
- React Query
- Axios
- Typescript
- CSR (Client Side Rendering)
- Jest
- Testing library react
- mswjs (mock network request to API)
- State management using React Query, Query Params

> Pages :
- Login Page (input any email & password) it will save into cookies
- Dashboard Page (this is the list of data from fake api)


>  Folder Structure :
Based on feature domain drive, every pages will have feature folder and from feature folder will have separate logic, separate view, separate model etc.

> Better Web Perfomance using React Query, it will cache the response of API, so if the network request hit the same endpoint and still have the cache, it will show the cache data from react query and will refresh the data if the cache became stall.

[![](https://lh5.googleusercontent.com/DAk-hJSfzBbkbhlZyBpuXfNiQ8XS82M3iUxIRk96bhM1yiSN5x2ld86QqlSX-a2hi-tugpfNM3CoCPVM2CR3=w1920-h968)](https://lh5.googleusercontent.com/DAk-hJSfzBbkbhlZyBpuXfNiQ8XS82M3iUxIRk96bhM1yiSN5x2ld86QqlSX-a2hi-tugpfNM3CoCPVM2CR3=w1920-h968)

[![Dashboard](https://lh3.googleusercontent.com/fife/AAbDypBxpS0pQ-c6qRSKYH0TmU4W11xubEc8NjIrzsj9zrbbCE2x2uy8PKaYsEl95bbZsfGEVg_86lFv_yX1zORreAi5vYcQX2wptFd4S1rsGgavY3H3H0SnRG8NGeZOyDfHnza_IjbjF2wO6CkTLYFnONxVUGRzt_4IiRdrbAgcPTscoLQxWTCHX8LSbqOZdXXG58JErOAJkOA0XD447CKUkJraeWfU1F31XNWEzxtGgMZCPI7H3CDq-g3D-wT_D_7X8-TP2eGqaBwsD6_ID7KhIwtQOP6ivWIjuy8FsmUzmxBQudcLaYgQzcK-pEVFy3fbKIijooiPiMYne8GzdTYxtlSblCywjY5rYtgQwbl4J5gFdHfjD_0NjsmWmMVMCBfFVicnkTl10rjyl-A93M6nQUCkXwvlh7xVpWwV9zZoW4qcdzRcm8ylOFtst05_tepOYXKh-la-vPGps_N0d7tBrVqEpXvIrvJMIY4GclxD1UCmLLQYgA4S36sFsXHhb5KU5PgHireuC1U0H3l4S4LfIOrlnXqa4xBCccKCq7DLp7RJeHHTyw32FVZfJ_QREUIXilF1YOUcH_ZPZTPjFLRaM70ylio-sHY0hnEFyVzOQtNRXApDVi18n_zxb6jX_9LLsP2OLdsAiE7cW_GA1XqoiZUC-wuWPWyDEW6t90BYsiIY7BbWkqmPCrEG-bQEKPreItr1LrKQJr4lov92dXRkN6MYsjoYZFUzZxXIPzQ9xkZ3ehIy4MZ_8oSxT6EZOmCgd1fNaksXNczq1PSvTCIQH9jo-CKmFHkZ-WPzWF0y3sHQypGoFfD8VaPAC5bGPc1_18CgNESk-34w-DEhYvxpvHnr2I8XvbehpxsDKVmNb9a14rVqcnU-bfW8Uy_qcO9nzJ--lveNYJ23IDVrXKfBih0DNZgmRStDLeqL4EffV88wCIP0532fRyHNcEYq66wICqGL5KmuQsLXH_1rHz7t5f7eqLH2JS-lRCUYMcjCogilRThr-kUiVL5uwT71riZVHdjDA7ZMNp5toinluQcSsWOFyh9tu9Zc1T3ZncTqs_Rl09Wvsjq0suziEd3bk5vb19IraWDfE9VLWlFKFdXQrSmtQVVbw5pFBwxOBKRdTtj5rWuBCju7UdqEaQ7xBMBRniqBYPC6QF9BS7MzG7jZU1bVasHr1bbnAt8t90CCFHPlDllx8inFzAyazIu3cHOHoVFdk-wW_WJWRbvKDnrTnj7EsA0ubn9WDJIjgWWDJTqSSu75C8lQjZOk7YQSEowGgrYmz22ivg=w1920-h968 "Dashboard")](https://lh3.googleusercontent.com/fife/AAbDypBxpS0pQ-c6qRSKYH0TmU4W11xubEc8NjIrzsj9zrbbCE2x2uy8PKaYsEl95bbZsfGEVg_86lFv_yX1zORreAi5vYcQX2wptFd4S1rsGgavY3H3H0SnRG8NGeZOyDfHnza_IjbjF2wO6CkTLYFnONxVUGRzt_4IiRdrbAgcPTscoLQxWTCHX8LSbqOZdXXG58JErOAJkOA0XD447CKUkJraeWfU1F31XNWEzxtGgMZCPI7H3CDq-g3D-wT_D_7X8-TP2eGqaBwsD6_ID7KhIwtQOP6ivWIjuy8FsmUzmxBQudcLaYgQzcK-pEVFy3fbKIijooiPiMYne8GzdTYxtlSblCywjY5rYtgQwbl4J5gFdHfjD_0NjsmWmMVMCBfFVicnkTl10rjyl-A93M6nQUCkXwvlh7xVpWwV9zZoW4qcdzRcm8ylOFtst05_tepOYXKh-la-vPGps_N0d7tBrVqEpXvIrvJMIY4GclxD1UCmLLQYgA4S36sFsXHhb5KU5PgHireuC1U0H3l4S4LfIOrlnXqa4xBCccKCq7DLp7RJeHHTyw32FVZfJ_QREUIXilF1YOUcH_ZPZTPjFLRaM70ylio-sHY0hnEFyVzOQtNRXApDVi18n_zxb6jX_9LLsP2OLdsAiE7cW_GA1XqoiZUC-wuWPWyDEW6t90BYsiIY7BbWkqmPCrEG-bQEKPreItr1LrKQJr4lov92dXRkN6MYsjoYZFUzZxXIPzQ9xkZ3ehIy4MZ_8oSxT6EZOmCgd1fNaksXNczq1PSvTCIQH9jo-CKmFHkZ-WPzWF0y3sHQypGoFfD8VaPAC5bGPc1_18CgNESk-34w-DEhYvxpvHnr2I8XvbehpxsDKVmNb9a14rVqcnU-bfW8Uy_qcO9nzJ--lveNYJ23IDVrXKfBih0DNZgmRStDLeqL4EffV88wCIP0532fRyHNcEYq66wICqGL5KmuQsLXH_1rHz7t5f7eqLH2JS-lRCUYMcjCogilRThr-kUiVL5uwT71riZVHdjDA7ZMNp5toinluQcSsWOFyh9tu9Zc1T3ZncTqs_Rl09Wvsjq0suziEd3bk5vb19IraWDfE9VLWlFKFdXQrSmtQVVbw5pFBwxOBKRdTtj5rWuBCju7UdqEaQ7xBMBRniqBYPC6QF9BS7MzG7jZU1bVasHr1bbnAt8t90CCFHPlDllx8inFzAyazIu3cHOHoVFdk-wW_WJWRbvKDnrTnj7EsA0ubn9WDJIjgWWDJTqSSu75C8lQjZOk7YQSEowGgrYmz22ivg=w1920-h968 "Dashboard")

[![Dashboard](https://lh3.googleusercontent.com/fife/AAbDypDuSkPlK309a8O3LnF0jEaxhU0fXyK139A80qvVV7libGNpKk268jgifu5DrDeAGOZ-kBWWhoLdxIiXE3FUFcvsBj2AHhpv3AhWuBqPXk2kMgROxgagZt5yg6oIIPNDc7mtwEA72j2JvZrWy5CbomsqgoxfKlnZ6z0BgNwlk7NebgOZTxHN_x5NUB6DqOmHelqQYiLe6h4qp2NT4iRLe7N7j4wJ_P_PKsKXJE-6Tb3pXuGuVsN2D9aS5t39bZFIjWVLH0z-9qmNZV6Jv84eJayGO0MCSqQQ5gbdiklzTb-qzh2zuU5ydQTIb0xRTe_vWM0I3fXql_RBFpUjjcMcxa_okry5YhlmYWZQxY0_Xhp0KyoYZKsjcs9q1pOBKzsiiWIXLxxrNeBcN3_o9lsqfOCKNlITnNV396pDXpE8KDGOMyC7hqmLduYN0ZAluAyOSuhgz9PD1pgY2ezwXB3fGx-aZgTs81IwQUIg8W8ge1bT9f5mEFhOAeKboQH0YDaUszI_5rISLCi_vFVOWh-84B4cxqQfmfbrpm2m1lAv0CLOiuhnidQpmEraEQDmAQLy-f4cKaFZF_D86UcTB2XvEoUfEJfraCnfymk-VE7TfAVk56jdxVs2bfhz-vaMugu1io2ETt2kSL5pyD0yVAJXI6fzU0VbZGHsprTi0ipMO_uricf70CdimeDe4TLxlj2Diw8Isa2OOPL9B5k3G474V2aFafPCR7GGVlA7QZUOIzKY6t0uLEYSj1WpK6xu0NyNGCM8k39JlAA0MpYhTbaUFewxpkWFXpqrIagwCderDR1jfOxvoHKAj7Prd-p0vihUNb-goUuYQ2EMYa8Cnmam0Q_EQD4S3wUTmm94xmeXcbW7ScUqOYsJ8Xrr5QScKSVPiPOA0EQnRGI0a5lONwUBQztlTERK8QSzfaee4zeMKxZ2slwFH-qPMPSWlx61F1jDOsF6nMWfZK0IrX9082suSjb_SJadhfvup2RFBw59Nw53e8uw-a7TQAnS6awLdYeYnZ5P3PZLmi1NXRim0rFougCA3fxMDnTdA0FHWReDbrmePTv89vkQLB6Ijg3vtkPn3AzTN5yiLJGASA3r0NN8ukV2hb5rJTOPSOPKPU3JzdVOj91pb1Km2M42AbeVLKhvzhzgzVZnO4eoAgREEAKUFUum2X2aoD2996kHDofB4vWDL2bT9HE7eySYqu6UIf1v6bRQto1GrWW2h46zw6jq9QZNZ9q_UJNjKfqkOgh2KtVAH22DC-Cksn20QWMy3u4dj54F6PmO1w=w1920-h636 "Dashboard")](https://lh3.googleusercontent.com/fife/AAbDypDuSkPlK309a8O3LnF0jEaxhU0fXyK139A80qvVV7libGNpKk268jgifu5DrDeAGOZ-kBWWhoLdxIiXE3FUFcvsBj2AHhpv3AhWuBqPXk2kMgROxgagZt5yg6oIIPNDc7mtwEA72j2JvZrWy5CbomsqgoxfKlnZ6z0BgNwlk7NebgOZTxHN_x5NUB6DqOmHelqQYiLe6h4qp2NT4iRLe7N7j4wJ_P_PKsKXJE-6Tb3pXuGuVsN2D9aS5t39bZFIjWVLH0z-9qmNZV6Jv84eJayGO0MCSqQQ5gbdiklzTb-qzh2zuU5ydQTIb0xRTe_vWM0I3fXql_RBFpUjjcMcxa_okry5YhlmYWZQxY0_Xhp0KyoYZKsjcs9q1pOBKzsiiWIXLxxrNeBcN3_o9lsqfOCKNlITnNV396pDXpE8KDGOMyC7hqmLduYN0ZAluAyOSuhgz9PD1pgY2ezwXB3fGx-aZgTs81IwQUIg8W8ge1bT9f5mEFhOAeKboQH0YDaUszI_5rISLCi_vFVOWh-84B4cxqQfmfbrpm2m1lAv0CLOiuhnidQpmEraEQDmAQLy-f4cKaFZF_D86UcTB2XvEoUfEJfraCnfymk-VE7TfAVk56jdxVs2bfhz-vaMugu1io2ETt2kSL5pyD0yVAJXI6fzU0VbZGHsprTi0ipMO_uricf70CdimeDe4TLxlj2Diw8Isa2OOPL9B5k3G474V2aFafPCR7GGVlA7QZUOIzKY6t0uLEYSj1WpK6xu0NyNGCM8k39JlAA0MpYhTbaUFewxpkWFXpqrIagwCderDR1jfOxvoHKAj7Prd-p0vihUNb-goUuYQ2EMYa8Cnmam0Q_EQD4S3wUTmm94xmeXcbW7ScUqOYsJ8Xrr5QScKSVPiPOA0EQnRGI0a5lONwUBQztlTERK8QSzfaee4zeMKxZ2slwFH-qPMPSWlx61F1jDOsF6nMWfZK0IrX9082suSjb_SJadhfvup2RFBw59Nw53e8uw-a7TQAnS6awLdYeYnZ5P3PZLmi1NXRim0rFougCA3fxMDnTdA0FHWReDbrmePTv89vkQLB6Ijg3vtkPn3AzTN5yiLJGASA3r0NN8ukV2hb5rJTOPSOPKPU3JzdVOj91pb1Km2M42AbeVLKhvzhzgzVZnO4eoAgREEAKUFUum2X2aoD2996kHDofB4vWDL2bT9HE7eySYqu6UIf1v6bRQto1GrWW2h46zw6jq9QZNZ9q_UJNjKfqkOgh2KtVAH22DC-Cksn20QWMy3u4dj54F6PmO1w=w1920-h636 "Dashboard")

## Demo URL
https://ajaib-web-engineering-test.vercel.app/dashboard
Login with any email & password
ex :
email :  test@mail.com
pass : test

## Install

```sh
yarn install
```

## Usage

```sh
create .env file
copy from env.local.example to .env file
yarn run dev
```

## Run tests

```sh
yarn run test
```

## Author

👤 **Ikhlas Risandy**

* Website: https://www.ikhlas-risandy.my.id/
* Twitter: [@ikhlassandy](https://twitter.com/ikhlassandy)
* Github: [@kucira](https://github.com/kucira)
* LinkedIn: [@https://www.linkedin.com/in/ikhlas-risandy-a8b4a552/](https://linkedin.com/in/https://www.linkedin.com/in/ikhlas-risandy-a8b4a552/)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_