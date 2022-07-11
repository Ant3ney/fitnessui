# Fitness UI

A React UI Library for Building Workout and Fitness Apps.

## Install

```bash
npm i --save fitnessui
```

## Testing components manualy via browser

Make sure to have one terminal run

```bash
npm run sass
```

Also run the following command in another terminal

```bash
npm run start
```

Why not just compile the scass using sass for node-sass.
The short answer is I don't know how to make those work. When you use sass or node-scass you import your .scass files by referencing them as '\*.scss' in the file consuming those files. This causes problems when trying to build this package for production as I only know how to make the production / dist files read .css files.
