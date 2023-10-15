## **["Scroll down..."](#output_start)**
```cpp
class OppositeNormal : public DisplayableObject
{
private:
    std::string name;

    std::vector<std::string> skilled_in;
    std::vector<std::string> able_to_work_with;
    std::vector<std::string> interested_in;
    std::vector<std::string> project_worked_with;
    std::vector<std::string> project_worked_on;

    // Being sneaky...
    void DisplayBaseInfo();
public:
    OppositeNormal() : name("OPPOSITE NORMAL")
    {
        skilled_in.push_back("C");
        skilled_in.push_back("C++");
        skilled_in.push_back("Python");
        skilled_in.push_back("Java");
        skilled_in.push_back("Kotlin");
        skilled_in.push_back("Godot Engine");

        able_to_work_with.push_back("OpenGL");
        able_to_work_with.push_back("Unreal Engine");
        able_to_work_with.push_back("Qt");
        able_to_work_with.push_back("Android");

        interested_in.push_back("Vulkan");
        interested_in.push_back("Linux");
        interested_in.push_back("Windows");
        interested_in.push_back("Rust");
        interested_in.push_back("GitHub");

        project_worked_with.push_back("EaseOut");
        project_worked_with.push_back("Does god roll the dice?");
        project_worked_with.push_back("HumanAbove");
        
        project_worked_on.push_back("CosGraphics");
        project_worked_on.push_back("ProjectFG");
    }
    virtual ~OppositeNormal() override {}

    virtual void Display() final override
    {
        DisplayTitle(name);
        DisplayBaseInfo();
        DisplayBlock("Skilled in...", skilled_in);
        DisplayBlock("Able to work with...", able_to_work_with);
        DisplayBlock("Interested in...", interested_in);
        DisplayBlock("Projects I've been working with...", project_worked_with);
        DisplayBlock("Projects I'm working on...", project_worked_on);
    }
}

int main()
{
    OppositeNormal opposite_normal;
    opposite_normal.Display();
    return 0;
}
```

<h1 align="center"> <div id = "output_start"> <img src="./assets/name.png" height="90"> <img src="./assets/icon-round.png" height="25px"></div></font> </h1>

<i>Undergrad student currently majoring in Computer Science and Mathematics. Interested in computer graphics, computer physics and game development. Likes to study with fundamental technologies with software development.</I>

<h2 align="center"><i>Skilled in...</i></h2>

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Godot Engine](https://img.shields.io/badge/GODOT-%23FFFFFF.svg?style=for-the-badge&logo=godot-engine)

<h2 align="center"><i>Able to work with...</i></h2>

![OpenGL](https://img.shields.io/badge/OpenGL-%23FFFFFF.svg?style=for-the-badge&logo=opengl)
![Unreal Engine](https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

<h2 align="center"><i>Interested in...</i></h2>

![Vulkan](https://img.shields.io/badge/Vulkan-AC162C.svg?style=for-the-badge&logo=vulkan&logoColor=white)
![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

<h2 align="center"><i>Projects I've been working with...</i></h2>

<a href = "https://store.steampowered.com/app/2191270/Ease_Out/">
<img src="https://cdn.cloudflare.steamstatic.com/steam/apps/2191270/header.jpg?t=1668990354" height="125px"></a>
<a href = "https://itch.io/jam/gmtk-jam-2022/rate/1622906">
<img src="https://img.itch.zone/aW1nLzk1MDU4MTIuanBn/315x250%23c/l7vSTT.jpg" height="125px"></a>
<a href = "https://on-gaming-studio.itch.io/above-us">
<img src="https://img.itch.zone/aW1hZ2UvMTA4NDg4My82MjIxNTkzLnBuZw==/347x500/U7TO94.png" height="125px"></a>


<h2 align="center"><i>Projects I'm working on...</i></h2>

<a href="https://github.com/OppositeNor/cos-graphics">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=OppositeNor&repo=cos-graphics" height="120px"></a>
<a href="https://github.com/OppositeNor/cos-graphics"> <img src="https://github.com/OppositeNor/cos-graphics/blob/main/assets/cos-graphics-white-with-background-high-res.png?raw=true" height="120"></a>

<a href="https://github.com/nugamestudioclub/Project-FG"><img src="https://github-readme-stats.vercel.app/api/pin/?username=nugamestudioclub&repo=Project-FG"> Project FG </a>

