---
layout: api
title: Checkbox
---

```
Checkbox.propTypes = {
  className: PropTypes.string,

  label: PropTypes.node,
  checked: PropTypes.bool,
  value: PropTypes.string,

  variant: PropTypes.oneOf([
    'block',
    'inline',
  ]),

  mod: PropTypes.oneOfType([
    PropTypes.arrayOf(PropTypes.string),
    PropTypes.string,
  ]),

  theme: PropTypes.shape({
    // Base
    checkbox: PropTypes.string.isRequired,

    // Variants
    block: PropTypes.string,
    inline: PropTypes.string,

    // Elements
    label: PropTypes.string,
  }).isRequired,
};
```
