### Hi there 👋, this is Xuhua
I consider myself to be a highly-motivated self-learner; various repositories contain all ~~self-taught~~ code written along the way.  

<!-- Logo -->
[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://gist.github.com/XuhuaHuang/starred)
[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>][LinkedIn Profile Link] 

✔ Self learner and quick learner craving for in-depth knowledge and challenges.  
✔ Strong passion in Embedded Software Development with C/C++, Python and Rust.  
✔ **Embedded Software Development** || Design || Analysis with advanced mathematics.  

### Recent Coding Activities
<!--START_SECTION:waka-->

```text
From: 28 March 2022 - To: 04 April 2022

Rust       57 hrs 43 mins  ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣶   98.91 %
C++        27 mins         ⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   00.78 %
Makefile   5 mins          ⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   00.16 %
Markdown   4 mins          ⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   00.14 %
TOML       0 secs          ⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   00.01 %
C          0 secs          ⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   00.00 %
```

<!--END_SECTION:waka-->

---

<!-- Fold Information Section -->
<details>
  <summary><b>Skills and badges</b></summary>
  
  #### Skills
  * 💻 C / C++ / Python
  * 🖥️ Rust / Cython / Java
  * ⌨️ Object-Oriented Programming
  * 🗃️ SQL / MySQL

  #### LinkedIn Skill Assessment Badges
  * ✒️ [C++ Programming][LinkedIn Profile Link]
  * ✒️ [Python Programming][LinkedIn Profile Link]
  * ✒️ [Object-Oriented Programming][LinkedIn Profile Link]
  * ✒️ [Object-Oriented Data Structures in C++][OO Data Structures C++]

  #### Recently Obtained Badges
  [<img src="https://images.credly.com/size/220x220/images/ba34cb1c-4344-43f5-9685-55e2e901c0f0/Data_Analysis_using_Python.png"
        alt="Data Analysis Using Python" width="130" height="130">][Data Analysis using Python]
  [<img src="https://images.credly.com/size/680x680/images/84ac9eff-b8a2-4683-846b-f59887a73801/Python_101_Data_Science.png"
        alt="Python for Data Science" width="130" height="130">][Python for Data Science]
</details>

<!-- Link Definitions -->
[LinkedIn Profile Link]: https://www.linkedin.com/in/xuhua-huang-io/
[OO Data Structures C++]: https://coursera.org/share/94edd41bd7533bffc5d01463b00a32cb
[Data Analysis using Python]: https://www.credly.com/badges/a79dd6e0-e8fe-45e6-a7d3-25bc8eaf2f04/public_url
[Python for Data Science]: https://www.credly.com/badges/57932d92-7a5a-4dee-95f9-a50237374199/public_url

<details>
  <summary><b>More about me</b></summary>

  - 🔭 I’m currently working on leanring OpenCV4 with Python3 and Qt5. 
  - 🌱 I’m currently learning Rust.
  - 📤 Most used line of code `git commit -m "Initial Commit"`.
  - 🤔 I’m looking for help with advanced Python and Machine Learning.
  - 📫 How to reach me: xuhua.huang.io@gmail.com
  - ⚡ Fun fact: code blooded animal `std::code_blooded`.
</details>

<details>
  <summary><b>GitHub profile status</b></summary>
  
  <!-- Overall -->
  #### Overview  
  ![Visitors](https://visitor-badge.glitch.me/badge?page_id=page.id)
  ![Profile views](https://gpvc.arturio.dev/XuhuaHuang)

  <!-- Languages -->
  #### Top Languages
  <!-- Link Definitions -->
  [Top Langs Link API]: https://github-readme-stats.vercel.app/api/top-langs/?username=XuhuaHuang&layout=compact&theme=solarized-dark&title_color=90d0e4&text_color=89d7a9
  [![Top Langs][Top Langs Link API]](https://github.com/anuraghazra/github-readme-stats)
  
  <!-- Wakatime profile -->
  #### Summary of Coding Activities
  <!-- Link Definitions -->
  [Wakatime Stats Link API]: https://github-readme-stats.vercel.app/api/wakatime?username=XuhuaHuang&layout=compact&theme=solarized-dark&title_color=90d0e4&text_color=89d7a9
  [![Xuhua's wakatime stats][Wakatime Stats Link API]](https://github.com/anuraghazra/github-readme-stats)
</details>

<details>
  <summary><b>I ❤️ Modern C++</b></summary>
  
  ```C++
  /*****************************************************************//**
  * \file   trimstr.hpp
  * \brief  Demonstration of handy constant expressions that trim
  *         `std::string` at compile time with `std::ranges`
  *
  * $ g++ trimstr.hpp -o trimstr.o -std=c++23 -Wall -Wextra -Wpedantic
  *
  * \author Xuhua Huang
  * \date   March 2022
  *********************************************************************/

  #if defined __has_include
  #if __has_include(<ranges>) && __has_include(<string>)
  #include <ranges>
  #include <string>
  #else
  #error "Require std::ranges and std::string library!"
  #endif
  #endif

  inline constexpr auto trim_front = std::views::drop_while(::isspace);
  inline constexpr auto trim_back = std::views::reverse
      | std::views::drop_while(::isspace)
      | std::views::reverse;

  inline constexpr auto trim_spaces = trim_front | trim_back;

  std::string trim_str(const std::string& str) {
      // std::rangesnext::to in C++23 proporsal
      // htat converts ranges to a containter
      return str | trim_spaces | std::rangesnext::to<std::string>;
  }
  ```
</details>
