## <div align="center"> Google Search

#### <div align="center">📚 _CS50 Web Project # 0 (Week 1 - 3) 10/03-05/2021_ </div>

**_<p align="right">By Daniel Adeyemi_**</p>

<p align="center">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="30" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="30"/>
<img alt="MySQL" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mysql/mysql.png" /> 
</p>
<div align="center">

![GitHub last commit (branch)](https://img.shields.io/github/last-commit/DanielAdeyemi/ParksLookup.Solution/main?color=purple&style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/DanielAdeyemi/ParksLookup.Solution?color=purple&style=for-the-badge) ![Languages](https://img.shields.io/github/languages/top/DanielAdeyemi/ParksLookup.Solution?color=purple&style=for-the-badge)

</div>
<img src="https://cdn.cheapism.com/images/National_Park_Photos.2e16d0ba.fill-1440x605.png" alt="Lake view"/>

## 🚩 _Description:_

#### **\*\***

<hr>
<summary><h3>📋 Project Specifications </h3></summary>
<details>

|  #  |     Block      |                                                                                                             Task Description                                                                                                              | Completed |
| :-: | :------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------: |
|  1  |     Pages      |                                                         should have at least three pages: one for Google Search, one for Google Image Search, and one for Google Advanced Search                                                          |           |
|  2  |     Pages      |                                                                       on the main page should be links in the upper-right to go to Image Search or Advanced Search                                                                        |           |
|  3  |     Pages      |                                                                    on Image Search and Advanced Search should be a link in the upper-right to go back to Google Search                                                                    |           |
|  4  |   Query Text   |                                           On the Google Search page, the user should be able to type in a query, click “Google Search”, and be taken to the Google search results for that page                                           |           |
|  5  |  Query Images  |                                     On the Google Image Search page, the user should be able to type in a query, click a search button, and be taken to the Google Image search results for that page                                     |           |
|  6  | Query Advanced |                                               On the Google Advanced Search page, the user should be able to provide input for the following field: "find pages with **all these words** "                                                |           |
|  7  | Query Advanced |                                          On the Google Advanced Search page, the user should be able to provide input for the following field: "find pages with **this exact word or phrase** "                                           |           |
|  8  | Query Advanced |                                              On the Google Advanced Search page, the user should be able to provide input for the following field: "find pages with **any of these words** "                                              |           |
|  9  | Query Advanced |                                             On the Google Advanced Search page, the user should be able to provide input for the following field: "find pages with **none of these words** "                                              |           |
| 10  |   Appearance   |                                                 Like Google’s own Advanced Search page, the four options should be stacked vertically, and all of the text fields should be left aligned                                                  |           |
| 11  |   Appearance   |            Consistent with Google’s own CSS, the “Advanced Search” button should be blue with white text. When the “Advanced Search” button is clicked, the user should be taken to search results page for their given query             |           |
| 12  |     Lucky      | Add an “I’m Feeling Lucky” button to the main Google Search page. Consistent with Google’s own behavior, clicking this link should take users directly to the first Google search result for the query, bypassing the normal results page |           |
| 13  |   Aesthetics   |                                                                                       CSS should match Google’s own aesthetics as best as possible                                                                                        |           |

</details>
<summary> <h3>🛸 Search Documentation</h3></summary>

#### **HTTP Request Structure:**

```
GET /api/parks
GET /api/parks/{id}

```

#### **Path Parameters:**

| Parameter |  Type  | Default | Required | Description                                                                                      |
| :-------: | :----: | :-----: | :------: | ------------------------------------------------------------------------------------------------ |
| ParkName  | string |  none   |  false   | Return matches by name.                                                                          |
| Location  | string |  none   |  false   | Return matches by location (check note below for comma separated locations such `Portland, OR`). |
| National  |  bool  |  none   |  false   | Return all parks marked as **National**                                                          |
|   Local   |  bool  |  none   |  false   | Return all parks marked as **Local**                                                             |

_⚠️ Note: for comma-separated locations, such `Portland, OR` use following path:_

```
?location=portland%2C%20or
```

#### **Example Query:**

```
http://localhost:5000/api/parks/?location=portland%2C%20or&local=true
```

## 🛠️ _Technologies used:_

- HTML 5
- CSS 3
- Bootstrap v5.0
- Git and GitHub

## 🖥️ View the project:

## 🐛 _Known bugs:_

## 🌟 _Improvement opportunities:_

## 📬 Contact Information

#### For any questions _[email author](mailto:adeyemidany+github@gmail.com?subject=[GitHubAPI])_

## 📘 _License and copyright:_

> **_© Daniel Adeyemi, 2021_**  
> ⚖️ _[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)_
