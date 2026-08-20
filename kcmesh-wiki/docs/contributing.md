# Contributing To The Wiki

The underlying Github repo can be [located here](https://github.com/kcmesh/communitywiki). 

## Contributer Guidelines
The following guidelines should be kept in mind when submitting changes:

- Use clear and precise language, avoiding slang or acronyms without explanation.
- Do not provide guides to facilitate illegal activity.
    - This includes but is not restricted to: jamming, illegal radio transmitting, and defeating regional frequency locks
- Do not provide direct links to items that allow the enablement of illegal activity
- Keep your writing tone non-biased and professional.
- if you upload any images, please try to keep them below 2 Megabytes in size. 



## Text Formatting Examples
### Markdown

[link to another wiki page](about.md)

[link to another page and section](about.md#about-this-site)

*Italic*

**Bold**

***Bold Italic***

^^Underlined^^

> Quote Indent

Tables:

| First Header | Second Header | Third Header |
| ------------ | ------------- | ------------ |
| Content Cell | Content Cell  | Content Cell |
| Content Cell | Content Cell  | Content Cell |


`single code line`


```
multi line
codeblock
```


```python
print("Multi line codeblock")
print("with lang specific syntax highlighting")
```
Local Image Embed

![KCmesh logo](assets/images/kcmesh-logo.png)

Remote Image Embed with scaling

![KCmesh logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/94/LoRa-RF_Ananlyzer-12-7.8k.1.jpg/960px-LoRa-RF_Ananlyzer-12-7.8k.1.jpg){ width="200" }

[comment]: <> (This is a hidden markdown comment that will not visibly show on the site)



### Material Theme Extended Markdown
The material theme provides extended features for markdown.
See the [official reference page](https://squidfunk.github.io/mkdocs-material/reference/) for extended examples. 


!!! note "note admonition"
    sample note
    with helpful info

??? note "collapsable note admonition"
    sample note
    with helpful info

!!! warning "warning admonitions"
    sample warning


Diagram using Mermaid syntax
``` mermaid
graph LR
  A[Start] --> B{Did you read docs?};
  B -->|No| C[Hmm...];
  C --> D[read again];
  D --> B;
  B ---->|Yes| E[Yay!];
```


### HTML
MkDocs supports basic HTML tag formatters as an alternative to markdown. Markdown cannot be used inside of an HTML tag block, only on the outside. 

**<p style="text-align:center">Notice: Notice text example</p>**

**<p style="text-align:center;color:red">Warning: Warning Text Example</p>**


