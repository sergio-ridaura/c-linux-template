# C Linux Template v24.06.27

_Copyright (c) 2024 [Sergio Ridaura](https://github.com/sergio-ridaura)._

Template for development in [C](https://www.iso.org/standard/74528.html) language on [Linux](https://ubuntu.com/).

[<img alt="C" src="https://img.shields.io/badge/C-0078D4?style=for-the-badge&logo=c&logoColor=FFFFFF" />](https://www.iso.org/standard/74528.html) &nbsp; [<img alt="Linux" src="https://img.shields.io/badge/Linux-333333?style=for-the-badge&logo=linux&logoColor=FFFFFF" />](https://www.iso.org/standard/74528.html)

## Install

Use this template in your [GitHub](https://github.com/) repository or clone the repository to your computer:

```shell
git clone https://github.com/sergio-ridaura/c-linux-template.git
```

Ensure you have the C compiler installed on your development machine. On [Ubuntu](https://ubuntu.com/), run the following commands:

```shell
sudo apt-get update
sudo apt-get -y upgrade

sudo apt install -y build-essential
```

## Development

Use [Visual Studio Code](https://code.visualstudio.com/) for development, employing the [C/C++ extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools), which facilitates application compilation.

Develop the code starting from the `src/main.c` file. Compile the project using the extension and run the resulting binary located in the `build` folder with the following command:

```shell
./build/main
```

### Docker

You can test or develop the application in a secure environment using a [Docker](https://docs.docker.com/) container.

Start the container with [Docker Compose](https://docs.docker.com/compose/).

```code
docker-compose up -d
```

Access the Ubuntu container:

```code
docker exec -it c-linux-template_node bash
```

## Author

### [Sergio Ridaura](https://github.com/sergio-ridaura)

Full Stack Developer specializing in [TypeScript](https://www.typescriptlang.org/), [WebAssembly](https://webassembly.org/), [Astro](https://astro.build/), [React.js](https://es.react.dev/), [Tailwind CSS](https://tailwindcss.com/), [Node.js](https://nodejs.org/) and [MySQL](https://www.mysql.com/). Expertise in rapid development of high-performance web applications and sites.

[<img alt="Email" src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=FFFFFF" />](mailto:sergio.ridaura@outlook.com) &nbsp; [<img alt="GitHub" src="https://img.shields.io/badge/GitHub-333333?style=for-the-badge&color=181717&logo=github&logoColor=FFFFFF" />](https://github.com/sergio-ridaura) &nbsp; [<img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=FFFFFF" />](https://www.linkedin.com/in/sergio-ridaura/) &nbsp;

## MIT License

_Copyright (c) 2024 [Sergio Ridaura](https://github.com/sergio-ridaura)._

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
