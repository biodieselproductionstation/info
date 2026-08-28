# [เครื่องใหม่](https://browser.geekbench.com/v7/cpu/208838)
# [ประวัติรัฐมนตรี](https://de.wikipedia.org/wiki/Loei_(Provinz))
# [DGA](https://www.dga.or.th/)
# [ตำแหน่งจังหวัดเลย]
# DGA Resource Center

This repository contains the documentation website code and Markdown source files for kb.dga.or.th.

We build this website using Astro and its official documentation framework, [![Starlight](https://astro.badg.es/v2/built-with-starlight/tiny.svg)](https://starlight.astro.build).

## Getting Started

### Prerequisites:

* Node.js and npm (or yarn) installed on your system. You can check your versions by running node -v and npm -v (or yarn -v) in your terminal.

### Running the Development Server:

1. Clone this repository or download the project files.
2. Open a terminal in the project directory.
3. Install dependencies:
    * Using npm: npm install
    * Using yarn: yarn install
4. Start the development server:
    * Using npm: npm run dev
    * Using yarn: yarn dev This will start the development server at http://localhost:4321/.   

### Building for Production:

Build the project for production:
* Using npm: npm run build
* Using yarn: yarn build This will create an optimized production build in the dist folder.

### Content Structure

This project uses the following folder structure:

```
.
├── README.md (You are here!)
├── astro.config.mjs  (Astro configuration file)
├── node_modules  (Dependency folder)
├── package.json  (Project dependencies and scripts)
├── public  (Static assets like favicons)
└── src  (Project source code)
    ├── assets  
    │   ├── images/  (Folder for images)
    │   └── files/   (Folder for files)
    ├── content  (Contains documentation content)
    │   └── docs  (Markdown files for documentation pages)
    │       ├── service  (Subfolder for each service)
    │       ├── index.mdx  (Homepage content)
    └── tsconfig.json  (TypeScript configuration file)
```

Starlight looks for `.md` or `.mdx` files in the `src/content/docs/` directory. Each file is exposed as a route based on its file name.

Static assets, like favicons, can be placed in the `public/` directory.

### 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

### Contributing

Contents within kb.dga.or.th, and thus in this repo, are maintained by DGA staffs. If you have enquiries please contact contact@dga.or.th

### License

This project is licensed under the MIT License. See the LICENSE file for details.

<img width="572" height="802" alt="5309" src="https://github.com/user-attachments/assets/c0a2bb8a-c60d-458e-85ee-29a3515dbc1a" />
<img width="572" height="799" alt="5308" src="https://github.com/user-attachments/assets/1042f83b-5e98-4f27-b4f8-2a3bef3301cd" />
<img width="572" height="795" alt="5307" src="https://github.com/user-attachments/assets/37e507a3-a8a9-4cf8-a09e-a1bf193efeef" />
<img width="572" height="802" alt="5306" src="https://github.com/user-attachments/assets/4bfac8ba-ba76-46e5-bd85-7dbd39664fa0" />
<img width="572" height="794" alt="5305" src="https://github.com/user-attachments/assets/8d51524f-0711-4e96-af7d-cf620350caae" />
<img width="572" height="805" alt="5304" src="https://github.com/user-attachments/assets/51ed1bb1-9753-4db9-a7fc-13ff28bfddc5" />

