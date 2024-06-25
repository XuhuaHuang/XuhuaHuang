### Hi there 👋, this is Xuhua

[![wakatime](https://wakatime.com/badge/user/f89598ea-6723-481b-a51b-6323e54a3c5c.svg)](https://wakatime.com/@f89598ea-6723-481b-a51b-6323e54a3c5c)
<!--START_SECTION:waka-->

```txt
From: 24 May 2024 - To: 23 June 2024

Total Time: 316 hrs 7 mins

C++           157 hrs 46 mins >>>>>>>>>>>>-------------   49.91 %
Python        111 hrs 34 mins >>>>>>>>>----------------   35.29 %
Other         13 hrs 41 mins  >------------------------   04.33 %
CMake         13 hrs 39 mins  >------------------------   04.32 %
Markdown      5 hrs 56 mins   -------------------------   01.88 %
```

<!--END_SECTION:waka-->

<p align="left">
    <a href="https://github.com/XuhuaHuang/EmbeddedProgramming"> <img src="https://skillicons.dev/icons?i=arduino,c,cpp,cmake,qt" /> </a>
    <br>
    <a href="https://github.com/XuhuaHuang/LearnPython"> <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,opencv,matlab" /> </a>
</p>

<!-- Fold Information Section -->
<details>
  <summary><b>Skills and badges</b></summary>
  
  #### Skills
  * 💻 C / C++ / Python
  * 🖥️ Rust / Cython / Java
  * 🗃️ Object-Oriented Programming

  #### LinkedIn Skill Assessment Badges
  * ✒️ [C++ Programming][LinkedIn Profile Link]
  * ✒️ [Python Programming][LinkedIn Profile Link]
  * ✒️ [Object-Oriented Programming][LinkedIn Profile Link]
  * ✒️ [Object-Oriented Data Structures in C++][OO Data Structures C++]

  #### Recently Obtained Badges
  [<img src="https://images.credly.com/size/340x340/images/73ac7b07-679c-4c0e-94d9-8b9dc11efe59/Applied_Data_Science_with_Python.png"
        alt="Applied Data Science with Python - Level 2" width="130" height="130">][Applied Data Science with Python - Level 2]
  [<img src="https://images.credly.com/size/340x340/images/087eaefb-61a2-426b-ae74-74efca195667/Data_Visualization_Using_Python.png"
        alt="Data Visualization using Python" width="130" height="130">][Data Visualization using Python]
  [<img src="https://images.credly.com/size/220x220/images/ba34cb1c-4344-43f5-9685-55e2e901c0f0/Data_Analysis_using_Python.png"
        alt="Data Analysis Using Python" width="130" height="130">][Data Analysis using Python]
  [<img src="https://images.credly.com/size/680x680/images/84ac9eff-b8a2-4683-846b-f59887a73801/Python_101_Data_Science.png"
        alt="Python for Data Science" width="130" height="130">][Python for Data Science]
</details>

<!-- Link Definitions -->
[LinkedIn Profile Link]: https://www.linkedin.com/in/xuhua-huang-io/
[OO Data Structures C++]: https://coursera.org/share/94edd41bd7533bffc5d01463b00a32cb
[Applied Data Science with Python - Level 2]: https://www.credly.com/badges/40332475-a724-4b55-a6d0-b44b3e0e882b/public_url
[Data Visualization using Python]: https://www.credly.com/badges/32ad0258-5283-4319-9023-bf87f36badc1/public_url
[Data Analysis using Python]: https://www.credly.com/badges/a79dd6e0-e8fe-45e6-a7d3-25bc8eaf2f04/public_url
[Python for Data Science]: https://www.credly.com/badges/57932d92-7a5a-4dee-95f9-a50237374199/public_url

<details>
  <summary><b>More about me</b></summary>

  - 🔭 I’m currently working on learning OpenCV4 with Python3 and Qt5. 
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
  <!-- Languages -->
  #### Top Languages
  <!-- Link Definitions -->
  ![XuhuaHuang's Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=XuhuaHuang&theme=vue-dark&show_icons=true&hide_border=true&layout=compact)
  
  <!-- Wakatime profile -->
  #### Summary of Coding Activities
  <!-- Link Definitions -->
  ![XuhuaHuang's Stats](https://github-readme-stats.vercel.app/api?username=XuhuaHuang&theme=vue-dark&show_icons=true&hide_border=true&count_private=true)

  ![XuhuaHuang's Streak](https://github-readme-streak-stats.herokuapp.com/?user=XuhuaHuang&theme=vue-dark&hide_border=true)

</details>

<details>
  <summary><b> ❤️ Modern C++</b></summary>
  
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
      // std::rangesnext::to in C++23 proposal
      // that converts ranges to a container
      return str | trim_spaces | std::rangesnext::to<std::string>;
  }
  ```
</details>
