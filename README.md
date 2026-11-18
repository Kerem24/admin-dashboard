# Admin Dashboard

A clean, modern Admin Dashboard layout built as the final capstone project for [The Odin Project](https://www.theodinproject.com/)'s **Intermediate HTML and CSS** curriculum.

## Overview

The primary goal of this project was to practice building a complex, multi-section dashboard layout by relying heavily on **CSS Grid** for the overarching page structure and nested card grids, paired with **Flexbox** for internal component alignment.

## Features

- **CSS Grid Architecture:** Structured into a 3-column, 3-row main layout featuring a fixed sidebar, a two-tier header, a dynamic project grid, and right-hand widgets (Announcements & Trending).
- **Fluid Center Content:** Uses fractional units (`1fr`) for the main project workspace so cards stretch and adapt smoothly across viewport widths while keeping sidebars anchored.
- **Component-Based Styling:** Modular cards with subtle drop shadows, accent borders, SVG iconography, and clean typography using Google Fonts (`Roboto`).

## Built With

- Semantic HTML5
- CSS3 (CSS Grid & Flexbox)
- [Google Fonts](https://fonts.google.com/) (Roboto)
- Inline SVGs & [DiceBear Avatars](https://www.dicebear.com/)

## What I Learned

- Combining fixed pixel tracks (`px`) with flexible fractional units (`1fr`) and `auto` row sizing to prevent layout distortion during browser zooming.
- Nesting CSS Grids inside Flexbox containers (and vice versa) to align complex UI elements without relying on manual negative margins.
- Structuring reusable card components (`Projects`, `Announcements`, `Trending`) with consistent spacing (`gap` and `padding`).

## Acknowledgments

- Project design and specifications provided by [The Odin Project](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard).
