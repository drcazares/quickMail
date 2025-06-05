# Email Template Builder (React + TipTap)

This project is a customizable email template builder built using React and [TipTap](https://tiptap.dev/). It enables users to create responsive, brand-consistent HTML email layouts with live preview, rich text editing, background color selection, component reordering, and export functionality.

## Features

- **Modular Components**: Add and arrange pre-defined components like full-width text blocks, full-width images, and spacers.
- **Custom Styling**: Edit font sizes, colors, alignment, and background colors directly within a user-friendly interface.
- **WYSIWYG Editing**: Built-in TipTap editor for rich text formatting, including bold, italic, underline, superscript, hyperlinks, and font size.
- **Export to HTML**: Generates clean, render-proof email HTML (including VML-friendly formatting for Microsoft Outlook).
- **Image Upload Support**: Handles external URLs and base64 encoding for downloadable images.
- **Outlook Styling Workarounds**: Includes smart formatting such as wrapping links in `<strong>` tags to avoid default blue styling in email clients.
- **ZIP Export**: Exports HTML + image assets in a zipped package.

## Tech Stack

- **React** (with TypeScript)
- **TipTap** Editor (v2)
- **Tailwind CSS** (utility-first styling)
- **JSZip** (for zip file generation)

## Getting Started

### Prerequisites

- Node.js (18+ recommended)
- npm or yarn

### Install

```bash
npm install
