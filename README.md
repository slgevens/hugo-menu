# hugo-menu
The menu template is designed for persons, restaurants and cafes to create menus with ease.

# Features:
- Dynamic Content: Easily manage and update menu items using Markdown files with front matter.
- Flexible Layout: The template uses Hugo's templating system to generate the menu layout, allowing for easy customization.
- Easy to Deploy: Once customized, the Hugo site can be deployed to any hosting provider or platform.


# Development
For local development run Hugo's built-in local server.

```
hugo server
```

Now enter [`localhost:1313`](http://localhost:1313) in the address bar of your browser.

# Localhost inside exampleSite

You can run this site without installing it as a hugo theme using the following command. I use this for theme development.

```
hugo server --source=exampleSite --theme=../..
```

# Github Codespace

```
hugo server --source=exampleSite --theme=../.. --baseURL=https://improved-pancake-7vgq497rpg72rw59-1313.app.github.dev/ --appendPort=false
```
