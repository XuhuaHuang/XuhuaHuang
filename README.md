### Hi there 👋, this is Xuhua
I consider myself to be a highly-motivated self-learner; various repositories contain all ~~self-taught~~ code written along the way.  

### Recent Coding Activities
<!--START_SECTION:waka-->
```text
C++        58 mins         ⣿⣿⣿⣿⣿⣿⣿⣿⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   32.58 % 
Python     52 mins         ⣿⣿⣿⣿⣿⣿⣿⣤⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   29.46 % 
Markdown   44 mins         ⣿⣿⣿⣿⣿⣿⣤⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   25.07 % 
C          14 mins         ⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   07.93 % 
JSON       4 mins          ⣶⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   02.47 % 
```
<!--END_SECTION:waka-->

### Skills
* 💻 C / C++ / Rust
* 🖥️ Python / Cython / Java
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
  
  extern std::list<string> knownLangsList { "C++", "Python", "Cython", "Rust", "Java" };
  extern std::list<string> mainLangsList { "C++", "Python" };
  
  namespace util {
    template<class T>
    void printList(std::list<T> argList) {
        std::cout << "\n[fn]Printing list..." << std::endl;

        typename std::list<T>::iterator iter;
        for (iter = argList.begin(); iter != argList.end(); ++iter)
            std::cout << *iter << " "; // dereference the iterator to print content

        std::cout << "\n[fn]Finished printing the list." << std::endl;
        return;
    }
  }
  
  int main(int argc, char** argv) {
    /* Test template function util::printList(std::list<T>) */
    util::printList(knownLangsList);
    util::printList(mainLangsList);

    return 0;
  }
  ```
</details>
