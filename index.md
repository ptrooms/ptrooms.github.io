## Welcome to GitHub Pages PtrO (wip) Jekyll  time: {{site.time}} textwallclock:15u33s20
Published [https://ptrooms.github.io](https://ptrooms.github.io) , this is file: index.md@gh-pages
[My GIT](https://github.com/ptrooms) and [hcc.pafo2.nl](http://hcc.pafo2.nl)

<img src="/assets/images/ptro_680x478.jpg" alt="ptrologo" height="100"> ![GitLogo](/assets/images/Git_logo.png) <img src="/assets/images/hcclogo.png" alt="hcclogo" height="100">

You can use the [editor on GitHub](https://github.com/ptrooms/ptro.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

# Using ticket-marks
```
- [X] Write the code
```
- [X] Write the code
- [ ] Write all the tests
- [ ] Document the code

# Using snippets
sample:
```java
for(int i=0 ; i < 5 ; i++)
{
System.out.println("i is : " + i);
}
```
# Using: quotes
```
> Whether 'tis Nobler in the mind to suffer
```
> The Slings and Arrows of outrageous Fortune, 
How big are these slings and in particular, these arrows?

# Flows
Flows using mermaid (tod:29may22 22u21m17)
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

# Using GeoJson
```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```
# Creating 3D STL
```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```

# Mathematical expressings

This sentence uses `$` delimiters to show math inline:  $\sqrt{3x-1}+(1+x)^2$


# using Emoji's
```
I :eyes: that :bug: and I :cold_sweat:.
:trophy: for :microscope: it.
:+1: and :sparkles: on this :ship:, it's :fire::poop:!
:clap::tada::panda_face:
```
:eyes: that :bug: and I :cold_sweat:.
:trophy: for :microscope: it.
:+1: and :sparkles: on this :ship:, it's :fire::poop:!
:clap::tada::panda_face:

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ptrooms/ptro.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
