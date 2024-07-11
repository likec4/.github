<div align="center">
  <h1>
    Architecture as a code
  </h1>
  <h4>
    Toolchain for your architecture diagrams
  </h4>
  
  [docs](https://likec4.dev/) | [playground](https://playground.likec4.dev/w/tutorial/) | [demo](https://template.likec4.dev/view/cloud)

![vscode extension](https://github.com/likec4/likec4/assets/824903/d6994540-55d1-4167-b66b-45056754cc29)

</div>


## What is LikeC4?

LikeC4 is a set of tools and DSL, that describes architecture as a single model and then compiled into multiple diagrams.

Your code is single source of truth.
Any change, refinement or deprecation is reflected automatically in the architecture diagrams.
No more outdated documentation!
And history of changes is your version control system.

LikeC4 provides:
- architecture-as-a-code with native IDE support
- development server with live reload
- static website generation (live demo)
- React and Webcomponents generation to embed to your website
- CI/CD automation via CLI and GitHub Actions
- export to various formats:
  - PNG
  -  Mermaid
  - D2
  - DOT (Graphviz)
 
You can use LikeC4 standalone or integrate with existing toolchain.

## Why “like”?
LikeC4 is inspired by the C4 model and Structurizr DSL, and goes beyond them by offering flexibility and customization.
You can use your ubiquitous language, your terms and any number of nested levels.


## What does LikeC4 look like?

<div align="center">
  <img src="https://github.com/likec4/.github/assets/824903/c0f22106-dba6-469e-ab47-85e7b8565513" width="675px">
</div>

Run CLI to preview:

```sh
npx likec4 start
```

And result:

<div align="center">
  <img src="https://github.com/likec4/likec4/assets/824903/27eabe54-7d97-47a8-a7e4-1bb44a8e03e5" width="984px">
</div>

Template repository - [likec4/template](https://github.com/likec4/template)  
Deployed - [https://template.likec4.dev](https://template.likec4.dev/view/cloud)
