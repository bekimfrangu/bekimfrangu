- 👋 Hi, I’m @bekimfrangu
- 👀 I’m interested in Backend (Fullstack)
- 🌱 I’m currently learning ReactJS/Typescript
Technologies:
PHP, Laravel, Lumen, Javascript, NodeJS, ExpressJS, VueJS, TailwindsCSS, Firebase, MySQL, MSSQL, MongoDB ...
- 📫 How to reach me -> bekimfrangu7@gmail.com

<?php

namespace BekimFrangu;

class About extends Me
{

    public function technologies(): array
    {
        return [
            PHP::class,
            Laravel::class,
            Lumen::class,
            Javascript::class,
            NodeJS::class,
            Vuejs::class,
            ReactJS::class,
            TailwindCss::class,
            Firebase::class,
            MySQL::class,
            MSSQL::class,
            MongoDB::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
<!---
bekimfrangu/bekimfrangu is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
