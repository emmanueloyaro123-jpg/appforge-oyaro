
---

## 📁 **FILE 3: SPEC_OYARO.md**

**Filename:** `SPEC_OYARO.md`

**Content:**
```markdown
# AppForge by OYARO - API Specification

## Overview

The `window.iappyx` JavaScript API provides access to native Android features from within generated apps.

## Core Bridge: window.iappyx

All features are accessed via the `window.iappyx` object:

```javascript
if (typeof window.iappyx !== 'undefined') {
    // Native bridges are available
    window.iappyx.camera.takePicture();
}
