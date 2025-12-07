# ![Void Pointer](https://raw.githubusercontent.com/voidptr-cxx/voidptr-cxx/void_pointer_logo.png)

<div align="center">

### `void* ptr = &developer;` 
### *Navigating the depths of C/C++ one pointer at a time*

[![Profile Views](https://komarev.com/ghpvc/?username=voidptr-cxx&color=00ff88&style=flat-square&label=Profile+Views)](https://github.com/voidptr-cxx)

</div>

---

## `$ whoami`

```cpp
class Developer {
private:
    std::string name = "voidptr-cxx";
    std::vector<std::string> languages = {"C", "C++", "Assembly"};
    std::string current_focus = "Low-level systems programming";
    
public:
    void* interests() {
        return reinterpret_cast<void*>(
            new std::vector<std::string>{
                "Memory management",
                "Performance optimization", 
                "System architecture",
                "Embedded systems",
                "Compiler internals"
            }
        );
    }
    
    [[nodiscard]] constexpr auto passion() const noexcept {
        return "Building things that go fast 🚀";
    }
};
```

---

## `⚡ Tech Stack`

<div align="center">

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GDB](https://img.shields.io/badge/GDB-3776AB?style=for-the-badge&logo=gnu&logoColor=white)
![Valgrind](https://img.shields.io/badge/Valgrind-800000?style=for-the-badge&logoColor=white)

</div>

---

## `📊 GitHub Stats`

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=voidptr-cxx&show_icons=true&theme=chartreuse-dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=000000&title_color=00ff88&icon_color=00ddff&text_color=ffffff"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=voidptr-cxx&layout=compact&langs_count=8&theme=chartreuse-dark&hide_border=true&bg_color=000000&title_color=00ff88&text_color=ffffff"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=voidptr-cxx&theme=chartreuse-dark&hide_border=true&background=000000&ring=00ff88&fire=ff0080&currStreakLabel=00ddff&sideNums=ffffff&sideLabels=00ff88&dates=ffffff)](https://git.io/streak-stats)

</div>

---

## `🔧 What I'm Working On`

```c
/* Currently focusing on */
typedef struct {
    const char* project;
    const char* description;
    int priority;
} CurrentWork;

CurrentWork stack[] = {
    {"High-performance data structures", "Custom allocators & cache-friendly designs", 1},
    {"Systems programming", "OS fundamentals & kernel modules", 2},
    {"Compiler exploration", "Understanding the magic behind the code", 3}
};
```

---

## `💡 Philosophy`

> *"C makes it easy to shoot yourself in the foot; C++ makes it harder, but when you do, it blows away your whole leg."*
> — Bjarne Stroustrup

I believe in:
- **Manual memory management** - Understanding what happens under the hood
- **Zero-cost abstractions** - Performance without compromise  
- **RAII** - Because destructors are your friends
- **Const correctness** - If it doesn't mutate, mark it const
- **Profile before optimizing** - But always write efficient code

---

## `🎯 Current Learning Path`

```cpp
auto learning_queue = std::queue<std::string>{
    "Advanced template metaprogramming",
    "Lock-free data structures", 
    "SIMD optimization techniques",
    "Modern C++ (C++20/23)",
    "Reverse engineering basics"
};
```

---

## `📫 Connect With Me`

<div align="center">

```
0x00: Exploring memory addresses
0x08: Dereferencing pointers  
0x10: Segmentation fault (core dumped)
0x18: git push origin main
```

**Let's collaborate on low-level projects or discuss systems programming!**

</div>

---

<div align="center">

### `while(alive) { code(); learn(); optimize(); }`

```
┌─────────────────────────────────────────┐
│  "In C we trust, in C++ we abstract"    │
└─────────────────────────────────────────┘
```

*Built with ⚡ by voidptr-cxx*

</div>
