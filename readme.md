# Bond Component Library

Used to develop, test and store all Bond components.

_Make sure you have Bun installed and Node 18+._

## Goal

The goal of this exercise is to create a simple component as part of the Bond Component Library.

**Start by forking this repository and then follow the instructions below. When you are done, send us a link to your fork.**

Use the following design as a reference:
[Figma file](https://www.figma.com/community/file/1296327233100400854)

1. Open in Figma.
2. Go to the `UI Kit` page.

## Challenge: Implement the Blog Column component

1. Use Tailwind.
2. Make it responsive as per the design.
3. Add a Storybook story for the component.
4. Add a test for the component.

Note: All data will come through props (title, description, date, etc).

## Getting Started

### To get started (development)

```
bun i
```

### Build:

```
bun run Build
```

### Storybook

```
bun run storybook-build && bun run storybook
```

### Testing

```
bun run test
```

## Component Structure

All components are in their own prospective folders to allow for storybook & testing files

#### e.g. a basic Button component example

```
Button.tsx
Button.stories.tsx
Button.test.tsx
index.ts
```
