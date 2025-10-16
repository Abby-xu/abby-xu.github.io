# Services Structure

This folder contains your services organized into two main categories:

## Folder Structure
```
_services/
├── academic/          # Academic services
├── misc/             # Miscellaneous services
└── README.md         # This file
```

## How to Add Services

### 1. Academic Services
Add markdown files to the `_services/academic/` folder with the following front matter:

```yaml
---
title: Your Service Title
order: 1
category: academic
---
```

### 2. Misc Services
Add markdown files to the `_services/misc/` folder with the following front matter:

```yaml
---
title: Your Service Title
order: 1
category: misc
---
```

## Front Matter Fields

- **title**: The display name of your service
- **order**: Display order (1, 2, 3, etc.)
- **category**: Either "academic" or "misc"

## Content Format

You can write your service content using standard Markdown:

```markdown
## Service Name

Brief description of the service.

### Key Features
- Feature 1
- Feature 2
- Feature 3

### Recent Activities
- Activity 1
- Activity 2
```

## Examples

See the existing files in both folders for examples of how to structure your services.

## Display

The services will automatically appear on the `/services` page, organized by category and sorted by the `order` field.
