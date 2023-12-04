# helloklara.com

This is my personal website/portfolio where you can get to know me as a programmer a bit better. The page is created with Astro, Javascript/Typescript and Tailwind.

## Project Structure

Here is a model of the project-structure. I have excluded some files to make the structure more visual.

```text
/
├── public/
│   └── images/
│   └── CNAME
│   └── ...
├── src/
│   └── pages/
│        └── projects.astro
│        └── portfolio.astro
│        └── CV.astro
│        └── pics.astro
│        └── books.astro
│        └── friends.astro
│   └── layouts/
│        └── MainLayout.astro
│   └── components/
│        └── Folder.astro
│        └── Footer.astro
│        └── LinkList.astro
│        └── Navbar.astro
└── ...
```

## Commands

All commands are run from the root of the project, from a terminal:

| Command    | Action                               |
| :--------- | :----------------------------------- |
| `yarn dev` | Starts local dev server at localhost |
