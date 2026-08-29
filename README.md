import type { CSSProperties } from 'react';

/**
 * Utility style object to visually hide an element while keeping it accessible to screen readers.
 * Useful for adding accessible labels or instructions that should only be announced by assistive technologies.
 */
const visuallyHidden: CSSProperties = {
  border: 0,
  clip: 'rect(0 0 0 0)',
  height: '1px',
  margin: -1,
  overflow: 'hidden',
  padding: 0,
  position: 'absolute',
  whiteSpace: 'nowrap',
  width: '1px',
};

export default visuallyHidden;