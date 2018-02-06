<div align='center'>
    <h1>
        cx-ui
    </h1>
    <p>
        React CX designed UI componets
    </p>
</div>

<h2 align='center'>Install</h2>

```bash
# for webpack 3
npm install --save cx-ui
```

<h2 align='center'>Usage</h2>

```js

import React from 'react';
import { TextField, Button } from 'cx-ui';

class MyForm extends React.Component {


    render() {

        return(
            <form>
                <div>
                    <TextField text={this.state.text} value={this.state.value} />
                </div>
                <div>
                    <Button type='submit'>
                        Save
                    </Button>
                </div>
            </form>
        );
    }
}


```
