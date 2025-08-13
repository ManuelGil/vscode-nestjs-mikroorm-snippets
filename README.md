# NestJS MikroORM Snippets

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/imgildev.vscode-nestjs-mikroorm-snippets?style=for-the-badge&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-mikroorm-snippets)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/imgildev.vscode-nestjs-mikroorm-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-mikroorm-snippets)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/imgildev.vscode-nestjs-mikroorm-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-mikroorm-snippets)
[![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/imgildev.vscode-nestjs-mikroorm-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-mikroorm-snippets&ssr=false#review-details)
[![GitHub Repo stars](https://img.shields.io/github/stars/ManuelGil/vscode-nestjs-mikroorm-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-nestjs-mikroorm-snippets)
[![GitHub license](https://img.shields.io/github/license/ManuelGil/vscode-nestjs-mikroorm-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-nestjs-mikroorm-snippets/blob/main/LICENSE)

> Snippets to speed up development with NestJS + MikroORM in Visual Studio Code.

## Overview

This extension provides a collection of handy snippets for NestJS projects that use MikroORM. Insert commonly used decorators, repository helpers, module bootstrap snippets and other MikroORM patterns with a few keystrokes.

![demo](https://raw.githubusercontent.com/ManuelGil/vscode-nestjs-mikroorm-snippets/main/docs/images/demo.gif)

## Requirements

- Visual Studio Code 1.46.0 or later

## Installation

1. Open Visual Studio Code (or a compatible editor).
2. Open the **Extensions** view (`Ctrl+Shift+X` / `⌘+Shift+X`).
3. Search for **NestJS MikroORM Snippets** or install directly from the [Marketplace page](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-mikroorm-snippets).
4. Click **Install** and reload the editor if prompted.

## Usage

Type part of a snippet name, press `Tab` or `Enter`, and the snippet unfolds.

### Key snippets

| Snippet                                   | Purpose                          |
| ----------------------------------------- | -------------------------------- |
| `ns_mikroorm_entity_manager`              | `EntityManager`                  |
| `ns_mikroorm_entity_dto`                  | `EntityDTO`                      |
| `ns_mikroorm_request_context`             | `RequestContext.create(...)`     |
| `ns_mikroorm_deco_entity`                 | `@Entity`                        |
| `ns_mikroorm_deco_primary_key`            | `@PrimaryKey` (with tabstop)     |
| `ns_mikroorm_deco_property`               | `@Property`                      |
| `ns_mikroorm_deco_many_to_one`            | `@ManyToOne`                     |
| `ns_mikroorm_deco_one_to_many`            | `@OneToMany`                     |
| `ns_mikroorm_deco_many_to_many`           | `@ManyToMany`                    |
| `ns_mikroorm_deco_one_to_one`             | `@OneToOne`                      |
| `ns_mikroorm_deco_check`                  | `@Check`                         |
| `ns_mikroorm_deco_embeddable`             | `@Embeddable`                    |
| `ns_mikroorm_deco_embedded`               | `@Embedded`                      |
| `ns_mikroorm_deco_ensure_request_context` | `@EnsureRequestContext`          |
| `ns_mikroorm_deco_enum`                   | `@Enum`                          |
| `ns_mikroorm_deco_filter`                 | `@Filter`                        |
| `ns_mikroorm_deco_formula`                | `@Formula`                       |
| `ns_mikroorm_deco_before_create`          | `@BeforeCreate`                  |
| `ns_mikroorm_deco_after_create`           | `@AfterCreate`                   |
| `ns_mikroorm_deco_before_update`          | `@BeforeUpdate`                  |
| `ns_mikroorm_deco_after_update`           | `@AfterUpdate`                   |
| `ns_mikroorm_deco_before_upsert`          | `@BeforeUpsert`                  |
| `ns_mikroorm_deco_after_upsert`           | `@AfterUpsert`                   |
| `ns_mikroorm_deco_on_init`                | `@OnInit`                        |
| `ns_mikroorm_deco_on_load`                | `@OnLoad`                        |
| `ns_mikroorm_deco_before_delete`          | `@BeforeDelete`                  |
| `ns_mikroorm_deco_after_delete`           | `@AfterDelete`                   |
| `ns_mikroorm_deco_index`                  | `@Index`                         |
| `ns_mikroorm_deco_unique`                 | `@Unique`                        |
| `ns_mikroorm_entity_repository`           | `EntityRepository`               |
| `ns_mikroorm_deco_inject_mikroorm`        | `@InjectMikroORM`                |
| `ns_mikroorm_deco_inject_repository`      | `@InjectRepository`              |
| `ns_mikroorm_deco_inject_entity_manager`  | `@InjectEntityManager`           |
| `ns_mikroorm_module_root`                 | `MikroOrmModule.forRoot(...)`    |
| `ns_mikroorm_module_feature`              | `MikroOrmModule.forFeature(...)` |
| `ns_mikroorm_deco_serialized_primary_key` | `@SerializedPrimaryKey`          |
| `ns_mikroorm_deco_subscriber`             | `@Subscriber`                    |

## Contributing

Contributions to the NestJS MikroORM Snippets are welcome and appreciated. To contribute:

1. Fork the [GitHub repository](https://github.com/ManuelGil/vscode-nestjs-mikroorm-snippets).
2. Create a new branch for your feature or fix:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make your changes, commit them, and push to your fork.
4. Submit a Pull Request targeting the `main` branch.

Before contributing, please review the [Contribution Guidelines](https://github.com/ManuelGil/vscode-nestjs-mikroorm-snippets/blob/main/CONTRIBUTING.md) for coding standards, testing, and commit message conventions. If you encounter a bug or wish to request a new feature, please open an Issue.

## Changelog

For a complete list of changes, see the [CHANGELOG.md](https://github.com/ManuelGil/vscode-nestjs-mikroorm-snippets/blob/main/CHANGELOG.md).

## Authors

- **Manuel Gil** - _Owner_ - [@ManuelGil](https://github.com/ManuelGil)

For a complete list of contributors, please refer to the [contributors](https://github.com/ManuelGil/vscode-nestjs-mikroorm-snippets/contributors) page.

## Follow Me

- **GitHub**: [![GitHub followers](https://img.shields.io/github/followers/ManuelGil?style=for-the-badge\&logo=github)](https://github.com/ManuelGil)
- **X (formerly Twitter)**: [![X Follow](https://img.shields.io/twitter/follow/imgildev?style=for-the-badge\&logo=x)](https://twitter.com/imgildev)

## Other Extensions

- **[Auto Barrel](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-auto-barrel)**
  Automatically generates and maintains barrel (`index.ts`) files for your TypeScript projects.

- **[Angular File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-angular-generator)**
  Generates boilerplate and navigates your Angular (9→20+) project from within the editor, with commands for components, services, directives, modules, pipes, guards, reactive snippets, and JSON2TS transformations.

- **[NestJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-generator)**
  Simplifies creation of controllers, services, modules, and more for NestJS projects, with custom commands and Swagger snippets.

- **[NestJS Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)**
  Ready-to-use code patterns for creating controllers, services, modules, DTOs, filters, interceptors, and more in NestJS.

- **[T3 Stack / NextJS / ReactJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nextjs-generator)**
  Automates file creation (components, pages, hooks, API routes, etc.) in T3 Stack (Next.js, React) projects and can start your dev server from VSCode.

- **[Drizzle ORM Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-drizzle-snippets)**
  Collection of code snippets to speed up Drizzle ORM usage, defines schemas, migrations, and common database operations in TypeScript/JavaScript.

- **[CodeIgniter 4 Spark](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-spark)**
  Scaffolds controllers, models, migrations, libraries, and CLI commands in CodeIgniter 4 projects using Spark, directly from the editor.

- **[CodeIgniter 4 Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-snippets)**
  Snippets for accelerating development with CodeIgniter 4, including controllers, models, validations, and more.

- **[CodeIgniter 4 Shield Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)**
  Snippets tailored to CodeIgniter 4 Shield for faster authentication and security-related code.

- **[Mustache Template Engine - Snippets & Autocomplete](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-mustache-snippets)**
  Snippets and autocomplete support for Mustache templates, making HTML templating faster and more reliable.

## Recommended Browser Extension

For developers who work with `.vsix` files for offline installations or distribution, the complementary [**One-Click VSIX**](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb) extension is recommended, available for both Chrome and Firefox.

> **One-Click VSIX** integrates a direct "Download Extension" button into each VSCode Marketplace page, ensuring the file is saved with the `.vsix` extension, even if the server provides a `.zip` archive. This simplifies the process of installing or sharing extensions offline by eliminating the need for manual file renaming.

- [Get One-Click VSIX for Chrome &rarr;](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb)
- [Get One-Click VSIX for Firefox &rarr;](https://addons.mozilla.org/es-ES/firefox/addon/one-click-vsix/)

## License

This project is licensed under the **MIT License**. See the [LICENSE](https://github.com/ManuelGil/vscode-nestjs-mikroorm-snippets/blob/main/LICENSE) file for full details.
