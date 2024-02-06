# Game Engine Comparison Matrix

This comparison matrix was created to aid selection of an engine for developing the Marloth game. The criteria and ratings of this comparison are specialized toward that goal (a first person 3D role playing game created by one person), but this document may have some general value for other projects.

GZDoom may seem like an odd option, but it is an impressive technology with a large community and is increasingly powering hit 3D indie games.

|                                     |       Unreal       |       Unity        |       Godot        |       GZDoom       |
| ----------------------------------- | :----------------: | :----------------: | :----------------: | :----------------: |
| **Licensing**                       |                    |                    |                    |                    |
| Open Source                         |                    |                    | :heavy_check_mark: | :heavy_check_mark: |
| Free source code visibility         | :heavy_check_mark: |                    | :heavy_check_mark: | :heavy_check_mark: |
| No royalties                        |                    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| No subscriptions                    | :heavy_check_mark: |        :x:         | :heavy_check_mark: | :heavy_check_mark: |
| **Totals**                          |         2          |         0          |         4          |         4          |
|                                     |                    |                    |                    |                    |
| **Programming**                     |                    |                    |                    |                    |
| Targets senior developers           | :heavy_check_mark: |                    |                    |                    |
| Elegant programming                 |                    | :heavy_check_mark: | :heavy_check_mark: |        :x:         |
| Good Refactoring                    |        :x:         | :heavy_check_mark: | :heavy_check_mark: |                    |
| Code separate from assets           | :heavy_check_mark: |                    | :heavy_check_mark: |                    |
| **Totals**                          |         1          |         2          |         3          |         -1         |
|                                     |                    |                    |                    |                    |
| **Graphics and Audio**              |                    |                    |                    |                    |
| Gorgeous out-of-the-box             | :heavy_check_mark: |                    |                    |                    |
| Advanced 3D graphics                | :heavy_check_mark: | :heavy_check_mark: |        :x:         |        :x:         |
| Lots of free content                | :heavy_check_mark: |                    |                    | :heavy_check_mark: |
| Advanced character animation        | :heavy_check_mark: |                    |        :x:         |                    |
| Professional audio system           | :heavy_check_mark: | :heavy_check_mark: |        :x:         | :heavy_check_mark: |
| Professional UI scaling             | :heavy_check_mark: | :heavy_check_mark: |                    |                    |
| Elegant shader programming          | :heavy_check_mark: |                    |                    |        :x:         |
| Integrated mesh editing             | :heavy_check_mark: | :heavy_check_mark: |                    |                    |
| **Totals**                          |         8          |         4          |         -3         |         0          |
|                                     |                    |                    |                    |                    |
| **Workflow**                        |                    |                    |                    |                    |
| Modular scenes                      |                    | :heavy_check_mark: | :heavy_check_mark: |                    |
| Text file assets                    |        :x:         | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Assets use industry standard format |                    | :heavy_check_mark: |                    |                    |
| Fast editor loading                 |                    |                    | :heavy_check_mark: | :heavy_check_mark: |
| Minimal editor pauses               | :heavy_check_mark: |                    | :heavy_check_mark: | :heavy_check_mark: |
| Performant editor                   | :heavy_check_mark: |                    | :heavy_check_mark: | :heavy_check_mark: |
| Easily customizable editor          |                    |                    | :heavy_check_mark: |                    |
| Component system                    | :heavy_check_mark: | :heavy_check_mark: |                    |                    |
| Advanced level creation             |                    | :heavy_check_mark: |        :x:         |                    |
| Debugging tools                     | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |        :x:         |
| Visual GUI editor                   | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |        :x:         |
| **Totals**                          |         4          |         7          |         7          |         2          |
|                                     |                    |                    |                    |                    |
| **General Features**                |                    |                    |                    |                    |
| Integrated 3D game framework        | :heavy_check_mark: |                    |                    | :heavy_check_mark: |
| Robust profiling tools              | :heavy_check_mark: |                    |        :x:         |        :x:         |
| Robust input system                 | :heavy_check_mark: | :heavy_check_mark: |                    |                    |
| Robust physics                      | :heavy_check_mark: | :heavy_check_mark: |                    | :heavy_check_mark: |
| Robust network support              | :heavy_check_mark: |                    |        :x:         |                    |
| Robust AI navigation                | :heavy_check_mark: |                    |                    |                    |
| 2D games                            |                    | :heavy_check_mark: | :heavy_check_mark: |                    |
| Local multiplayer                   | :heavy_check_mark: | :heavy_check_mark: |                    |        :x:         |
| **Totals**                          |         7          |         4          |         -1         |         0          |
|                                     |                    |                    |                    |                    |
| **Reliability and Usability**       |                    |                    |                    |                    |
| Battle-tested                       | :heavy_check_mark: | :heavy_check_mark: |        :x:         | :heavy_check_mark: |
| General purpose engine              | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    |
| Easy editor installation            |                    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Editor can run on medium hardware   |                    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Good documentation                  |                    |                    |        :x:         |        :x:         |
| High performance scripting          | :heavy_check_mark: | :heavy_check_mark: |                    |                    |
| Career opportunities                | :heavy_check_mark: | :heavy_check_mark: |                    |                    |
| Minimal bugs                        | :heavy_check_mark: |                    |                    |                    |
| Backwards compatibility             | :heavy_check_mark: |                    |        :x:         | :heavy_check_mark: |
| Stable performance                  | :heavy_check_mark: | :heavy_check_mark: |        :x:         | :heavy_check_mark: |
| **Totals**                          |         8          |         8          |         0          |         4          |
|                                     |                    |                    |                    |                    |
| **Aggregate Totals**                |         29         |         24         |         9          |         10         |

