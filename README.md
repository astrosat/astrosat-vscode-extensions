# VSCode Extensions I use

An extension pack to maintain mandatory vscode extensions I use.

## Extensions included

|              |
|--------------|
|[Terraform](https://marketplace.visualstudio.com/items?itemName=4ops.terraform&ssr=false)|
|[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments&ssr=false)|
|[Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss&ssr=false)|
|[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint&ssr=false)|
|[ES7+ React/Redux/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets&ssr=false)|
|[GitLens - Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens&ssr=false)|
|[Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode&ssr=false)|
|[Auto Complete Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-complete-tag&ssr=false)|
|[Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker&ssr=false)|
|[Live Share Extension Pack](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack&ssr=false)|
|[Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)|
|[Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight&ssr=false)|
|[Svg Preview](https://marketplace.visualstudio.com/items?itemName=SimonSiefke.svg-preview&ssr=false)|
|[Tabnine AI Autocomplete for Javascript, Python, Typescript, PHP, Go, Java, Ruby & more](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode&ssr=false)|
|[IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode&ssr=false)|
|[React code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets&ssr=false)|
|[Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one&ssr=false)|
|[Better TOML](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml)|
|[DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)|
|[Print](https://marketplace.visualstudio.com/items?itemName=pdconsec.vscode-print)|
|              |

## Building Extension

1. update package.json as needed
2. Install packages: `yarn install`
3. Package extension: `yarn package`
4. Circluate `*.vsix` file to anyone who needs it
5. Press `CTRL + SHIFT + P`, to open the command palette
6. Type `vsix`, to find the command to install a local extension
7. Locate your `*.vsix` file in the root of this repo and select it
8. Verify extension loaded by going to your list of `installed extensions` and search for `Mark Small`, if it is there, then so should all extensions it refers to be.