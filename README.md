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
C++          35 hrs 48 mins  ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⣀⣀⣀⣀⣀⣀⣀⣀⣀   62.03 %
Python       11 hrs 52 mins  ⣿⣿⣿⣿⣿⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   20.58 %
C            8 hrs 2 mins    ⣿⣿⣿⣦⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   13.93 %
Markdown     1 hr 5 mins     ⣦⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   01.88 %
Rust         21 mins         ⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   00.63 %
PowerShell   17 mins         ⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   00.49 %
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
  [<img src="https://images.credly.com/size/220x220/images/ba34cb1c-4344-43f5-9685-55e2e901c0f0/Data_Analysis_using_Python.png" alt="Data Analysis Using Python" width="130" height="130">][Data Analysis using Python]
  [<img src="https://images.credly.com/size/680x680/images/84ac9eff-b8a2-4683-846b-f59887a73801/Python_101_Data_Science.png" alt="Python for Data Science" width="130" height="130">][Python for Data Science]
</details>

<!-- Link Definitions -->
[LinkedIn Profile Link]: https://www.linkedin.com/in/xuhua-huang-io/
[OO Data Structures C++]: https://coursera.org/share/94edd41bd7533bffc5d01463b00a32cb
[Data Analysis using Python]: https://www.credly.com/badges/a79dd6e0-e8fe-45e6-a7d3-25bc8eaf2f04/public_url
[Python for Data Science]: https://www.credly.com/badges/57932d92-7a5a-4dee-95f9-a50237374199/public_url

<details>
  <summary><b>More about me</b></summary>
  
  - 🔭 I’m currently working on enhancing Python skills. 
  - 🌱 I’m currently learning Rust.
  - 📤 Most used line of code `git commit -m "Initial Commit"`
  - 🤔 I’m looking for help with advance Python and Machine Learning.
  - 📫 How to reach me: xuhua.huang.io@gmail.com
  - ⚡ Fun fact: code blooded animal.
</details>

<details>
  <summary><b>GitHub profile status</b></summary>
  
  <!-- Overall -->
  #### Overview  
  ![Visitors](https://visitor-badge.glitch.me/badge?page_id=page.id)
  ![Profile views](https://gpvc.arturio.dev/XuhuaHuang)
  
  <!-- Languages -->
  #### Top Languages
  [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=XuhuaHuang&layout=compact&theme=vue-dark)](https://github.com/anuraghazra/github-readme-stats)
  
  <!-- Wakatime profile -->
  #### Summary of Coding Activities
  [![Xuhua's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=XuhuaHuang&layout=compact&theme=vue-dark)](https://github.com/anuraghazra/github-readme-stats)
</details>

<details>
  <summary><b>I ❤️ Modern C++</b></summary>
  
  ```C++
  #include<iostream>
  #include<list>
  #include<string>

  #ifndef DEBUG
  #define DEBUG(arg_str) std::cout << arg_str << std::endl;
  #endif

  inline constexpr auto trim_front = views::drop_while(::isspace);
  inline constexpr auto trim_back = views::reverse
    | views::drop_while(::isspace)
    | views::reverse;

  inline constexpr auto trim = trim_front | trim_back;

  std::string trim_str(const std::string& str) {
    return str | trim | rangesnext::to<std::string>;
  }
  
  namespace util::list {

      /* Template to print a std::list with O(n). */
      /* For sanity, using constant reference instead of iterators. */
      template<typename T>
      static void print_list(std::list<T> arg_list) {
          DEBUG("\n[fn]util::list::print_list");

          /* Loop through the vector with iterator. */
          typename std::list<T>::iterator iter; // keyword "typename" is required for iterator
          for (iter = arg_list.begin(); iter != arg_list.end(); ++iter)
              std::cout << *iter << ", "; // dereference the iterator to print content

          DEBUG("\n[fn]Finished printing the list.");
          return;
      }

  } // end namespace util::list

  std::list<std::string> knownLangsList { "C++", "Python", "Cython", "Rust", "Java" };
  std::list<std::string> mainLangsList { "C++", "Python" };

  int main(int argc, const char** argv) {
      /* Test template function util::print_list(std::list<T>) */
      util::list::print_list(knownLangsList);
      util::list::print_list(mainLangsList);

      return 0;
  }
  ```
</details>