## Notes

### No subscriptions

* The [revenue caps on Unity subscriptions](https://unity.com/legal/terms-of-service/software) are a little dubious:
  * The caps are based on all income regardless of whether the income is related to Unity or gaming
  * For contractors, the revenue cap is dictated by the *client's* income, meaning that if a developer is providing free Unity services to a corporation, that developer would need to pay for the Pro Unity subscription ($1,800 per year as of mid 2022)
  * Technically, Unity's usage restrictions have nothing to do with whether a game is published—many people on the internet falsely claim that Unity is free for everyone to experiment with, but Unity's legal documents and representatives have made it clear that is not the case—there are many cases where it is illegal for a user to install and run the Unity editor without first paying for a subscription
    * This is not legal advice, but it is probable that Unity can only practically enforce their terms when there is a published game
* In essence, Unity's terms discourage contractors and agencies who only dabble with Unity
* Conversely, Unity's terms prefer customers who are either pure hobbyists or dedicated game developers

### Elegant Programming

* Unreal's programming has the following issues:
  * Extremely inefficient C++ compile times
    * Beefy hardware can help with this but only to a point, and it shouldn't be needed
    * Contrary to what many Unreal developers say, the issue is not that the Unreal codebase is large—the problem is with UBT
      * Incremental C++ builds are a solved problem—Unreal bypasses much industry standard tooling in favor of their incomplete custom tooling that doesn't have proper incremental build support
  * The majority of C++ code needs to be parsed by UBT, which only supports a narrow subset of C++ features and forces some unprofessional programming practices
  * Even though C++ is Unreal's foundation, many of Unreal's systems (Such as it's UI, AI, and skeletal animation) treat C++ as a second-rate citizen (in favor of Blueprints)
  * For an experienced developer, blueprints take more time to create and maintain than code, are more limited in their ability to abstract common patterns, and are more limited in terms of refactoring, debugging, and profiling
  * In practice, most Unreal games need to split their codebase between C++ and Blueprints, which generally means increased shuffling of functionality back and forth between the two domains and increased code rewriting
  * The Unreal codebase has many legacy design decisions from the 90s, such as:
    * Requiring developers to prefix classes with letter symbols
    * A [non-standard coordinate system](https://www.techarthub.com/wp-content/uploads/coordinate-comparison-chart-full.jpg)
      * Which is non-standard because it frankly doesn't make a lot of sense
        * Having X+ be the forward axis might make sense considering that X+ *is* the starting point for cartesian rotations except Unreal's Y axis is backwards for that to be useful
        * At least Unreal uses Z-up :thumbsup:

### Code separate from assets

* While there are cases where it can be convenient to treat some code as game assets, Unity's treatment of the entire codebase as a collection of game assets sacrifices many professional programming features and introduces additional workflow challenges and workflow performance challenges

### Integrated 3D game framework

* A similar framework can be built in other engines, but out-of-the-box, the Unreal game systems are so polished and mature (particularly their character and camera rigs), it is difficult to recreate that same level of quality elsewhere
* Likewise, DOOM's gameplay systems have an extremely polished and definitive feel that has been an industry reference point for decades

### Minimal editor pauses

* Unity can suffer from severe editor pauses unless the code is well organized (divided into assemblies) and the relatively recent feature of skipping domain reloading when playing is turned on

### Component system

* Godot's node-based system is inferior to a more traditional component system
  * Unreal and Unity's component systems work great for 90% of use cases and are terrible for the remaining 10%
  * Godot's node system is convoluted for 90% of use cases, and great for the remaining 10%

### Robust profiling tools

* Unity's profiling tools are adequate—Unreal's profiling tools are impressive

### Up front technical costs

* Unity has a tendency to be full of technical surprises that don't surface until late into production

### Easy editor installation

* Unreal Engine is a massive installation
* The Epic Games Store is not a great tool for downloading software, particularly large downloads
* The Unreal Engine installation process is unusually error prone
