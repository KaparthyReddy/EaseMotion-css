# Line Clamp Truncation Utilities

An encapsulated utility token package implementing multi-line programmatic text truncation via modern box-orientation controls without resorting to brittle string truncation algorithms.

## Utility Roster API

- `.ease-line-clamp-1`: Forces text strings to truncate flush with a trailing ellipsis exactly at row one.
- `.ease-line-clamp-2`: Forces text strings to truncate flush with a trailing ellipsis exactly at row two.
- `.ease-line-clamp-3`: Forces text strings to truncate flush with a trailing ellipsis exactly at row three.
- `.ease-line-clamp-4`: Forces text strings to truncate flush with a trailing ellipsis exactly at row four.
- `.ease-line-clamp-none`: Destroys clamp parameters, restoring natural content dimension flows safely.

## Usage Layout Structure
```html

<div class="ease-profile-card">
  <p class="ease-card-body ease-line-clamp-2">
    Long text block string values go here...
  </p>
</div>
```

Closes #12660
