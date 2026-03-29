# CLAUDE.md

## Overview

This repo contains custom UserCSS stylesheets for the [Stylus](https://github.com/openstyles/stylus) browser extension. Each subdirectory holds a standalone userstyle targeting a specific website.

## Formatting

- Run: `npx prettier --write .`

## UserCSS Format

Stylesheets use the [UserCSS](https://github.com/openstyles/stylus/wiki/Writing-UserCSS) format:

- Files must be named `*.user.css`
- Each file begins with a `/* ==UserStyle== ... ==/UserStyle== */` metadata block containing `@name`, `@namespace`, `@version`, `@author`, `@license`, etc.
- CSS rules follow the metadata block and are wrapped in `@-moz-document` directives to scope styles to specific domains

## Project Structure

Each subdirectory is a self-contained userstyle (CSS file + optional screenshot). There is no build step or test suite.

## License

CC-BY-NC-SA-4.0
