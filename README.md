# MsgContent

Render the content of a message according to its type

```jsx
import * as MsgContent from 'patchkit-msg-content'

<MsgContent.Block msg={msg} />
<MsgContent.Inline msg={msg} />

// you can force "raw" data rendering:
<MsgContent.Block msg={msg} forceRaw />
<MsgContent.Inline msg={msg} forceRaw />