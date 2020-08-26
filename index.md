
### Assumptions
- Basic to Intermediate modeling abilities
- No zbrush or substance painter required, but since I use them, I’ll cover them here
### Modeling and Topology
- Default T pose
- 30 and 70k polys are plenty
- Scaling
- Going back and forth between Zbrush and Blender
- Before continuing, now that modifying your topology after this point will make you re-texture and re-rig your model
- Testing for watertightness
- - Select by trait - ctrl + 
- Redoing it - pose mode, select all, select object, weight paint mode, automatic weight paints
### Previewing your avatar
- Unity import
- Getting the right version
- Test bones
- Testing your bones
- Setting up your camera
- Testing locally
- Errors when importing
- Importing from Blender
- Importing from FBX
- “Force T Pose”
### Moving to the next step:
- Apply your modifiers
Texturing
- Making UVs
- UVs with substance painter
- Editing textures in blender
- - Filling uv islands
- - Previewing your texture
- Editing textures externally
- Exporting textures
- Substance painter
- FBX gotchas
- Shader gotchas
### Rigging
- Default rigs
- Default bones
- Hips and alignment
- Figure out - weird standing
- Extra bones for dynamic bones
- Rigging and vertex groups
- Eye rig
- Clearing vertex groups
- Working with vertex Groups
- - In the 'n' menu - select a vertex, deselect it, then bring it back
- - Mirror modifier
- - Bug in vertex weights - have to turn it off then back on again
- Weight painting tips
- - Turn on auto normalize
- - Symmetry settings
- - ctrl + left click bone while in weight paint mode to pick a different bone (right now you need to check the tail) - you can move those bones and test themout from here. 
- - Spend a few minutes on a rough draft, then pose it up, then clean it up
- - Add a little bit of smoothing - .2 is recommended by royal skies
- - alt g, alt r, alt s to clear transforms in pose
- - Transfering weights TODO 
- Pose libraries, you can use them for testing - turn on the little save button by default
### Shape Keys
- Shape keys
- Visimes
- Additional rigging resources
- Blend shapes with zbrush
- Updating shape keys
- - vertex -> propogate to shapes
- TODO figure out blend from shapes
- Mirroring shape keys - duplicate shape key, mirror topology
### Unity: 
- Bones
- Testing your muscles
- Multiple objects will have multiple materials
- Visimes
- Eyes
- Dynamic Bones
- Materials
### Issues in isolation
- Flexible bones and small areas (read: floppy ears.) 
### Additional Resources
- Blender retopo
- https://flippednormals.com/downloads/retopology-in-blender-2-8/
- https://cgcookie.com/course/introduction-to-retopology
- General retopo
- https://flippednormals.com/downloads/how-to-retopologize-a-full-character/
- Blender rigging
- https://www.youtube.com/watch?v=uWuE8Gnhuy4&list=PLZpDYt0cyiusytIPAOTPRzsa4GK6LgY3_&index=11
- Zbrush
- https://gumroad.com/pavlovich#xOIoZ - Zbrush for Ideation - Michael Mavlovich
- Substance Painter
- https://flippednormals.com/downloads/introduction-to-substance-painter/

## Bounce notes (may not apply to dynamic bones)
- stiffness - affects how frequently the bones bounce. Closer to 0, longer but less bounces, closer to 1 more bounces but shorter
- dampenining - 0 means loses energy slowly, 1 means loses energy quickly
- 

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/vreahli/vrchat-avatars-from-scratch.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

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

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/vreahli/vrchat-avatars-from-scratch.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
