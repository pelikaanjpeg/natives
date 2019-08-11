---
ns: DLC
---
## GET_IS_LOADING_SCREEN_ACTIVE

```c
// 0x10D0A8F259E93EC9 0x517B601B
BOOL GET_IS_LOADING_SCREEN_ACTIVE();
```

Gets a value indicating whether there is a loading screen being displayed.
Seems to sometimes return false while in loading screen, combining it with IsScreenFadedOut() seems to work properly.

## Return value
Current loading screen state
