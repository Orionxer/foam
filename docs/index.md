# Using Foam

Foam is a collection VS Code extensions and recipes that power up the editor
into a full-blown note taking system. This folder contains user documentation
describing how to get started using Foam, what its main features are, and
strategies for getting the most out of Foam. The full docs are included in the
`foam-template` repo that most users start from.

> See also [[frequently-asked-questions]].

这是一个脚注 [^1]

## Getting Started

- [[get-started-with-vscode]]
- [[recommended-extensions]]
- [[creating-new-notes]]
- [[write-notes-in-foam]]
- [[sync-notes-with-source-control]]
- [[keyboard-shortcuts]]

## Features

- [[wikilinks]]
- [[tags]]
- [[backlinking]]
- [[daily-notes]]
- [[including-notes]]
- [[spell-checking]]
- [[graph-visualization]]
- [[note-properties]]
- [[note-templates]]
- [[paste-images-from-clipboard]]
- [[custom-markdown-preview-styles]]
- [[link-reference-definitions]]
- [[custom-snippets]]

## Recipes

[[recipes]] is a collection of user-contributed patterns that describe different ways you could utilize Foam or integrate it with other tools.

## Publishing

You can publish your Foam notes for consumption in different formats.
Examples: [[publish-to-github-pages]], [[generate-gatsby-site]], [[publish-to-vercel]]

See [[publishing]] for more details.

## Tools

- [[cli]]
- [[workspace-janitor]]
- [[orphans]]
- [[foam-logging-in-vscode]]

## Code Snippet

```c
/******************************************************
 * @brief   最简单的C函数
 * @note    没有需要注意的
 ******************************************************/
for (size_t i = 0; i < 5; i++)
{
    printf("Hello World\n");   
}
```

```sh
echo "Hello World"
```

Inline math: $x^2$

Math block:

$$
\displaystyle
\left( \sum_{k=1}^n a_k b_k \right)^2
\leq
\left( \sum_{k=1}^n a_k^2 \right)
\left( \sum_{k=1}^n b_k^2 \right)
$$

![Memory View](image.png)

## Git Commit常用Emoji

| Emoji |      描述      |           Description            |
| :---: | :------------: | :------------------------------: |
|   🎉   |   创建新工程   |          Beginaproject           |
|   ✨   |     新功能     |       Introducenewfeatures       |
|   🐛   |    修复Bug     |             Fixabug              |
|   🔀   |    合并分支    |          Mergebranches           |
|   ⚡️   |    性能提升    |        Improveperformance        |
|   ✅   |    通过测试    |     Add,update,orpasstests.      |
|   ♻️   |      重构      |           Refactorcode           |
|   🔥   | 删除代码或文件 |        Removecodeorfiles         |
|   📝   | 更新文档或协议 |    Addorupdatedocumentation.     |
|   🔖   |    发布版本    |       Release/Versiontags        |
|   💡   |    增加注释    | Addorupdatecommentsinsourcecode. |

<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

You can add text within a collapsed section. 

You can add an image or a code block, too.

```ruby
puts "Hello World"~~~~
```

### Mkdocs-Material

It's good to use mkdocs-material!

</details>

[^1]: 脚注 1
