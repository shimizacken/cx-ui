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
npm install --save cx-ui
```
<h2 align='center'>Getting started</h2>

In order to apply the style there's a css file that must be imported in the root component of the application

```js
import 'cx-ui/style.css';
```

<h2 align='center'>Usage</h2>

Simple form with `TextField` and `Button components`

```js
import React, { Component } from 'react';
import { TextField, Button } from 'cx-ui';

class MyForm extends Component {

    submitForm = (e) => {

        e.preventDefault();

        // do some logic
    }

    render() {

        return(
            <form onSubmit={this.submitForm}>
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

<h2 align='center'>Components</h2>

|Name|Description|
|:--:|:----------|
|**Button**|General `Button`. Typically use as submit forms button|