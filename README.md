# react-typescript-signature-pad
A [signature pad](https://github.com/szimek/signature_pad "signature pad")  implementation for react written in typescript.
# Basic Usage
```javascript
import * as React from "react";
<SignaturePad onEnd={(event: any, data: string) => this.props.event(data) } />
```
