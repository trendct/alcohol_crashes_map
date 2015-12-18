#TrendDataMapper project template

#####About
This is a project that depends on TrendCT libraries Trendy and TrendDataMapper, which are separate repos.

This was removed from the TrendDataMapper repo so that this repository could be forked to start new projects, rather than keeping it as a demo subdirectory of TrendDataMapper. The vendor/TrendDataMapper/ and vendor/Trendy/ folders are clones of their respective github repos, so that any good changes can just be pushed there.

#####Directory structure

.
├── README.md
├── index.html
├── resources
│   ├── data
│   │   └── sample_project_data.js
│   └── main.js
└── vendor
    ├── TrendDataMapper
    │   ├── README.md
    │   ├── css
    │   │   └── TrendDataMapper.css
    │   └── js
    │       ├── TrendDataMapper.js
    │       └── ct_towns.topojson.js
    ├── Trendy
    │   ├── README.md
    │   └── Trendy.js
    ├── d3.min.js
    ├── datamaps.usa.min.js
    └── topojson.min.js
