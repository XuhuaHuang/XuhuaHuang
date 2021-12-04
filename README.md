### Hi there 👋, this is Xuhua
I consider myself to be a highly-motivated self-learner; various repositories contain all ~~self-taught~~ code written along the way.  
✓ Self learner, quick learner  
✓ C/C++ and Python enthusiast  
✓ Craving for new knowledge and challenges  

### Recent Coding Activities
<!--START_SECTION:waka-->
```text
C++        4 hrs 22 mins   ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀   96.16 % 
Markdown   10 mins         ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   03.67 % 
```
<!--END_SECTION:waka-->

### Skills
* 💻 C / C++ / Python
* 🖥️ Rust / Cython / Java
* ⌨️ Object-Oriented Programming
* 🗃️ SQL / MySQL

#### LinkedIn Skill Assessment Badges
* ✒️ [C++ Programming][LinkedIn Profile Link]
* ✒️ [Python Programming][LinkedIn Profile Link]
* ✒️ [Object-Oriented Programming][LinkedIn Profile Link]

[LinkedIn Profile Link]: https://www.linkedin.com/in/coder-xuhua-huang/

[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/XuhuaHuang)
[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>](https://www.linkedin.com/in/coder-xuhua-huang/)

<!--### More-->

---

<details>
  <summary>More about me</summary>
  
  - 🔭 I’m currently working on enhancing Python skills. 
  - 🌱 I’m currently learning Rust.
  - 📤 Most used line of code `git commit -m "Initial Commit"`
  - 🤔 I’m looking for help with advance Python and Machine Learning.
  - 📫 How to reach me: xuhuahuang0412@gmail.com
  - ⚡ Fun fact: code blooded animal.
</details>

<details>
  <summary>GitHub profile</summary>
  
  <!-- Overall -->
  ##### Overview
  ![visitors](https://visitor-badge.glitch.me/badge?page_id=page.id)
  ![Profile views](https://gpvc.arturio.dev/XuhuaHuang)
  
  <!-- Languages -->
  ##### Top Languages
  [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=XuhuaHuang&layout=compact&theme=vue-dark)](https://github.com/anuraghazra/github-readme-stats)
  
  <!-- Wakatime profile -->
  ##### Summary of Coding Activities
  [![Xuhua's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=XuhuaHuang&layout=compact&theme=vue-dark)](https://github.com/anuraghazra/github-readme-stats)
</details>

<details>
  <summary>I ❤️ C++</summary>
  
  ```C++
  #include<iostream>
  #include<list>
  #include<string>

  #ifndef DEBUG
  #define DEBUG(arg_str) std::cout << arg_str << std::endl;
  #endif

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

  } // end Util::list

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
